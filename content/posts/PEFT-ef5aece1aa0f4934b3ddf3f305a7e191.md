---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666REV4P7G%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T042759Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCaT7rYokSXq9zjrxT\
  %2F1xdUf8R4vGq3SSWm7tyX4XesSAIgDKKeYtHOQCGeVRa3gaap2DBkPpUMsBHRh3IVM8TE2gYqiA\
  QI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDAD9AfrYnLKAZQs\
  H8CrcA1%2Fv%2FB7LE1xN%2BnZBX%2BUC8Hut2EuW9dNt%2FlqpEGFd2sT6%2Fwpih7mHDMqT7DjM\
  vOkthlPT5epMqfY894%2FXClP9Si6pQM9g4eAgfzVu%2FChEz%2FBn9ebZ3jIDlAV86urncjtdvP9\
  7uKZzfk2dww3%2FXOdiFY3WJEKJqArtsuJsISp%2FHr80ECiexmdW91U7b7rNCiDcflvqtgwRjs%2\
  B8nWFbZDanni8IgCX6ExCyMP0%2Bp%2F7iYRw2bpIBh5wfOARarmoXTTpQ6ZzAxcqgtxu%2Bv8HKz\
  sirPoUG%2B7ajHGG3jvTyye%2BCZBF2fkQn4SQr1nJeO0Dh3v09SEfAJ35j9ygF6E%2Br%2BASTxg\
  lwIyDBJVyJC1oeof7VeEBEYwNRTW%2BkcXbilhlGT%2Fpq7EBZ4rxuxcU%2BtcF%2FXXu%2Fcvn4a\
  BnFHZR2%2BmSPR7EBh%2FO%2BK%2F7HzLY8uPLSuBXERsfeN%2FIpTUvirHErHKcqaMA2T3sgeog%\
  2Fb88g3aIGzHs2HKEWyqp8F9Ko0d%2FXpN5UFPjYacW1fLVPr6Iq6RdKnEA5zR2G3kOPTdbOP2Deu\
  ul46A3Zf7BlzzjRmNnetyRoYPoEMsyfNBEBI6HaWvXCvqtXviMf52C7W7JxwDaz3eMX7G1vdYY32Q\
  Jq%2FnjRCRJsMJeQ6r0GOqUBtlGeDVrltmcTviL19d92Pp5o7%2FUJnCEDxco4nIzOHEAbtSUrw5J\
  WVeKFdY20B8lpR5aBm6P0B9RLBtXwtZfOQnz30bfrEwM1CeX9LwMlhu7EgzPnIv4GC4PZ1BjMSdGp\
  vOCZN5PzI%2FWlj%2B%2B%2BrKBOSS5YqRbEI0lHOfQ9B46P%2FjiRg0AO22CVPXnP5nk58lgLItt\
  F%2F6nho3bVt1FDZ59tBs9iJED2&X-Amz-Signature=d2dfb4680f8016b229e7dabed2ae16444\
  c91c37842328779b871faf4654ca973&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663BC53CIR%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T042644Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIM\
        EYCIQCCThlErhxfBoyPWEUrdi9PDK8iM6MZPs1rocpg2koPjQIhANq7zjTbodUawzHgNNtH\
        TbtfFd%2FoWF8pCdjgwvv7bu8TKogECPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMN\
        jM3NDIzMTgzODA1Igx25Qjj2bx9mti%2Bub0q3AOdkO9qbg9lraMjwVlfzloYJ8CSVEIYB3\
        l2pdYy8ps3AuKgSRtYIL3LQEnFakrrZc0ZxMU%2BHME58RS1vtU72vyY7asz%2Fv%2FUh8S\
        lvYXzg2mmUDRZtSKZLiWgCEnWqi8mse7s92yUEUMk9e2ztCK7t1TsxZdT2PO2hG2y5psfql\
        ngmu6ewz%2Fz8kOCAZU%2BvW8nADNM%2Ficd6bwInLHclk0smFcGWQkATUpfNPOx%2BHgpl\
        B1SIeBSe40qBF8ClTqIemkQ2xk2I3%2BQVLDcM7Bdd8M1QEDXG0GU%2B7NeAhTaj4LmnW9f\
        1Yp375PROjEwdmKfyFROTy1CkIeVGD%2F%2BPfJG76PxIqHdXsyFGnFSONZh3wuBtEMbxE2\
        xKqYEdAeDIKYjBYkwltW08CmTjBUn9KGAc1COR9WZuhGu2Rk%2FQnqm2wkfpvO7VKKovRqo\
        pE9yQrMFLNoQoO2kTI3UPrtJ5xpZdbKcCnRR75vkUIVhuOsZKaTD001VHE%2FSYO5M7n51a\
        cTSxuhzTKQ%2F4wVZQCh3aZGaPUIhs1JI61XYhN1scrVBpEDedFvqr%2B0ECrnCaz1ylhyK\
        UfeZaeSk2ZEqso3P8YokwCYq2TcBmQMM6yOp%2BceJTRMJYKw41UiwZuFj3gm3mL0zdjDjq\
        em9BjqkAdzzCmUuIxodtl95sU8deMZNy4UFjsL5zTuz23N89ENn8CBpxN7rKPz4d4dpBm1d\
        Sj9buxbHngc2mCJzNz0t4Sr0Fu60fE7IwsG8xLlJHuj88%2B4hCPRULWQseKapVbyhPwXkw\
        UQiU%2BgBt%2F2b00BsHFuhKrn4LSs%2Fvd8ZT1AXDN%2F3nOxFxjb73nPG9Ad0RHSxYliG\
        0jgZS2%2B3mIA6CayKjhjmZ0kG&X-Amz-Signature=54e5f0578ab0d578e0e2618fcd1b\
        9db3333857cf72c6462378c211e4168250a0&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-23T05:26:43.897Z"
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
UPDATE_TIME: "2025-02-23T04:28:08.239Z"
EXPIRY_TIME: "2025-02-23T05:27:57.476Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=6230deeabeddcce371fd6599262cf3bafa3ef5e93625607d83e0ce2bcba9127d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=62a5287d5e549d97869b0036ecfd3b0add897a846a66d36d70dd3e2ab23d70d6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=4ff66486293e8dac1a19227889b3ab0b80c461efc023a2c27399a74b8adba492&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=90a478570e293c58d1f1c9f3aaeeee24dc718c8e390011acf7fed8e99edad4a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=d2d64c61a372e7e8e82b175b4b1ad5091895a59321c466ade8a06a7c306751ca&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JMO3B7K%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDdLuCRoEUy4btJD2dgFPgImyBhEEx7gvrQpiBGVzk2AAIgXpRkOHHRUeigY%2FPBwRmj%2F2RKBSZbDoctDffnNtDeW%2FwqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCnxM1a2gcr9uAE9fyrcA5JNrancaXclZxbGJZ1k3s%2B20nWuLTIuNktdVng1R8RDDUHdHwKEWS4cgQsA8ii9CFpLNDe%2FXXM2YP5%2BLATYB2SL%2FW7zPNwgJG%2FcR2BJ5FTVo4oNsYQ6KjXgb8936IDe96JxejCzuZ9DWzAScEr%2FFlovfFQT646sJekHIRIPrCSIy7ruQsyku2K1X8QaFvHsjuhDo%2B7%2FHWv%2FUNKh9HAfCF4wVkxElWIdazgHPS43xreCxdE1tGYLbTpA1udFY5an%2F5EbscEnrMmy%2FREJM3Ve56lTggs733%2BI9AzwiGOBbzR8%2BA%2Fhh9iDbd2GPVdfJH02Ifd62eZIZJqkm%2Fyth%2B%2FuGp4W2a43fOlgPmLo6erauzEMn1iFy7rtWeowawfIu0kxDTtEwgnjtuOvc5AgmXWu8NiaLejqp5MZV1ujjsJpcVVEYVmBtt8JVubM4qcD4wT3yULRyy0CZzWKuWIhQAAzGc0ILHMDDsexiGbYNRC3AZkvFQOk7j8mfcOn9XzcIYv5OJKWJVMLkQfGNOg00bzdxYkK%2F1ZjP66v0rHhPYBb6Rzyt6oRapD89v0SqZ3wEcaPs3cAeC9A2Nt82FmYEtTLWYVkEGiG%2BSWsm%2F%2BhQF8rVn7q1syfoHMo%2FbvC%2FbJiMKyv6b0GOqUBuCNJ5C1y%2FZiOmHpnpwGHEvuJu0A%2FNPY3RYaZ%2BKop5plTPklZY3Po4HZN6PjfdxeMLXR4ZMV93H4zLgJNyIAsS6zxEITLLHblCTNS0g1A8d0khJVo%2FRNSmaEdQYveYWQFn71G0rMjzjvTR9O5QuHl9TOc1Yz%2Fivqhjz9%2FiHfAd1%2Fls3DO33Xb6XC3qk3XPqJfNvEZ%2Fznxy9%2Bjk%2Fl2VzWFjmryJD9C&X-Amz-Signature=8f567a206f04994ff6a96698c89a9cab050c9d9aaf3755c50c16f36416356761&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZF3MAKEC%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCBQFP%2FCo91qiqUfji2of4XG96uEPl5XxkwAje8HxJ7NQIhALh%2FkIMYptNATLT0KxSlgZB5DXDKMZzpUwI9C3l3Mq0%2FKogECPz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgymQit3xdWqCEi0YsYq3AMS3%2FtcayiR985YdKpbrx1jzCqOneJwxuK55DhOmP3oWsQl6kYgYeqs2De7W7d%2FQ79pI5q6XQhFG5Aqt654PVV9RmNFOscrMVge7tuXKL24rbECJXFpnKYy2xvGYoY1p3UdxSUt1kob3iwMXuX0N7%2F4cVkBES1bU05NfWZowxDeT%2Br2xsWuZkEGPFOGFzjaH9bbR%2FdlxKWaMWSeuHxm4W8mHqrN8y23cFqkfbxIDHIMMhdHcvyL1Pp9FFg1ucPlBC8prsIHcLcFdPOojNWbb11uyP1smZEwVMOI62f6euDDMnTJsZjSVo9DZ9WIZ%2F1rQLnNGWySb2%2FWf9S3gShsbpa2JU1eN1b1kGg%2FCQrxmmENI2RyuF8kPF3tQBfajPfb2rHiXDFZumzS%2BlRRlKPx%2FVGLKu9KwB%2Boj6nB7JFSJU1jpVTmhsWyLOTEOZZYBZE2pY8I8PH4iDtPbCCJrcNwQ5tnqF2jLm02OKWyK1NoRuBlZXc4S9ZnSWv1%2BouVkjLqZrvXccRsRYOyIPNuvfLr7Kx3XaTrsILArve4oBUWS6aTcOdQukiykOd82RlCUt3b9PfxfwiF%2FGgc6bwPvaOKBl2OI%2FDUb3UF9m3Ra4rNgdvyZrRv9xFhgq2II8dQjzCxkOq9BjqkAfGKnJHXtC9dmwMZOQCJpoTNEFxMfYWfiat%2FhOMHWAf5jiYxqgpuEt9qtb6YyvwvB2dVE2zNNxrF9nlECqX1rOWM8Fln5zXHOdh7IFrw7uT60LpMqU4rMb7EwXe6aqajE7kK2Y1qOv%2B94ysbFfdIJbXKDsYWiwoa7EFAoEM%2Fy9IiTm9NPWCJpFOnqgObeoE%2B8rk9bNbYrKEbLdyyNQZMklHBpUAN&X-Amz-Signature=836ada69caa69df694e4da0712e42eda8cb7de0880cb7b929b835fa3918ec434&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=8129f1e01a2f27637cf429b072ec7674a185385eb01a85d8c56e091cd9318f5d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=6eb627b7dd609fe3cb42b325a3bbc4d8689818e1c4b3e93709ec068d5d71b8dc&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667UFP7KPW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T042758Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEM%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDerOUdFb5boled1IQ6MjC%2B1VMBbAALmQc3N1T%2FocxTJAIgY9cLrHdIuqTJ9WB%2Bkdv34kAAQPNIgTTW93NbTvbbG8oqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHn592SEnTaSwlrTRircA8XXxgzRPnhhWDmjiHy7rkolwcNtfUXwfOnkXzmj9yO8LxWbd%2F7nSTsnC%2BKkAgdpZbeMbSmNvPfBGUNNvAyVM1ou%2Fjq4wFG%2FAWUQ79PtnFboMUGw9gfSm3KDORPXAtr8nQqKNdAQFLvBfGEuxR5Hj%2FEtxq5kJH9TntLy0AI8MV2PYlldyuinDRNgHOrVz5OZNj%2BDvg1Q98sKDJ43Vw%2FIzGJ02DbsudMa76N70DdFVvsjGfwKlh4X0OVASeHrPDPX3d9wSMQOrCzbysB8jPUbY2f0pjVfGM1%2FVMmeXZJraQJU9PgbxWYQ%2B%2FvJF2o9GmnZKKVS4v4fZQir3FPBPxM4uSll2tNpC4t1CzCQ7gJI5pTjVwbKWRdTLsI2BlP%2F7D4UNO8g%2F5TjgqDWnPdYVkd7C1vOy45MUkh3NgWWVLiy4i3MBNfycIQ18PvnjpoYnqyLsJTiFSQUJb4hN6wizXPxu%2FbEKXGUHgVToh1vlyVVvbztpQ8k9%2Fo4bBNCJ8WAgcfXuWzdj39wP2kmOPXu2MIx%2F0VqNHAXAxTE1pM84QiNWRVty%2F87HeCnkruDCCyRzcgvAAnQINJCHGlqVLFZSt9dYdi%2F%2B%2FRDxYgwD9aRUHwVwj8rFDeY8lo6zfirgWnrMKmm6b0GOqUBs0Jzx9suroQ1Gzf6CtPd3ZYUQeSIvgUqUCIZ%2B%2B1mEGa1v6A2Otu%2FCcpc%2Bro7m6BtQEiMDvUp3NvQirB%2BGtO5%2BfJKanIi9y32gGNAk%2BAWU%2BTlCvegwLwMOLHPCj6OmWKrpuokSj5bkmglpNcXyb6QuKje0Go4Q2fd3Ry4kxQq9w06SXTT2BdWPA%2FIFsqO2oeeI5M2kqK8j3xuOBGtduXqdLaXFajK&X-Amz-Signature=656efecebad3526c721e7f48b4ef9c359157db6dd2633288a12c0cc494d54c42&X-Amz-SignedHeaders=host&x-id=GetObject)


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

