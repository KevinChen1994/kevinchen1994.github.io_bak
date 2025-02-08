---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XNMLZ4IQ%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T132325Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHQaCXVzLXdlc3QtMiJGMEQCIAYGSd5qsX2nek85btqdwto%2FRZ151PMdHKkrRllJs%2FRJAiA\
  XTKvmGuXhC0RDK05C%2FyPVVAQNcSvIYV8ck6lmgQhsSyqIBAiN%2F%2F%2F%2F%2F%2F%2F%2F%2\
  F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMEiPQbd3W%2Fgt8hKw%2BKtwD5VKpQo2CwL7rcflqHC8nP7R\
  jyhLDhk5Kfr1%2FsCn0K3zx2imRi8kRvfHUSWH2Y5yiquDdTpWrXXsozwunBe54yxWZHXmvADQhMY\
  OuRLpsk%2Fwc3xIwBPxwXQMdM%2F58moe77L35ptUE3Q5FX5X%2F8wHZMDScdv28eAqczEssBMkGC\
  H77iS1BcuaLTOwhgIMqq0uFhJSywZSbZY5CKvouemyGFYKc2TtNsSZxYAlISqAnb1xIiieY2VvxFA\
  jBhyGbJ7qFX9xfarCRHrsDdxc5y6vUah4gDjGgeati9gbSBWSyh4PaR9jl8cD09BGkMaN%2BwiMUP\
  IOyRpgSPALeaUx6P3%2BuAlCdUrmpcruuJIYZ99DltE2y8lqcqFy76vpq7OY9nfGtSL2HAhdlohiv\
  J%2B7JRRFWyn9PHOtQsU983ft42xQNpDcexdMs76QBX2uKQns6Sq21iEk5mnmQB%2Blf41ZNB2Klr\
  fIKXgWk63B%2BaK9pUTEY6%2FxcP3NxWyYG8DZVJPn61EoWcRdwURawUtvMBTUcByryn8q6iaGzd0\
  QIGfrHopF3pjA2ac9eSWErPIcHJl%2FKrr4oe41wZ%2FlRSd12UwozcxKycGu3Jv173AgVxETqHXf\
  F3tgWEA2v4efyf11CxfgwroadvQY6pgEWAQUFUcSkSFoqWIFcCK0imwJxOB8tynFd9QIHb1fYoqVc\
  FH0lQtB1lvs7%2BMNZC16EchBnQV3YDb%2FvNM%2Betp%2F0OmQVAJaHk4dUQq9RwoiUmqJs3a2pw\
  7t8MgdqVGpT%2BY%2FpGi9GvSllSSarU4oxBmU0kC1mUTdH8pkGHBAH9HQWqfJ91SQ7iZvuSZARkj\
  cdHUFWnqMNcoy5OL9PyvWNW%2BoTWIWOzGcN&X-Amz-Signature=bb726cc08b4c512bd09f64af\
  2f710cb745c877366c30540c7b48544f93713ef5&X-Amz-SignedHeaders=host&x-id=GetObj\
  ect"
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
        redential=ASIAZI2LB466V5DE3MDA%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T132203Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDz6hZENPmOUj2%2FX2XWx5DgIK0yx\
        %2FgvOSlb8PdeFHxBawIhAJO4zVvTIPKTeLg3zxHkTguUyruFBInPiGBop1oSLZoLKogECI\
        3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxj%2BO8b1RPB5R%\
        2FSPwEq3ANrag7AfVVLp6aVeh4WMxsxKQInECAp%2FL1u17ErKR05se97jS%2BJM0r72QOA\
        S1V5k6dBvWLfrFC77Ws3qW61Xu3PuZPXzThTTaT2NNPR%2FaBNi4x8Mr1wtyu%2FrFKsMSn\
        EbcGpoGV9T0wj1UqpQYB7el8iDNg4Aaq7TMekpo7UK9YTweEMEHxjo3fJtC9Swjnx9NMP41\
        iMn%2BPY4sEVRKcNOUa9lgxyANJ3hlLUkfDLXf0LYoFfUU3fpg%2FctidrFpZXBvJUxTUT4\
        Mufki647jWQuSxle%2B%2FEiIxHSHtHoEt3UuCCSnA8l9F6ZzhaHDY5YlY4aQtTSlhmWTwS\
        bqnCaIpusoOz2hxQTMzAfA56FuP4Rs342mDd%2BKJvNB3mNvgYXq51kKquhW9yRl850sQGx\
        jSP2QiSUX%2BgwTeXt6Y1XFN%2F6FeKmlsq0c6%2FdOJYuQTvQgXrxAMvtzAqLn5acDvMAI\
        W1eJoUO3N1HS4r1qBDseps3dfNnexU1M3Pfy1aL4X2MD6k10tCdfmJCPNxQyuS3xF02eEzZ\
        kSWwxLa9%2BRmZqKzkcp7g1b1WHCaghH9Tw9EqKPVZQz491Lm6E%2Fty1qwnMVKbYsIBsgl\
        dYRK%2BsPfwHx4iXorIWqITfH%2B3pRblumQ%2BjDKhp29BjqkAXR4VubU5nUSZ%2FFi5Ty\
        2ODtlVhnzB1iH1v5NJrwLXxQB5%2Blh8Tm7tMCbBqaT3jgGbHq213uge9GFJOkTmxcvNA%2\
        BPiJRf%2FAVdrmnuMF76AICFf9OM8SIyYpq91uHePLWA%2FIOKb%2BDbpJD%2Fnw%2Fa%2F\
        ZaHr1%2FUtEtoY7l1d%2BENSUlc8h9EFk05j0chaehEDWW5OXMuHU52zkujVpQhILQdYdaq\
        60AluGek&X-Amz-Signature=8ca87688888339f5fd0ee19aef222d32da1b1fe63c3f67\
        d34c0353b1df7f6e6b&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T14:22:03.799Z"
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
UPDATE_TIME: "2025-02-08T13:23:30.689Z"
EXPIRY_TIME: "2025-02-08T14:23:16.987Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=eda7ab5af4502b6120f316157a9df7c8365a1312a35f131e5f1d8131e8bbc35b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=b4e1f340da08e17998ff8785a6ad7d31e4c5167ee27d4997bf661c5693bf1669&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=723f8af28bfd4679120e37a683885e73419789777dd4a7f81916c75fb0b1f29e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=12460a51f5b142daea3372412f94157a3e35edd047ad424e9bfc0dcebfddc099&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=3b1ab41670aa3c6e4b70be6ba89d62b43bccb27eb056d4b0194eb06574db57f4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635LRJFCV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJGMEQCIFphVELJPuSVEH7tBk8wQ3JVPHMWpowlBnhKRti9IYsiAiBJW7miwhCqWYW8GO2qVvTuIOf9gRCI3dCl4b3guKPnjCqIBAiN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMadNxGDp3Hbi9TVgXKtwDs8Dn3IhWhflOYsuFMCvUdSjxEhNNrZCjkTfByho%2BvLFggWue0SlL6M3IhiYzNqzDbz%2BmqEemB3R33qQ1bm7cSnqAiI1VAJmlT%2BLmdQGdIDOh9DypCRc779vgMkS9qzW8KT9ndpZM2F0fQMVfdvfKDEvw5NrobL%2Bz9EwxhFQWOPnLnwR29Eoys%2FrnVVDgtIjZr11ecME83awkr7uELaxDTaHZS5I5mnn0TCIuuxMXna%2BDS8JcJW%2BdyWba2LChET3ELUAEYIrWEqF30c6QJ8Z7V2%2BXzmyZJI5nmP4VILUZ%2Fx9u4JtY%2BFVnp4fIZF%2FPAzXmawneotXWtJODkdRHqjveolhIcOFOCKM8stpeVqBwd1nf1jg1DrpcmEXQVQRI4ZfehFfgkM1APUt8y8pcOsC5mQHATpKNmgq7SNhPRH48Bco3oM%2F8VxJydvAq5ppxIuM3HU8vIKVcopjbox1CUnRDn%2BTCoofHsF57O0qPEaYfST57TKr6sOKNC5liXbmzh6zu%2FlWk1bUSgk3mwLJ5wkFVfdoasmHZ8gWzPhV3EJOTt0luBTKPkHVc8xO0rYL4%2FdFmnTlNujwtf92MdorCiTHEma3FUmLgwu2bpfQgsbnkAp9%2BlWMKLIMwIsGknzwwq4advQY6pgGXLTBMNAN9Uec%2F03K85pTL%2BGBG9ygXUaEoK%2FWdFv4zaar8VfRUQ7tbbXR%2F9znZpnM5TOch0ymnvALopxlie7F47ET%2F%2B9OmbL3tTak3kbG0spPzXmqmbW2QcueHVcV3oJVpKxYambWrulIDRAbDqkyn5i%2FaDNWa8l9R4IBmWdkYdE4B979djNPdI9Muj6kQHP%2F9niH%2FZN70mCqSUGOkq5m%2BXSAJVDu7&X-Amz-Signature=095797a0078ef4d34a19d0ff0d90f921443b519850fe76ee467de4006ddf6e3a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YOGOFHOV%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132320Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJHMEUCIQD3x44QUWHvu2x7cUA149ix3EjoiG2F1jPEmeTQu2fmdQIgb0TXze2%2FpNlZCBepJ1CE5KFpKMlWqOj2V5grkWaIswgqiAQIjf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCF%2BIPCmPKVeKJzsnircA2m%2BUMnCvn28eOOG4Wp9TDDMcWmpv6HRz8DOE3F6Poc6wj165%2FrgyzIkIeE5r376CISESjpzIkLs1LGGtqmpabfGf6hHxvsy3nLGRFOGyRDL02Ou6wdTEUqppjTeBJTxd7pgIZXBZMrEUz1%2FnM7yMyGhPT%2Buhs20Z86psoVz0km0mHNgQhXM%2FH%2FihY6v8ms8WwTZ5Y3Da%2F9KlHJ8T%2B0ne4MbZs0K9uloEZrWVynZqw%2FPDDPwZ%2BgheR%2B0MrrEed4c02jREw8PC4VlUTuDJVdaM%2BcTpSEJofPEUdQG3bPmKbC3X5EczNmgyEDYxN8pl1p372WFsz5F5RiL8VjX7rEXYYsjlJhZzPZ785LdRmh16oipI3xrY%2BYkbseSHLYJTRccfJ7ggKYfFasztqLSARVizfZlCNQs0kqlqlfJItx6oB8RuzsnxJAFS7rrpdBgmJ4%2BOO90PAzTqJYbLTnjysharSCePSBBzGtuTJk1Y02Y3V2nmaxzWBHU9o%2F3yblf0jF%2FTRsik%2FRjGY1CPE6lih3vKOXvQON5t9ZzmQ3R2OGnKGEbi0BeJJbteCSbxZfHbdGuM2rdwo1vvWsEDrMgsw4iRsWfwkCDlWH7JV2LpbmbgtKG%2BSltcUvDUR2bdhTtMLqGnb0GOqUBXthwhDZnBk4Hp7Ux5Qoq3GYgB8fc3xBCdxB04%2FeaW9yt9D1CXGkDvhczP%2FJckQQaSNgySS9SiNTOfAp1kzExCQ3UojTQlX8HWMeYpY415TcFJpBBexiL0Wnx%2FUpfF6zW7nBMysdBCec%2BnpiXMPKkbsxHIHsc2iCSwvI1qsUwNgV18MSkCVcsNO9kgRXlCXvzuIvVFMZUoDo6%2FC6GIagO%2BPwjBmg7&X-Amz-Signature=4f844fc9e28d888990eb23dd2b47239fb20f9fb92166ae9fb08d50b8a31c4b40&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=9cca8debc0f4ab073751e6316f264886a98e0a081cd98c2c12ff6723f136b103&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=fa165cfb88ac91a6952e54a8fc298698223688234c3e172543121300f7142c24&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666PQXAVN4%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T132317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHQaCXVzLXdlc3QtMiJIMEYCIQDAUO3e3101xlELM3txppe%2BmpPT7p2JLiSMVJoT%2Bw7KVAIhAMvtLsPe2iYWJvJ1NgU1tMprdYPpYt6GxqWb3qXBV1X2KogECI3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzaQJvNwVUj3dxVpmYq3AOA%2BLWeVXMzC%2Fn8y%2BDpKpffcOgd9Oj%2FbEFgF81ArPoa4gk2m1xhVlfcJCQR4COi092Y5vfFvZvjY9AuMyv%2Bk%2BeQlk9cnOHE5QpH1eWE%2B02CmLJQbVXlMY80V%2Fdb85Dok%2FtIzKnHw0%2BKRGGD71RVO%2FrnrUkl1L6WKGZNghBwAVIxvmb1S6WbpG6hs%2FnOF%2FznxpgBfsm8GduOUNkVpHmAt9Ql47Y7MMnHtBVI1jlCTu%2BW1BospFoGAW3En%2FgcXI0ZvhD%2F0dC7CZazSYixzWKjyy053U7kaQXol9hhKPoGYP%2FX706RooCsgvQA7MqE1vV1VHYHuF77VsyNOGZlfbd2TYwx6anhnoWXUcT%2BUkkoSCk9obrmh%2BxGWRtWR%2FTbbEkMYo5Lxr9dTS4m%2B512dfzUwgPMXC1SPCgYgmpc4yEAqeOB0f1j9E8qN9jRmPiFZwHiLjoi6H8Y%2BuBBnJn%2FkeFFU8rWfQ9sFOe%2Fi3KY2PIwcsxA5hEDJ2W7MC2u9Tl%2FXpxWSvNpUTNOKuW9uVtoDN%2FzxzindqXU829H%2FyFxas%2F%2FKU%2FeRtfYtW%2BVia30n9zF%2BS1nVnlBHnb8iMsH%2FUVZ0qsTm5%2Bj0xmVXTl%2FXd4rHOEoq3JSuPZTLtcA7ciZ9oSTpzChhp29BjqkAV90JCkktoFRfLm%2Beu2CE4Icb1kN6godH050l6HhFKvGRe0Nfbz7OySUumFeopuO6kV8lGaW%2BtjM3r7ixGAoOelGj%2FnzBGV9xRDi2UNFWCqsznKTf5iWXzjZP5C3iGmFz%2B3cNPxaX48hdLRE2AtSQRmmhGFO3JqUomDfdYR0xMLVBClszHhXNMNpyERxDP1qxgNS6gQhnR7iCPtn5wOMGxaBjfTx&X-Amz-Signature=f602b17692b2edec61fb9167031ff4b98bcac9b49963220a266ce3dada00fe9e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

