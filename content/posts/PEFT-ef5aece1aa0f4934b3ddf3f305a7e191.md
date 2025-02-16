---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663E7PDWIA%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T222114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjED8aCXVzLXdlc3QtMiJHMEUCIQDmk6IYmfI7ma5wTtNxk5jc3mjUf3%2FGl4P%2BvEtCuoBongI\
  gH6GcuadpE1BWdiUNHcAIcMA2I3sQ4dqwN5GvwXy7cjIq%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDD\
  vhes0wwdObGa6d2yrcA8AuQQ2apagW%2Fa%2FivxBKXsOfCKkL15wdf0PmCfVirDC%2Bjls1kCA82\
  uYSs%2Fe1qIaIYLWku%2BwVwWfHkSNglqj0Y0ZpftbwfOBUxS1OQkGCAFeMapLpsgz2Fcj47J9%2B\
  gwEiCleB%2BY6fWwmzXuR230xOXeWRehDN47k2Df%2BjWydUjGklwjhlE6Gtf%2BkmJJkm22yQznf\
  JPma87rlZrTkyjooUEKuUdjDaiTFvB5aMd5UDGdvJm0OwUoYgstQI7TmDC83GoECzFcAT2zqOJ%2F\
  YdLGwXs1I72tP0a3R4l3RBOQF1wdYXdvbspbMqe6FPcDUnxDXUaOo%2FkxC4HJzPJu%2BPJM1msTw\
  raICbwI%2FXrUejrQTNSPlYFJN4tXXk31vU3a6HhWWCWfa7L2CIQogKdIktngIBuCBcb2EhlWEzcZ\
  fnHbV2jzF1YSpamgSNQI%2F59nSV5hkG6o%2FR5OAT%2FQgh6Tpb%2BHq3NqqdcNllhKgeEhsvSHe\
  ZvSSzrDL5O2OV%2FTYk2%2ByroEcXGdUiXmgTHYUOEX%2FenfnOIzkQ9jc3VjpH33PctcNg%2FcZA\
  a0oNArauCe%2FFMUXbhDA%2F7Qekq7TlGM5NDcChEJejFWTQ7DH9D9Zxl3EvvTOGSvY68o62W8Nue\
  72bm6p2MObIyb0GOqUB%2Bi%2B8MUasZk6gBOZVQ%2Fxv%2F3SSLWmK0rsGQCnamZgJ3SHjxknE6x\
  CTaCLzag%2FMga4h%2FNIZPZb9wBuBxw6iPzXbCB1E9l1wa0KRYf8HMXdR4SFu2m465o4NWnt9ZOx\
  he2PjOxr8ozpyZsteYc9js1sbBFoMy3HS99wJEVCjb6TA2Css1GJayzoDtvFuC4jW9cehHnbp%2Fj\
  SICaEG3pOEWTIrXhmzFOk1&X-Amz-Signature=14480a5b5e7fe40f1bff8e2f4580912638ddd8\
  a456c8d46909913941cde9bfc6&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665AWOEHYL%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T222008Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjED0aCXVzLXdlc3QtMiJHMEUCIFN53gWnpz93x%2BEf1qDMLE4BgINHd\
        lHgFJXfnlCYfblKAiEAmIhUxQzjy5j9GS%2FsWbN8GIQfuuEmQavEp%2FLqGepLfRgq%2Fw\
        MIZhAAGgw2Mzc0MjMxODM4MDUiDNv2LpZ3IwuUt5V7KircA6Od0XwT3%2BV9V6pycQH%2FE\
        Acwm2ugmrvqpsRbgYdBXEVFwesr48qAs4Sm8Cml8r%2FY2SnbZ05xqNjgE5beYCxDfP4rwp\
        QuItpieZPdR%2BWkcGaDUop%2F0TURqoF4g0HhSt%2F33asG9LX8ev%2BOnqIv5m19oO3vy\
        fJMAoxIa3Di7z44PjuGYDGZOhsEI0kv1hcpv%2FtY5c%2Bsg4vGfyzJT57ZiILvm1Wmfl2p\
        C7v5alfz1bz3K1kTnx51g8eseOBIbrC5OQv4uT5TQ1J9IWyqk%2B9mKfFescINMrP5H%2Bj\
        v5rFy7cgs%2F%2FcyPH8hqIIQW8ew8Ls2Kq%2F23kcYudYd6HYkwhJreeegqoNtuJWN1GJ2\
        7eS2IMV0H8qqEBEydPbu%2BXGuScEvFQeGpdaJTC9gp4Z49TwTg6o5BEwq7UwiaKpiit22R\
        6vnTgX%2BWTfS6SrUO2JP3kVCwgATwLiefzbJomU7eGOOcxR%2FuhGteNEurM%2BjJUzPT0\
        5zhZsWkaAYvSpFLB2eYD3EA%2F7V1ER8pvsgPWTGWo4GRcCnHznyhoDmnQmR9CsmOtpStpf\
        W294g1P8AgBFLyByyuQUUGEZhPGr9QFqlTXn4uPvMRtFn2AqnkWRP9pKqM%2FZ2fs0Lsvpn\
        8LDHAwOy2D2KMN%2Bkyb0GOqUBgkXR2A7L2yw%2BaiiT3dQSPTerzqhlpOGrrG5OvA2AGdW\
        n3YRnE%2FPEooozUxDykfn2%2B5DN%2FTNogLe2QLoaFl11Q9p0CQ1VO6z1KKST463VWoXH\
        QwxBByOfs2Pg07eWGFXbh51fxwe9XPdYaHqpJvx%2BSSMTRX75LUe8hwpJ2YwmgM2SK%2BC\
        BQv8wxcSwXd1ZLTdxQ5QSY6%2FM7KoVC2pZY35FLx%2F9e1TL&X-Amz-Signature=39cb9\
        c230a2456786e75ad1f94730727a7f76313b21ea6622f4638c1adb51571&X-Amz-Signe\
        dHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-16T23:20:08.920Z"
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
UPDATE_TIME: "2025-02-16T22:21:19.678Z"
EXPIRY_TIME: "2025-02-16T23:21:11.672Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=0a99959d04d0e094a2671009e9a71a9f59698fc27a3cbfc77d404380b66ac8a0&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=3837e99b56aa43a8d9094ec1d489696406b0e9151aa2c6b8063065a4325a87bc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=eafc911c22683a15bf4d65b283ab3e3c69e84dd18392e38b223f76d5eeb7e593&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=aa96902ec8166d7aa1b04e6161ea1b6894b2cfc6be57bd8f322668a1c37b2c5d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=a3b64f3bc96fd492492dcf0583f585a04ee49ec8861c8e61949be934c109e285&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JTWOK2N%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222113Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCmqH8SQCOqCqNzwMasDE70etQi7ZMpQ2JqtKJUm6eyswIhAO5TiMvGEl%2FmzJ5kSmB94vFjG56PSroOsYEvkPt0fXGZKv8DCGcQABoMNjM3NDIzMTgzODA1Igyj4mydvz5yKFzVJZoq3ANR4TZLQ8QvW8Y%2BUURt%2B0PSnpiValt7Jg2WW9%2F%2BheFovnAWJhqeVPkqALWBo1gdMPXWgSQNnVq9Xn5vy2sUbVXUTOUbhL%2BgpsIlXdl1WGwe8v3hX0HglvuCE3B2Vxg1WcC57Wp9tEGI7oSH2nFWpOwrVSjzQVFOKH2BnqGnxEjK4YWF2RkEPIu6V5o4lfM5LRMkJmEpSikbDyvQZRsMt8pWz7AYnWi84QNz6xzsSHg5gYYJsP1EcSxN8tu0XUbWNRrJj9ewwOcmqRbfvoYNedqqdJHDVeS7wl7bBQyIVl%2BCuqFKaaqjv0K7kGQk3amVACfwffGArdn8krGvnxmm8TnpQUg2r4uDWsepX82okiPBlyCOL99k%2FhfsNcrW0O6HtqBNXGXI2YPva%2Bp8rQd2pdyU85VzzCz3lwapVDJrVx%2FTofbfeAKtTPJqbLMHzXEwgtb0v%2FZVDaVbLVoJWVQN8LwmlgMWrJPDqMeFsOwUdI1QI5q69QCkL2elqNwiUO6yOeYbqVYjZh8vF56H%2Fd2XgLbtP36lnNrND00EUa3PD9JGJG54SQg1fMIH8hKIzajLCtehRZD6u2wfJVMSWoKLmWt%2FgM7gI3VDRLLhz6HMoH8iVl27q434R6pzrFbSvDDYyMm9BjqkARUwcCzdgGl%2FMV7REU7hTKDCe4g4bTh2R4fysFvCReo9CVA6vROneGfw1ee%2B%2Fqn23%2FEethPUS8Sn4phNf9gDDRSb66zzhmQp0yu7EhisLlgth62T0oGAi9QYHgkM4MCpuhRUGH7tJVcoGv4jjcqUNx2oCWBj2VQpJeH%2BLDelti0QPErjf9XMIFNk02bHZHyRGS5HzAYJE%2FcZ7bwJ9W5o5dDdz%2F9X&X-Amz-Signature=815e2ae516ebb8245fbdda3fd673509ebaa0a53be0353e0271aa0271481ba814&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QROAWCAZ%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222114Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJIMEYCIQCSzlrVzGS%2BY2L5W8%2BX%2BvMI3u13AwdxIhK%2BIThdMCQA6AIhAP%2BXlIWbOuFLomaXaORO3ltpLxYtzU25yzHkaL6LzXGoKv8DCGcQABoMNjM3NDIzMTgzODA1IgyGoAm5ZHI%2F6xgtRFsq3AMAWjsZ2NZBMlhj8rkCQCApfwyEIYrVrrgzC25fm0ptWsbQYd3TpHsw9shwnpeaYHVeMybiQMxe4x764y2VoGgSafTDwSVxji%2BbgMdPWA0EYfK2h6KTLCXXp4oEzGv66ESjEFRJVA0DCmLrBW4rI4UNvxo1AUvHXhth7seT4NAQKaXCAeUZWlm0l9o2%2BoZ4IPlkKSNhuYF%2FU3gjrVOdzptZH6Q0W%2F0fmqpjaiaMRW3NEz0X%2FNa8kI9UUCigQGyl8jaz1t%2BC7fAMShg8sIPgnOH5pC0lbVvkPTpsravwmVFnw4PqQ2bISKH87SJXxXpE5ahRTlQnz9gVxZ%2Bd56VnfLl8gHOz%2B03c6l83qFrDopV%2FU8D1HTHR4LL%2Bso2xYo1MewIvwkbjKFuiovwnuxJ6HiCBVj34dNzTD68iO30cK%2F0lwxwgnd7ldK0cEE%2BAljq491d1s9BnA9jyDY2z2zTD8chu2HRt0iPAUIUkkENbToCkXuYYtblWEfDy49fTohdgEB7h931c3kZScP6882bBQN0z5r7NypPrSwl%2FaCH3I2%2FLW1ZcFh7lF5u0EobBg9DK7TZnumbTJsw6XACjDQEEwCTDPPnmGhvLj2epQ2bW1X83dCEak%2BZ9RUTek16KEzC%2ByMm9BjqkAST11ubMfYGU%2Fyrp63nFzhS2Ji3ws1fBHyVYVaderNMK4BEPIhHgFd%2FMXjkdLz2NmaoWJBNvZsnPd57Q63owTyrfrCnuOFgA1W4VAykd734lrZNu0xjghspk74gO%2FOpKjC3HCRmu1imU3GuzHBr%2BO25uhCc8PRAbpTrIZxIp%2BXDtPJ54tcvvlY%2B4WEkQQl%2F8Z5rNhfFAarZuoCJa1lPcI2N5Uo9a&X-Amz-Signature=efa66490f6a7925cac3d619b85c97f495d028d930513f012bdc3838ae8e34ee2&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=83629b1b1c21060137baacc9054250b273367f840ee12f1734253dfd418493db&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=f3dea8356a712b082c858800736df0169bac229276c3cc3d5eed4d92174ac0ef&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKJ2CQS4%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T222112Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjED8aCXVzLXdlc3QtMiJHMEUCIQCEjXVe7%2Fj5v%2FKE0KubnRciKQvFY7tqG09CchknwxyoWQIgGeD2RQwVI95vR0IeEdPfOgXdYM73DQ6wTw9ob1cQOn8q%2FwMIZxAAGgw2Mzc0MjMxODM4MDUiDMrs15%2B7BPawzBZ%2FoSrcA8yrA8BZLHDdzjP98phl8qNUctV5d5U6EtR6YxjeI8Xv8Z%2F0R%2FCegTjxrrQj%2BOo2wWQjvoZNMCNjgox07YW6Vs2EOfzv7%2F%2FlnJZ8XeOamfiaTQW%2Bvgz6EBuxqi3z2rHWKIzgF4Bk20Gvy9w2m2E7Aiz4eFhvdVnWcUKAlhLdDCL4s1TS3XpZbaw6yXFk1lVGQExPbBDxLf9eee3tXOwfu0ic915Xh0VSg16tjcl1AvK8N%2Bk9Qd0IySlh41QYgoOHD3pMQ4faLAM041PBgsdI3TmqPmR9k3LyX9jyaiWiFu4YnMM0LkR3CZJSB4Ih%2F8s5bYnSwbXIJsyV22lMuFEdCC%2BV%2FHbxoCiE5%2BZKXIQMU6B6De8QKxO7Wcf0QTXcPWEawSOvB2ZtH17qVVK9Ge7JL2rDFULev%2B7wBG92%2ByHhhm6sMWAnPr%2FneOgrDoUMZFeXFHzepNLVk97lIEvm%2Fg%2F%2BNSvW45SbSKEIdQMpfgCLDRPHjOH72%2FfInDkMwVty3IPzeWr0rYuYzN8Sj1vActrrlNedQT6rALJXBFWL7qL4ztJ5fsagLsuw2MxPeoJKd%2FI8tNY%2B2lUA%2FeTxoupLZmnSUMRhzaLkEJLVmLS%2F93N5LRjNjYjLx5op7OcuSvbQMOLIyb0GOqUBlJx22eq1spp2rmEB57VJAqaUp2Y5REh38dN%2F%2F1FPEgUFzLGyV%2B7PraYOkYaRYmx%2FKXnw4FEKMdiryF7RBFW9clz9cUTbti8t6DnB526h6z3uku2x1FjjCs75AgVLcTrOeOfN%2FKor6Jo1z7knZ45GmL%2FSHxLC5UiUq0Au%2FHuBBzjh%2B2pP2dzp0Vg%2F0FECdU3ylkAW6iOz4iwBh2knxU7VoEswSTi4&X-Amz-Signature=ed3e159f87e7fdacd95b7b008e58461901c7ebe7fb3027b70497cedab43dced8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

