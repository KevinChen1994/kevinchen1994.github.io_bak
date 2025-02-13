---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4663IKBNEXE%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T072227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDIaqEaZHHkC61mVK3\
  p%2FA6toBzlDTgxXobCur5S5aptfgIgcNJ2hrL65ihdlF%2F3AIztMqjwwqLeFgo0MNmD3USJazwq\
  %2FwMIEBAAGgw2Mzc0MjMxODM4MDUiDDySunUxAuGOvBU37CrcA%2FrB8PI%2BWK8TAWK384hDv2b\
  dYnOgzQhhrV7vovEDD%2FqnxyfEdhnTZOuCuWKY55c2o1jTuZ1Xi0jw%2B7kzFOLzcakS9z9eFlR9\
  OcEOP2pKjb%2BmdotSkx14%2FgYuAnA78u3MHVRJZXqul7BEWrPT6kEcT74mvRrufyuk7tpmi9sGf\
  %2Fh%2F0timytejAM838O0wylzPBgCG%2FICx4kBknLEK449q%2Fcs6%2F4yp%2Bu%2B2K2mkYx95\
  CCSFIWSVECUEUPc%2FVV%2FKpGHyq%2F8ob3ciciOshvrcgT6ZhThfJpN6K0zx4iCj09wIenR9%2B\
  nsJRFp6%2F4fhocgpaRHaWtBTTZdrhjmIYsROucjK3EpFhwsXRkVP3ze2COV8gDLmpBij751lU%2F\
  Ffry56Kd%2F%2BTnHRNil%2F1ltws5cJ1YZjXXTQvrsp1ro%2BilP509rBX1gOaf6RmzYv3STJish\
  PSF10j0TCEh82NX5PZjIPC9gxXSiy%2B49X7l%2FNh9EM%2BTGGaBDqzdJS1k7b109z3PhN81F%2F\
  KZSe36%2FUtFYWgjbBWqrJMEOt2LXq9VwymfABVsOn819QPdubIIPqxYmRaw9SkxfJaaJcNLv7vEz\
  NI%2FbeyNswVC2yyhol4HfESYpNQ4TvSrYQeuQiMUbzLvlbRTfzMOmptr0GOqUBTOcW3zf3woWfgr\
  mi2mRosZFvVV259a5f9xZ%2Fuy%2F%2F%2BgQxboHtouhTY1Kf8q8Kau3WViJbRm477OVfF89dV3o\
  VFCBu1DQQ49lsyPD8ceSJqI1Xif%2BLC4zm6exxwuHs1Gac3GUSKjsEyPZKVwa03HRI4%2FpjwoJD\
  Lkd86HVRPAzUnME0fUT6QtsiFV%2FLDA1FrPUxmZDDBGCFwmYfCPyAAZX3wt%2FvO6W%2F&X-Amz-\
  Signature=9d110e8e043ccd9733511362bd060488aeaec18edc735c83af8ac532fd15adfe&X-\
  Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466U4TEQY6Y%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T072054Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCnxZ1jTJNZfffg5mvvqvV6%2FGfmeI%2FtLQm2S%2F%2F5%2FvS38AIgEEoNOz9QoUwQ\
        Xk31DIkgWxH9n9UBQ3ozZKYZCXftbJQq%2FwMIEBAAGgw2Mzc0MjMxODM4MDUiDBb6Qw6eG\
        CyeW4ZagSrcAzlO%2FhB383r8o70kS75r0hmfaCiodQ0TuitNoA0WaSyWASecFyjJpM%2F6\
        mdQ3WebW%2BSIi6B59y4hkcBoGjbIhor2IUnwz%2BbD5xeNtwCfEoZ085q89x910Vrw1EJ7\
        %2FRDJlDxV6HZkg4ReBPDpeRm1KriGxOdG4ZfWh6HjUqCqv09IyP5rDwfEQscsIHxukw3FW\
        x%2FcFdd0cOYyURuR9xbIkTml3MVgBima7rsX2BjC65qxK5q7bo94v0Um8oEJ5l%2BXTD%2\
        FBhuGDwua3FGbaf7mbUXOeVPUJ15UlC6fMR3UQD%2FFpyNrurtjjh3ue1eFTUGLF3MbWoRo\
        LEyCROZ2eYNfDysAlCK0sCe0gteWTGsS1WtM8SJckYFHmJU1C33T6aybInNZ%2Bni71OIUh\
        TDayp9RMUKiRYJawl4QRbeNRyc17w%2BnPrYYYQDccjXNjaQwUz4orxxnqBwi3ABbcy%2Bb\
        29wpOzzgv%2FPFDWafdv69blcEraMY81SnGCXtkXcBRYX0KEWquTZKglo8GWzAKhaHG8AEV\
        broQNlbt1PHpsDliEbe3Iufi9TT9yIKv1HyIjj%2BY12XOoIIyWr0k4GYCvhGZHvFyxibw6\
        %2BGEMWoW%2BxWTc%2FTjelltLuMjMO%2BDWqKmdGzSVMLqptr0GOqUBZEkK7dJY0LP5i7%\
        2FJ4sucVvrlL47mx4y9C%2B%2F6clNfBu2u2iNRkyKTJMVYr9eBn6%2By3x3i5V70KjVmlk\
        hL3rZFUxCKgrIjhKHb9oG7QEJ8YrEZcORdO3eNGW%2BGRuOLu0xms1VLQRIRhzPmf25Fg%2\
        F3GGGaebMYzXLk%2BJya8HkP4Oyqvn3%2F4bsiJGozTGj9XTegEt7yAtSKaYsu4ZZnm%2Bu\
        4xylGdbMEO&X-Amz-Signature=5c9f12bb32c4e6636badb5436be6d791cd017f182c50\
        c43dc1ae20d0d619e293&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T08:20:53.998Z"
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
UPDATE_TIME: "2025-02-13T07:22:32.786Z"
EXPIRY_TIME: "2025-02-13T08:22:21.313Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=4cf9b556cd11c01ffe90fbb7041c08e1dc137761cca1293e7b86b83701824fb9&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=db5547c8533830a65125702632982834e6ea2ae2ca246a28499a8effb1239a49&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=0b0ea7fab135f061af1015d02a625dd7240d9e24bfe7961639ec63ada2f5fd40&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=6a65f6c17795ccbbf1c11e7e2416e44af6800cfb35bb4b9252ed3f7ea4a65619&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=e68f7c27a64c9bf51462b81e8640e27fd7632708c25b619e2801c681e88b902f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZPONLRCQ%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072222Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFFIuVBD3C3UCkdMUzZjZa1KgE2DCqJSE4kAEyV1QdNIAiB2XltdpLh%2BfVdz9RyecfBSobxYBsO4Gu%2BuCgs6Ycq0lSr%2FAwgQEAAaDDYzNzQyMzE4MzgwNSIMw6cEtZupqEksI3xWKtwDa7LQmXAD%2FXpE9zCHjeBS9Og58K3oPWCBR%2BlL4VgNXswuEz7xZpfvadBUQxJRAA7Zwg0qn6uwjlqUa3xFe93GbzdpoN7GzXNsZk0pLtoW2bdj2ltpfEjie0ocf6OfVn1%2BFHkz43ZZMJc3Z3HULePbsjo4T6YX3yWWCk7T%2FRM%2BZM34O1OHZ97JCq9xvm96njgJy9K%2F%2BdX%2Bj7a0SCkfkgaYTpBzL5NoU6usHVazr%2FGMAyuL5ApC2UY5pcEZEsJngJdYjhqYtlUDZc78tQVyNysLGwzr694VSuDtM6Gq%2BHkebRZp7Vz3rdxbSro7tnk%2BFBAId%2Fn4kqQQAFQmUt5QlbqkO66iO207W0RB2QXOz%2Fjb7cIie%2B8fZh9FBhAHXZ8xXzsV%2BFMHhPPZRC0fn%2BihpyzoXgtH2Y6FkyseaqWikWqnT2rgAECv4nYgVdtkXYFXCMpDNJUs2TEinKIvAJJ1OcZgZkzashN2Ls8r%2Bhi%2FtGsAPRw2IxLC3okCNDwjBrTp7brD0hCOUX5TEMz1v6ZGkZvgo0DfSI68vxfp1Rnj0zxB5WBz87N%2BWjHj1hXXRr4Wfi2KiAOWU5MHqE7q%2FUw1%2Ft80AHTxhuOb4km1DUJ%2F%2BxyJlCq8%2FhiS8kNnGeebghUwpam2vQY6pgFxt1fEoXziZTB1gnuS2yO6r8Ry%2FQpemJ%2F2iF42lAF0C65rHa1f1Bvfw%2FvYqKt8otBFldv2E521fuanyfRsAmcZeoJgcN3e0rRwnVV2FBK%2F%2F3o3p%2BnZss8FaELSyLT%2Bpp%2BN8z2uDlGojvsTp2o1jZQgaAv2ho7dshrkJjlM9p%2F%2BUSU8px51HLeAZWEK%2BOXEzc54v9%2B%2Bhl3SKkb7AxYi1c4pzfojH9Nf&X-Amz-Signature=12de51049b2b08351560f7b458a02c26126382cd9cd74ffa144610b95cddec37&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466W7PMQOWW%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072227Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCL8A1m55z%2Btdi3hD8THh13mM6Kk%2F37O67GjREwDM%2FTfAIgYxLlwATyX4SdyTVxRw48GLIdZzVP6BiBU7wH2ulveDEq%2FwMIEBAAGgw2Mzc0MjMxODM4MDUiDDzYxLP2N4j5VUAF2yrcAxzpVRZIoDn27VLWyArHS12wqXZX15g1tu5Q7K%2B7iq3jZ42ivhnaOnlG%2FRaP90T8ama40SGjMog4zIsuCaW4BuG5GeiqKnNbXh1q5xRA75Uft91w%2B63mc7PQHrJHldnXm5b7rQlRgA7wWwyVoq4SMshoUUFZcVt3Ax02SXMHQnqE9KnOSQMKO%2FbX%2FQm9VAzSzGFIOsGf2N8pk%2FxvK3%2BZTk5KO4O9%2FMtFv%2Fe0PWU72BWPUepKneInDgfrfsG0KG%2FKuxx2DB69tGftp7K9cVQ2gqmhcBJxdeVs%2B5r0PE727BO%2FyQ3jzv9f7Mu4fdHeMHwmye6g38cJBPvTGZZlJR3vSkdqIg1Vf%2Fuh0Ut0nM9KBc08mHUOE4M5BW7d%2FyPSRISOc3%2BiRRaem%2FvDgSeeWtZOaV0sq%2BfNItNxgil1pqX%2FQlEMxv0K%2BQrQZEavkpeWZaJOTBSZiRZS9zezc8Ndx8R8Ha4O2QlvPoLz9WIq3tZavjeu4tJAo0WHAhQM6yWL23bMd%2BVR85C%2BO7KdGgssxU7D0FyLM9b4S5GGmDvb3ZKvIlzq%2BYgL8yesRmOKK9%2Fhe39jSWPKbgVdBY%2FJ8uEdt2bG8q7dXz%2FePBTGJYgnaAWYlHAWpQM1RlfVfQsmKqzlMNSptr0GOqUBf1b266Cd%2BWEgg0UHQD48ZiclcL0MpDTX6PLBGf5N3PSCMZY187WW5gtBARFZxdJQ3u2PrECUKP9eJQAXd%2F%2BzWLaMnku5F%2Ba3seC9wBKdbhzkQGcUzqaMid0ooIttmJw3JosCOtAYJ4r1%2Feqf5Om2%2BEY2pVz%2FlqZmjRovRdVLQ93Dmfuw%2FyRluWyn1eMrcuSkBfoncuUHRFedJP8vdzp0n4bXURH%2B&X-Amz-Signature=11e95b69a3996c58506022b8819622023517062db6d982d2f0986533f00824a8&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=9879a51a13d8ad4b0e8628c0cb5a94ddea6314f9c42291f06d5ca0e7bda39e0f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=bdf20623482d740cd8596cf789e6cb4755092fca0a624aa121cc4ef5d18590cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667HWVFZ2N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T072221Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD61AapPOyLVuhKRgvEbKRwKU%2B2Q9xhe%2BgwavMOeNbubgIhAJ167eHbkokltv%2F6Wqb8VfVnaXKC1jm7NkgWnXPZyPMBKv8DCBAQABoMNjM3NDIzMTgzODA1Igwd82gvGjUD44XYeL8q3ANcn2vbPxRYoXy9gzOLa%2BHO5MGak%2BpaNhN7pKKxPLtn41Zdu0E9fA9Vf9iYvkWiHKEOPQJTuD8iZCO0KU1tL0Xjh6nzFrs1E8bFBeeGO%2B3Re64pnZ2ToghtfCITkkJQ9YBT04v%2FsOmhYy19rGOX9GuTeNMHDVkKQQQubHA7m6HIESh7%2BnE9J5ro0IC%2BZxQx9TiNYszkRFkfHRT6P%2BhLArvk6Lsjyab4jLLjTAK%2F5atZw4%2FOCmzQFuEbdnqCDUQ4hfOFhPqjyL%2BjfXZf50fYJyFRYtUqEq0F03pP95YUfohQDj0aBLImnCrrUFzvKjJ2ofOoRjcUP1393JCtY9xmma72Cwb2CwfR47pyuFUA89tMFhrMuhvHN%2F%2BChrkuhtBCiNAj2oLR21RXRNahGkVt35EnTicLXNOeSzGKGjIUaFAi69K3Q4%2BPJ856VGi8ZBiiMoRw%2BM%2FYIUrISD08RINllNFSse%2FsL04Tl30AJCNGCEcTGWvaHsP7XdEL3vcmBEfNPnBvupMMZ60iGh2smpVR9Oi3vSyT93ceX68odY5szGwwV2ar7tzzyKURT7kf9flYVLM659QB1jbQDcFnOWsTuWtQKbosgfR%2B9j3RJpj3fyLvtFFN8%2FjXLmoRJRxGETDqqba9BjqkATpxAtnmR3O0mt9xVKtAaZMfc%2Fp3UcgLfcfnntXPq1UtK8YMyIjRasrCukwqB%2FX%2BUjL57Y3DfxJK4ZYJvLB2CHMwWeCvnjn14EPIU3uUTW5VHu6A6h8IK20jDOhKbwoUcynG0xbb8u0tJWTJkpRtI5eUTWdYeAm%2BuB4yIWQXXgt7OMmi18vY%2FbPT96nLtPJmI01Yi5KGCo0igKLUUGnl8cHc8zUS&X-Amz-Signature=8caa39fa5654a1af306ac0d2012e3b465de6481aa148153840e3253b26264605&X-Amz-SignedHeaders=host&x-id=GetObject)


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

