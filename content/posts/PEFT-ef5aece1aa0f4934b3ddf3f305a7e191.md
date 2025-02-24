---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q7GWXTFR%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250224T212216Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIEGLDjbAWb0xu3VNOok\
  AaQh2XIfNq2SRLmQm%2BiLjMeEDAiEAmIACJbBJvfB9JWprm4hD1YR9W7yYE%2FGEiad1mnyAfG8q\
  %2FwMINhAAGgw2Mzc0MjMxODM4MDUiDOaSpWdK0fbO1Z2%2BSCrcA5dBsp4ZiR1f7Dk8gtrHMK4ND\
  %2Bas%2FRy2iNDrOZJEo7c5aWFMcbGLT%2BTjCn8Ix2vuGMwelFbza89xR%2BbV43eogefmHXTrf7\
  WzyjH2ypS%2BuhV6TwA4bMKeChr8SBUP%2FtWok7m0ATMEaudA48F8ip6LH5Zrk6AOZlAEbIBjChE\
  6Wa2P9MsTA%2BWpal9cJsmcdDHM4G36UHdn3bSAuVxb8mZf0P%2FUylLgcrcZTeCSgXKjQiEown9a\
  XhKgjUn%2Fl851U%2Ft4DyWvaEPFWSY65qwPGb0ml1o9sU6XeZFdlPSMiPRI2O4yMq%2FkI8IONlY\
  4BXBk9Ac13L6OhSQ861ZncPITw3EySViJAGytJ3cRgN%2Frsof9Za3II2mPXsFUAwWAD%2Fp2IUJE\
  6g77gTMqZjtun%2BoIwCGVdbI1nY2uEkFq9d3IkvVeAU2ck6BF7DmnAhH8kiAjHybcwCH9OvLculR\
  YrPCloXaft73wo0Ckd%2B8zWfljkNdR%2FcH8Uic1gWbN%2BQTtNP3Gw9DMq3vEj%2FKHHouFgH9D\
  d1SX3zA3WzCWxwpYPz5rVUajUN0fldE4w7je%2FWfTTBx3eDk8WcjbHZGP5HVtUgPA9eh1oxrtaOR\
  g%2BRPH%2Bx2dPqy%2FrhMHcZ7VU7y5J17t8vlVMKm6870GOqUBt%2Fnm%2B4TfDigTFuZF6LsEvy\
  F3bGc%2BnZ9wTJSv5YteI7LZs7pQK4AMb6WlUkhvkr%2BdLjBdrQovqKBfgrevxWFgoTN3dQDpmcG\
  HdlQcPERnIsaQXFptQgFWxg3i9jzl2LX%2FGQPBcEDdNQzBgjXt2Fa9u54N3w5wPbpu60jnaw9kTC\
  5uDqoV42eAn449hClsb5gtNH44atmSrg6fVyq9rbMToy7CKSFb&X-Amz-Signature=53ce4dfffd\
  53cb768d1535b9e9d2edfd325353f354d638c9c723bc6746801b73&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB4665IPI5OA2%2F20250224%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250224T212029Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQD5zQ8DjcWSiYlneG3Mo6KMFMVbNYgNe7ce3fY10bcCbAIhAJLj%2FdC%2BqiiyTK3B0f\
        55CmZXbHsQw9W00pnHJnTyqWdlKv8DCDYQABoMNjM3NDIzMTgzODA1IgwNusY70nbQ2WeQp\
        j8q3AMHydbFZI0zM4OdKGMc%2FUaGhHiNTvzfnEQ4mGd997CGsqYFujSCa3HiuI%2FmH6kl\
        %2BG7MR%2FBVvsGACk0RnKSBglfLJ%2B1LaX6WSajRx%2Blmq9Y4b1OosaUxLZKRIy4tUCN\
        0d7opskIUdQlW%2F%2FXWRA9m8s4ft7WRN4BnE3wiL%2BYh4ZjFgP%2F0ol9akMm6UPKNFh\
        3HJsuXgdeMzVgRnL%2BwvjiF1o3w%2Ba3G8cpsWQUZulVDKJFy0FyO8jys7vUP%2BMlgfUh\
        sZNvfQOo7kDMII%2FDYv9xte1s1j155zyQVYRsKCTK%2FicXBLKY%2BKxSJ5aR0jF%2FyWF\
        nrgchgkmbXwMmArRjm1RAaxgMd0CHWHPkT8smUt70keOjPN6tSJn3JNV5%2B9l3Llv%2B7b\
        aXxt%2FYg93pXFyJ%2FTKVBDMnvckLulPXZuIM6iTqR5zgPlmUXQZfiVcMEITFrmKRgBTag\
        6ljyUHkDLKuNKqjkTiA6UrncKcf0wCpjQu99nJPup0oIpeE5zUn%2FMALwcY2Xz14RFIPcx\
        FlLTwpMbLsihGwXU0mDdURQr64HsWe18qe%2F%2FPVUbtHz7cD%2F1%2BrQPzHFI5Kxj3%2\
        B6Azet81HaAIJin9pmUTSbItmKHgQ%2FfBe7P%2FVBP4ULRCac%2Bt%2FwdvzSZTCLuvO9B\
        jqkAbF87va3o0RecAkVHc16jG9FtfXJM%2FhkyvGy0BrUocUOUYM%2BZJi%2BZGwWUzzXYn\
        DRTPOFPld0bwwazw94hkMDDHl8mZwQLJ2dAIVWRqdf%2Fti99mp37xrpES%2FeSBuIkjXE6\
        WCsbZ2GMexu5ZIYLPKlBbjUyfaffC5RqPzXt1qOzlGro5jmFqYiOa%2BCAEO2SL4nFX5%2F\
        yzm65ycudYTDPuxXFa5wPIQi&X-Amz-Signature=6245c9c3e9902b133545cc740d1dd6\
        4c3fba65ed56865f829510c06de842ebd4&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-02-24T22:20:29.251Z"
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
UPDATE_TIME: "2025-02-24T21:22:23.412Z"
EXPIRY_TIME: "2025-02-24T22:22:13.531Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=8a9d803f388d64bbde85ae5a18bc4c68448f5fc109036c12c05ae6a5da7f64e2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=4e95746e952e1e393e3236fadeac5e4771b0731f7e86c8a73c4aa5b623641f8f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=12f7e808c69409972535c1906942d1b0cbe4ef652f4159f071d7330d5aa9fc64&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=3f04bd7e76e573c7fb3368a1af00530b9f76379c4c3495c8de3721ef5638baa2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=509590fca0a702e5414ef4b5d87078e0ba4534c0a4358b6eb9e83f595f80f90d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q6KLYOII%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212216Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGDhggL7xHFu22wr131SlewHcyRq61Atc7ZA92g9B1tbAiEAyu9skQTK%2ByLWFUP0UaTD8fyZytjnI9d6yr6LYimJuYMq%2FwMINhAAGgw2Mzc0MjMxODM4MDUiDJ16OwfwV9O1uZAo3ircA%2Fpc7AxxlnRhghPWgzPsM9DQqnJAkuERE0TdDW%2FZP5F5rlPupkEucHcogpjWqMns46lOCGUHWBGk0MUTT9CtgeztLO9NS3N14XJNrYhZgatFdEsjWE7npx%2FmxnRWYFbiRnUIUbB%2F%2BNVay%2FJOqEKYz8deNRG7EAZMsNk05lfrGBv6gqNfM%2BgHbGq8OkYPpobx%2Fx%2BaIOnGzAgQdtKcf9NdD7dyket%2BzoMZ66nsyej4p2TDzBarl5bzFdLCntq8nBdasa6VZCAAMRJGo6b5JQNVzpjJvhqA166ttqtCcW02g8or0s%2BjTSXy2zsueUkZ2clKFRJ%2B557NYJCYWDNqf0o0J67NQEWqVZpe2tSYWw3KpzJA1uWpLf5xMtQNofI%2Fa6dP8Ggyh4fHjMZEZW97njdPidBwBCNVXtZSqCZfrSqJbc0XM7JGI3miEdheurymfkwkfngPvJrjg%2B%2Bgx1MPalRW3IS%2BxMhOBsf87iYVRX3B%2Bkmze5NWGwLUAUWoHsOfGiyOI9rY34hYkx1LRQvKIgRaGbYdbIE3O%2BrFDo7eiZe0U5gYhQk4jVqafxVzwrlWaDH47A0%2B63S2BvUNllTO18a5%2BWfJDwttwSw%2FICXTLnnn3597piopSiChIeCO%2F%2FzpMKm6870GOqUB%2B7juvC6t%2BTQV3nCXd0K1fNXcr9zpIHDYwsIyhCwiu1VdOxvPs%2F%2BprtH1OHFe%2BLSDijuRJKjazJMkSWobD4qMFWy%2FW160FXPkPdL08dwqnQaXIO9DgeQBtTJ1dZrC4ytRa4BZY%2B5z%2BVrUZ4QJdHb1pggG7pBhnGX9kcOKW5SbDfWN9u%2BAn4p7nHxGiRCtrUVnUcI0%2FLW6KFKqfdchMrEULuGCq9GM&X-Amz-Signature=615c6ece02b0a8eaad28a6deaa9a5f2da5b095ae4b607e531fc51b8dbfe32afc&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WFDSSP22%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212216Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCWEHA9MDDEnH4UqdqieEsiap80%2F9zfd3i7BDOZ9sJUgwIhAP5ZCkqonCiqf4MNPxQT819PaCVywo3Ucg8qrXJ7AIupKv8DCDYQABoMNjM3NDIzMTgzODA1IgwuK1AXAUB1XI4T8XYq3AMi4xxTDoqCzuZzl%2FtCJMJ89ksWEWkuiR3xB1kZqhzofgFgtox6MVmX63qUjoh5h%2Bv%2BbmJALYhjRtmwYm98scqCcwrS60n7gfi1t%2BOdDGyO68nCw2pCZ5LViYv0N8G6wMefdIkTaiUhEZaeVyEy8oEKfeFC0UCTsF3%2BYfrgWllgAbs%2B6a6KDdsD8oD%2B2JuznFGvk4CB0AZnc7tISVXZ086fYUZ0e2Ij8ahlRen64pVaQdRa%2FlGsc3plvjvSToJH5hIOZ4ZqF4x0alISxprZ%2F900pc6Umxwr%2BIaEO2zKmpdoTLICxHXFYAqvA3tvPntWoS0iIoJwK9lOLIZ6sSrBDxObTnOMGvu1WLV18o7%2FJFzc1kgWWaff9nwrUqLuhgPpg%2Bpc%2Bq4cx6nXkOOvLw3GkMmp%2BFVjDcXlacBF%2Fhgwbo0J2HHOBXCUmhX8mE45J7e2FgOsjRkUVoI9sfh9nGtz2X%2B%2BgazoG572k74G2UgRcaLSJ1R0WETJ%2Fjb%2B3tSeFba%2F3UxmNR3QHg5mxdyMFFYm1XqpctuIZnIGc6vZJHVHYWq4F%2BAwbDBZLB8GzZklqkOVn76vLUP1EniLG5Ar229ITGbf0K35PHY%2FESmAOylYkoGCvXgFKNIFOq4EstU3OTCBuvO9BjqkARu%2B%2FTDWr%2FVD0VxBo1LtNG7e%2FeoLKFwA7R5ZnUrm3ao9%2Ff6O6cPlINS1IFarwHaiE%2Bxo9bu%2FRK1Y0SbIZZqJNmROU7jr9aQ0KZe18yrETGEPO19aRrYHVwRCqFkEFBx3JpgxA9HulXjTquFUsTZN18cQGDKjMBjItt26%2BP4RS45lhiapp8fgLGCdAHIKeES1z4Z4LojURFJLaBBs5XYXRdUGrtyK&X-Amz-Signature=5fa9be7272a56e0ff79f99c1d8f55dfdf560c0d72dd6efeae3982c60b7bb0447&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=7163b834080426189ac5037c0e0eb655600c72332582457f17f87f561b853765&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=f3bbe240aba333ec88cfd9a8ead298c2e23cc1d35425889823a5836e74bc7503&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664JJDX6WM%2F20250224%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250224T212213Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIB8vVbS8FRmaO5bqPyq%2B7uNSP2ian699indm6m%2BIVHKuAiAcGODI070Fp1hjNxgCsOGGrXbZ8v%2Bex4jaXaiTah6S7Sr%2FAwg2EAAaDDYzNzQyMzE4MzgwNSIMK2LmRvQY8O%2BH27lMKtwDGeIDQ4HcsZDkInb5nqsSTucSw5DJKdUJ16GfzbuHmMp1gHuTSYPXDh4Br%2Bd%2FqHGQQTzOjxqO0WWqgBQSxxxIhINaPB%2BmWg3vSlyfNuXEWMP1A8KMLJboUD%2BjZj8I38OBzLxS80knN4NTp6WT0WCuBoroORUpqQRmPqG%2FvuhnKDvdKYJoGJteCkA7XOOOE782WLD%2BlVKpAZd4wRKOseZjIdFl223FoSTbIDRuqLE2%2FjiYtdvVJjmZEaOgfJTSVJ%2FGwrN1nVePjKAh5QoeUXLr12aqkpslY1ojUs78TO%2BRWUDCoVqglNY4sj8Up2TNM%2FDTq%2F8%2Bn0RwR%2F9a3KGgWB02%2B5QvJj%2FPO57Su%2FHLDq3mT22mBJub00YnkfRZy%2F4kp2ksSPMO4IwU%2F6YzyJixGhtdJm%2FCUmANp9xb7FcYN4G%2ByqOqzbgrtlE97uB5UUavQC%2B6l8LwQTFGDfimHChBsY1L8o%2B5UGLxezIfA3hhtcFlwjowltMPmZOOUPXdLlyMzWQdoPfH6hNf79fbQdbgt1fy2U%2FMMqGrUoJJHQpS8BcAOIYaKm7udQofyX2%2BInLV3Mpm3J%2FBgIyw4WiuLKSX0y4txBWP%2FrqC2x24x1fmcK2lhyO0OdvsCntn%2FxXtIAwwjLvzvQY6pgGqH29EnU6BLiOhg0nFULM6FMK6CKU7W%2FTsf%2Bw%2FV%2Fi%2B6EY9UonpbCCjK5gUWd2n2kV6kVF6VDZ5QSlyeJgNrAewC2Ip1EPBjmWYKS2UGd0cTly%2Fnewca1NbByHfEjcbXMYkb8%2BcORFDg5RQcBMTQY40DkRi78cwb3X8YfATKHWIBcYJOLVL2AgLvqSCwbUZAs3W0ffe%2BkLBae04bq3I8OcC%2Fq%2FFnPQw&X-Amz-Signature=0b09179e6a7793d388947e990c15be058a487f815a9d80eab33a8d3d034ec05b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

