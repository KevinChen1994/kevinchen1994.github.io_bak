---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46667C2LQBE%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T222213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICg8a1YB84VZYmRXu%2\
  F3ZC%2Bf9aktxJGwbY9qQSbDt1oRcAiEAqDCD8BnagR7fdbsZM6XVe3P0y1pG1GyjHH9KmXG9rW4q\
  %2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDAwlXnfvndw2T3x2USrcA4mUFDrjgi0p7FayabqfWkm%2F8\
  flRDcTSZtCoNC0w869BzpZ%2BThrz7Eq7sZa9faOQ0ZGBYk%2FS7McJe5II%2BoiqkKwzofxlYwZQ\
  btd%2BEASDpE7i2MENx1pAMDcz%2B05PRbuN%2BVn11SI%2B4vKzT7Tt2TTStJGW16R4u7kEFD5E1\
  2AhKJVfq6xKxxwywRrHZmtB9lgstkpf0G043MgDl1pqtw9gkJtIauH1DZ%2BWkvqJ6O074wz99AFJ\
  VcQ2EFzrOdKkpzVpv4pD9FuP8JF22IQBsOKAn4837kRP5d%2FsuM5%2BaKiry0L97PDDDPEscVkcw\
  Kzf3TAgW2kkcVa%2B21bg0BywqsI4CYmMCk%2FJCjLDqQQ1rfDH2ALp5Avcl44%2BC99oyBFQBoPQ\
  OwYJ2hSm4XR%2FbKQx%2BR1Rd3fBhDKHtacf4LtM56cIa9X3uLNtQGm4Xazh88bjyYK9kka5s7B5u\
  JsJCokCALRFT2y5prEi76kWmSCb%2F2Jlo6%2F%2FUNrsg0e%2Ff5WhnCodqiuZrq1JAr0YbesOPQ\
  7Q3pb2E5d9GVnHX0kL50SoEHnriGDuzlOc%2FR6kJZo%2Fr3pdJgLBum8i%2FxoJqT2Pd2yjYXLnS\
  ghw%2BgzffkTgNCaE%2BIxhg89echR5CLdA%2B%2BksIEXjMKWz7r0GOqUBVEyQ32%2FCb22oyN0J\
  xeJWDZi2UunQxnrZmbTo%2FmKsU6ceFf6fdUMkGiY4kgwwQj4SpoLsvBwkQFaVkoG4zWdegAsoFjc\
  PduQ7N65r%2F8vGRq0Wj8cxL7LwRKs%2F7tle5bjg6YcMUR0ReLSNJVGHSTS5SEDNaeeAhVyWIy3j\
  A5FQf63kyH54PFtO4E1Kckc2nE5R%2FmR2QDlJVcOoBOTn3J%2BsMdXFXsx0&X-Amz-Signature=\
  a6f15d600523c643ee355f80716ced50839af59401a196caf85bc790c4cb4821&X-Amz-Signed\
  Headers=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XKPMULBC%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T222047Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIGRbbg8ad4hWZbGRgWxkRB4qFMRYffEecKLHwX6ptfrTAiEAz%2BfCMuS7C5AO6pXEnnQy\
        6zonc4W8a%2Br357Cx8UUOihUq%2FwMIHhAAGgw2Mzc0MjMxODM4MDUiDAPl%2BLBLzDZ4X\
        Lc0qCrcA5IkbDRd9CQczGu4wVkRNa8oj7GKAwU37wTVN1X3xEU2hqddKkp3yAKSliET52Q5\
        6hvftSHENnahMHAqE1eItwgg7As3eohz5e1%2F77wf8hTAJ36I4cWyiYhyUxPgPbuQsgdmH\
        8Y4bbCNVvwzpY1M8XBTf%2Fudfwxug3mZz2T6%2FYhQgxHVvkhbvkSjw4xpt%2FdKUfL3eh\
        ZDLlAqbMkW0Czfzr%2BAeI0n9%2B%2FYgebcV%2F7PHnN1D0lfVp0dnJmK3bbIEQdWnztGg\
        w0boJsbSqdaytporgq%2B1b3oGLjbSGg9cPrjFbq4dNHi0kUL98cNJ%2Ba5axvS30sArFQi\
        mECH6Ovr61velbfQ%2FvD4YMbgAP7pilTgCPYzozIvKijVuHv5u%2FDyR1%2FXVWUBmJ%2F\
        xA6gJ1rUhngKhjFedrGDIVyHBPW9mG6gPf9bb7jT40bTmQXzmXv1URDbC46szCLPnyKvFVZ\
        zVFKoIrDHHdhst%2BFcvqaBz8jYSR5cF7xA0K5%2FdWrW63izDK4eM%2FfKzGjbOiAl2x7O\
        BrN7OkXSJ0BxxZy04rkPVEiHdzo%2F6gv%2BVg%2Fi9DiLIvr6psy%2FhXcG4%2FaYMqwm%\
        2BbgqLIw2dSY7IaAwOWCkIdXDEpsEGR4p%2FNb%2Fnw73sY5OWpveVMLuX7r0GOqUBB%2FC\
        AtxPZu%2Bd2dHp%2BF0VaPo%2BeTp6AdyvvHXoWibyvFohhABK5WUWz3Ugl%2FDziav5rax\
        TP7ykspV7P%2BGtBGBkzNObdIxaPAg9ueO9IZwQbAhEsD0hK%2FviFSpSB%2Fh5wSoM7hlt\
        bJ%2BpYCGmPp2AaaKGESKgZTSJbSe%2ByExsWgE0dKNueXEWIdvvGNrLcKkH1dZhzs81nhC\
        tXiN8gK0GGGILcN6vzv0dR&X-Amz-Signature=db3c327f5da309214a6d2473d5c7ee9d\
        50a7b8f88f588d6e214c629effd8d3f9&X-Amz-SignedHeaders=host&x-id=GetObjec\
        t"
      expiry_time: "2025-02-23T23:20:47.697Z"
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
UPDATE_TIME: "2025-02-23T22:22:37.175Z"
EXPIRY_TIME: "2025-02-23T23:22:05.190Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=1ac9fd5dad8e1d8abedff67e1ad6b394454fc4aa4c13fa15c800f7b2381100fc&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=b34646e93ba0e101a4f654b5dc0809170f498abfafc918ab5ed4477b1d8a6b4f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=9ccacb1d56768afeaf60bf41bfdaf8f0780f2142619fe88842fe65f8aa2d25c9&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=8e09fe8d44eacba45ada01e59e5a8ae622f7798eca03d19759ef7fca285f7ea1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=aeae521db8b6326e9b3a2eb119a4fcba1be3fc740d3d58b2b996b9fc200f2a43&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UXUELQU5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222206Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDoYpZkgwtJqisR%2BbuPoyt%2BAwXjvSEENUqhj9JPyORbZAIhALP4dACkoIRFFdzVJ%2BdjPVlFpFg0%2FPRbiYx%2FxMdBn1LMKv8DCB8QABoMNjM3NDIzMTgzODA1IgxVDrNHzn1sCmSur6oq3AOx3WGU2e223jxaoLi9KRH%2BC7H%2BVErAByBBV8vB1B%2Fsx8r45RMT%2FwxW%2BGQnFTP9lOxWiPA16mZZLZ8XJ%2FqiV2xMVMZaDyCMizomf368%2F59IF%2BHREN6fvPu%2F79BSz%2B3mr%2BZdyy%2BCbH7z5akD2MEaSdllosSlyDIpsHhSp7bpJI1HhLiUGmFIS79eoVhCI%2FTGa6BzSeAeYMZleCLxobN3zwQxlyvKqqEFvVK68m2a5X5cSWkMr%2FC%2FuJ6lKksoFfMstOkvEjMzIqgdRV7zFeQ5PeoPsOwpPWYh8Jg38qLYt%2BnO8efJQ3VjW49hT4PSTaWG0BijTDZ2kP2mMXwpJ0vV6ek3rhdIjnZwliNloG8GBLuiI4ouUmLMszM0f56Mba65wAYto2eyyBEnhae8QT23HZwBbitY1%2BQ9iqm9kJgEu1Y4q08mwQ%2B9ypX8hly62tkdeptuKZi8eu5X2HSUKC1yaT4kY0CvkdjU9axmLJnOW%2Fc9N3WRRAxoIhhdlnf%2BSYjq0EQnfyJyjgF8DCcjI4vchneF4pYxdneS4hRXiHVl6AfE1EhiU0217W3rI1%2BdMzQwmAxoiAsEgXYvuRwgIu2FyGhCjyiM1GDqd1kZqw61vI1cBvrtnZeD903%2FIqPfADCls%2B69BjqkAeCk5obS9%2FWW6KkIQUPz2PCfdOOljxZz3rOxtVaSkAm3M68MhVSqU4WuES54MJeW08WZOHPQjhW0bKsVRkOZWdC4Z7L73WReYmhd37WjwLwoPwc8WsHjcSiBgOPQo%2B7G%2BVLlYiOex0BfaQ8bAGI58yxkh%2F9HUx71ZAihrVm6IJzAwwOqiHERcD4DUTWKZgqFvd4q7qj%2FYK1XUKmGvg5CcdAaIDAT&X-Amz-Signature=e855036661781e9540f74a20c77f1944587a518e4d11df00a865feb0d73b1b9b&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665ZWJVCKC%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222208Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD7B3aUi6RVHnHywwZR%2Bs8rdwIgZJLTxf%2BoefzuYsyQswIhAN7lS5TiMtcEKd97N1ZRqVRKtPdRrDxmExV4DvmgDJeWKv8DCBsQABoMNjM3NDIzMTgzODA1IgzxkVGS2VmoELmVgVoq3AM4YL7RdlX1wxJr3rEEqVH8B9UmapoqAMrebEf0SXty60xJoBDQnMlQNWeqZHRIuQlLlIfKmVctWV9xLk9nV0jKfAEt16dZ6i%2BxfxcNrvLhHIl1vgs1YCEOw3nB0Ww6P%2FvuWBV8X%2BJ6mpTDtj4ol8H%2FEFPR4uy3gdTsyQcSHqcIkHGBNtR8HMEL6rFIftTOnF9OH1NLtdjZYEzjz%2F%2BS15Wi09ZPZ233vlDOZ5cho1C%2BayggSF4ohlq1gM3dOOP8hR4bImea98%2FhpLZ%2Bw4fuINEyScik%2BVBQgePxLeVK0meZYkTkvPAH4TRZcjNOgj1G%2BNaly7M4wacSg5U5ty4LQk04jL30Cz2n1UrNuMpNSv9rt5Orxrssdb12rsgoEbB3C69lDPBY8PrH%2BmzMBjw0FnMfUXKalUD7BjtMk4VG8tOIz%2FjjcYxgX7Wp%2Bw8AqmiZHk5q8naYv%2BzZjAewA7YN4PAgpAxBXOU%2BuEdvaLfCzVW6k%2B4F%2FTavIN196v%2Bi%2BcDzwnb%2F1FYprySKeqbjQQJjcJFte2e8MQPetNUQXIChNWO05pGkPLbIKYCZUYwf4GqKcujBPQ1aXMmeZotgt6Nhmu8MpV3GwCPJo779HD0AdtaxKPAs%2ByojCMOAytE3IjCexu29BjqkAdWgT2qzKlGr6ATgcG9XhBvtL074pjPpJD2a1GpakpXVkRpCJC9h%2BDAdpYnLmO8wkMvC8A9Q3XZiNyHT%2BColcX6jfNmHKKj0oKmpPJxrbpAPuuoY%2B2cU%2BKxUBOre0hXIPvsfjWYJn9zX%2FeGAhsGeAwMZcpi6Z8MeN5jywEm7UdjPeTfLhWZfIuKGBmUgwMHLTIWsSdYzfq%2FiqyU4wpZ6zU1Y87b%2F&X-Amz-Signature=280bd9149a425ba26e38388a783f224f1794c8f218a6e9ef39146f974c68d130&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=e26b5854c6c455de0e61c3933ab770959e2a109879ed45b0d3d517094667a7dc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=8eee7f10594edcf1fc74ba13bf1f9d8527fca1103765a95e6e7a9d21f9db1e9b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667NYJ7PIF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T222205Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDre%2BgJ4HaJxfNldLK6pBH3HBQuB4ENSsj1WdUDO%2BZx%2BgIgGf6WBhm7J5EP1t7liEexpZvKuzI95TxOsZpcbAO1%2FeMq%2FwMIHxAAGgw2Mzc0MjMxODM4MDUiDBEzxi%2BefDT0kqJPfCrcAzVFXl5dzOqIfCtd%2BgjveBG8lZlGPFjceoznrz8BK18lfzC70TLx5DfGdA9PehfshhoMVX91qsnFI4xc8gB9HvVecsbqZ290tEnaAiTiDdL7Nim1nX2mcSdUQb1mQ7DkWikO%2Fl44yjS7bxMTvLHMHVVF1TEtccJccZkqYCvNgq0R27BV7Py%2FrEbnBcDW3bXgzzhCC9hcRUGF6U4mrMqxsAMCR816vFB3KYzd%2B3syLzkFiovT6TUwFres8hQFgUUqM46KBhDskaZnd9p6EFwPtih7F2gE%2BEWj9h7wUfIueWRepylUboVa5m2LL9e18zVqxLnnDmvqXyDgU5q4OAGbJged29BVN3SbnyFnEQtbsH3ugFw0Oje%2FplBcrq1oWSlfPvRD12tY749iMXDEjlRgk2FDoL%2Fpl9zzJBAkg37WUIyW66EHl0P6ANi8eiG70DgJ5nn%2Bmyg2lNsMGS%2B3VwdpLEjtkaBq%2FcOT9utS2WDSAb6TuD%2BqjfrwnfNmBNwvvYbGPbbkcFIV%2F0AQ7pGrNLBy%2BOoU74WWR0lruz6ZqYwLNYqdDeNqgJnxQzOEU2aTxpymJ%2FBqn6VIxAeSmYOv3zb3OcQWek9959vQH66pShd3OvBi7a4CinHBk5AfDbV2MJ6z7r0GOqUB3akW6Fksn8Y1XIvHMcZkV74nDSsMODn4ObVOA%2B8nNbata0iAd2LycRuAEa6MjqN6ondpqBKBgCeUcdTA6OvPoMJZGf9KPIhyycgKk7fa5CyFrZYL5%2F%2FSAgnio5XuQKjH4xC%2B8kKUoZkD4w7NH8Bs%2BwUbF6nL3knJ%2B2y7CB12QCQeFtFN%2FysK4yFn6gyvSR57M2nYFygGtWiwUgW%2BROnI8NzEhVWY&X-Amz-Signature=6b4eeeaec9f901d402efbb11eaca49327676ddf428ed1f2a7bcab6d3402c6f1b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

