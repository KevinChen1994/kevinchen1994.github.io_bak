---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UJCI2C4Y%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T124340Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDQaCXVzLXdlc3QtMiJIMEYCIQDMudp1J1criFrRwUVIkB5a9bLxzYl7Y%2FBWPgLx1A71TAIhA\
  KPepZfwZ1WWXRibdsAA844f8mSfQUH%2B9PGJ6McK0G%2F4Kv8DCF0QABoMNjM3NDIzMTgzODA1Ig\
  xANe6ur0oEjE%2FAy18q3ANg1%2B3Wzs1U5F2Fz8gatfSk6lYYQrLZ4QzXjOf1WuNxn9EGUAeLrId\
  OUY66pLpCwHyWci%2BmDKgHNkDjbMxtMfEIMvp7kxwKm7JDkcgLlgRkzz1VdxgOXzLiYhvCobVJLe\
  vpIo%2FAhy%2Bq%2BCHaQ3p86HhHChAiq0PigQNtfke9m2aj2VvT8R9GLpXEAXVhSxgtFQcb85uwF\
  YNN2PDKWyDEXtZ27XJG11wVDr0XuWnzpwg6Wwqx0cni2bgxxZ4SWqKqb93abOEFZZC4lNam6uLknJ\
  Z9kU97KOAbuZ1ozOLWkyvhNfadDeSAZSkEEkMGxTIV5Vt%2BmlUur%2FV0zTmDWU0Hi75G60HnXvl\
  81q6TrMK6S94w1%2FEkD3RF0l2c7rPILEum0ae8z7NuaRoEjybMMTS%2FTsuJI48lwE8a%2B7jdFQ\
  vlRIJyOviM9WQ9hlFFzI1AhGDrApW1D9zxzvlJxkMif4NpGVhENU6fahvUyAyPDDTUMWjCA9F3OjG\
  IAaSFeN8D6X66UQXMun4llwRH3jG7u%2FCWN4RvFwUDwIW0cxLA4zrCoPsltfG9oyqN8tCUSrlhUh\
  IJTx%2B1jxmrPiqnFKBwbS3MzYkRGh5MnaOA5%2BEEQzPtkEW3iThSgAWBIu4NJ%2BUq5zCXose9B\
  jqkAaeKKi7rGQeI713a6vJMtwg9UIKD%2F7FDu8WS1eJ2bz2ZCRwTO4%2F%2FV1u8I39SbNlSGe1P\
  zB4zTL12G3M4O5eI0fdURUGcypbYVK9ay2TeCE9ygZ%2Fr5UTEiWS1nmwRo83bIfPmkT6DOMmuz%2\
  Fk1alncyh20lxf3hJElsOlMlpuKmPVCpzWNlBJ5NziKl%2F01Rihr4LMs4PnzrgCsU1KoT3w08%2F\
  pLN77C&X-Amz-Signature=a159584ef5485fb0af76d8510c07b57431885411de6d517d740f8b\
  1c785f10d1&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YAWRQ64R%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T124206Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIDvhUiP00MJA6qWz%2FwVe9YpueGDYJ\
        13%2Fe%2FDah%2BU9QbTlAiBQJD%2BkjqClMjbSb9kmKcoMJVGd2cbUtc3wiAC9DGFdoyr%\
        2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMAS1WMP%2FZ7eLCaKAHKtwDEcgEGghC4EVpjKOEBJl\
        q9IRiP2URTCfIh2AhX0r8cvLDiZ4bH2uWKU1PdsAMYQjHsl%2FoQmDfE6cJzPc6p1q9g%2B\
        GMhfWKz%2FrvamZQCyQ6VhUEe%2BrEB%2B0QNbMozbwfl5M1kB478ec1hEUX0%2BN9L40Tj\
        DuN6kr6HICsLBYaEJ%2FJrA5X11A0Izcg7%2BAlEmcGWGu23vfzAfCBbYOEyPZjcD6yLuyT\
        fDNAmH7iawt60Q3Da%2FjsIJoB1%2FdwqE9Pk8znClE2RsgQIKnGkDVBi2vA%2BEAaC00Q%\
        2FcTo71O2bpYQoNmzvjSGhsjei%2F7AZ0aiUsq6gPIYnsobEJtlEY39jppOzANBph%2Fwc7\
        OxahUOGz%2FK5DcWLDwwO%2Bm3ivuavAOyohz2ggArBlK0rQYYmovYwO9YuGWwVNnYJzTAI\
        kf7p67VVr5tzQwAEDszeECE5HK%2FDXLsuhiMOhUMoHt0fslphivsdx8IhVsDh3xH6008gs\
        u3cx%2BLUg0gPa%2F76zPqBhO%2B7%2BfDVdq6fq4dPHrQwlKB%2FM5DFZAONSPkgwVBKPC\
        ttpQEmgA0YPrtRO19WC3T1sDjHAsyqrAAZ66keAA7HoHEPGALmmB8YMoSTJdCeE66OI0OxS\
        BrR2AC52gmPz0nkvYrdngw2aLHvQY6pgEx9cMUbAP2AWl4trxziwwyqroeuM3c%2FbZQIc8\
        9N1pbMHJBu86XeJzZXLx6u5aQHTS0JmEW5iJnGFolPWSPl72ExXtrR%2FDkRo4VDrXiraFO\
        pGZQap5S%2FflmaybjyDMQBoisa6Jv6uftap4Mmo1W7RyJCto58KspBeSprxTCjecb2k4mE\
        8Ta6sxpPZBx5ghXHYbmOX5MG4FsRrr1Hx4Z9AldsSzS0kIq&X-Amz-Signature=ca9a3f1\
        250a5d54ca7a8be4f8fa82296d8e5a3bc92aa229ee62d9ad6a076fc07&X-Amz-SignedH\
        eaders=host&x-id=GetObject"
      expiry_time: "2025-02-16T13:42:05.689Z"
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
UPDATE_TIME: "2025-02-16T12:43:45.635Z"
EXPIRY_TIME: "2025-02-16T13:43:38.039Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=d8aebee6d4201355fedad1ddfbdf6bfb49113ad96c712c862539c87a9f4d4248&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=7f0530cb0f7f8f8d3fcef106f2e05622ef89217cf5fa07e01f004c9ef6b70a09&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=2b4da965872f24427c91f008596476d9c586cc61629e6364d545eea4b596f013&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=f54cc601c8014f6ff90aef594a901bc202bc98f2793f3f12a26850e176a7975f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=363d7ac5f0f362827c80b6c53b49da2ed8a986bd3451290bc3333f00b8c427c4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466374HYTZT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124339Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIE%2BGdOuOAobZpjDQRo2fyVsycSOiMR1kxvwnI5bwNyl1AiA4Hz9hRjKcmW3c5aeGx39zKoyU4ydSsggVx8ZK80u6Iir%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMeLPLrooI4jfRtTiWKtwD8X%2FS%2FtA9%2F%2BxrR%2BFtaTUcFa1uS86lTBrCnCD2cfe%2FhRSkSR0h6QnmdDDzdhaQV4mzkodFoAym63mjJVcWpq92k04e8QZdvVeYknklv%2BxMWdaX3gtjpcMCbdPRscF6olzNNpulF8ax96z5eQNN4vDed4GWuEw9dOzNB3CNiNjXDvZ%2BKwpqrmFHSNskOZIvaIViLOepS2Wh4ey9SWEsMNehU4ViGCecjjTuR3953kQFvEzEmm74nACVlOnw24NeRUDzO2WfpouCzMN%2BUYcO7e4L%2FuhXesQG%2FgWwJTR4QcS7xna068u3Kp54OcrlN2TFq8mkh7ePoOPJS2ypoxyplWpuw5l77GqTeOQyzY2fah9ZgtEUZXiRKPC1%2FntfZkHWAUhorDSzyqRlgojunUG0UgXPrAhKlL48kQrLp2dDFXn9UtcbX%2FKkG4ImBfLa%2FXM%2Be70IUzg%2BsXJaq5jyf8Z882qvS8ELEGBS8USlvrfL%2FjBzBSJVYpS%2F2buVsFPxG9rQik1HVMJFiXkJubjb2%2FVTPmP4sGGqc6G4TaRbBvfLl35ut8DoMWhjpXtWOCiqXKggU3Xf5hrkGK3AWMnKvsA8ONXQa9HxiR%2FrFiHvmU6l9uDS5X%2B4eDSjZAwbRrxpZT8wuaTHvQY6pgEt546P8I8BAYzSTq6Jn1Lc7xSAZVgn74EaP3e39u%2ByQJxtL6nCVvao3SUULRp%2FZzc478iHxf31j0KpSlHaESJNwAwgdYRrKZZYweADqj23kSaCQfN6QzvI9HtawlcV4dZZSb58Nr5NGBIQaKwmiTUNx8NCz%2BAIiwBdFs%2BmPNpFHbT2IWp3L1qDXTzOu%2BhM2f%2FnAuc7JBN7JXIuGSfQrbIKMyZ5COXD&X-Amz-Signature=ea066db9b75121de570dee10dded362f5ae4344dc8191ed5bd35bdb3b3b67303&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VBP4CMG%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124339Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCic8CYgRoH5m6gVfbHLeXHjt1MWknnAlUWzahfSkjRNQIhAOtUG5am4RqtXKYUh3Be8t7w%2FNFBK4e9CEWbA6PfwdC4Kv8DCF0QABoMNjM3NDIzMTgzODA1IgxZzhSWvBbwN7QrwHAq3AOiMuJCMT9hoAv%2FvnakEmDqtuZHf50f%2FUVoGtxRHhcfBGG7LryTWl5fPz5%2FhKyA%2Fc0xo%2FUA%2BZ7IKlVB6Gqyxqo6J06SYuP6Wanfl0xc8VFXUsodtW2iUbaDzDKCdwCMbRWf88dMG3Y8oNOzr%2BpfetbQoDvbrtI422tWy%2FyFi1NK4ZlUeC8geVjueBLgl0crjus0Ij95JIy%2FKzzcSKJhhuxk2g%2FttaGpP0EOEOa8H%2B5on2PYiKCqFOkySV%2BAIzG23kNGMPl%2BXi7Kr6zJgLrNQo9Ho2OyX9sApNbdsEjOwtsq2%2B0o8zIRO95HXls7t79F%2B5qhd2810pDNB3V5rABRd3q0eJz%2B3I4bo%2BTI6WVziFYnvJPRXvs1UuqPN2DeSnyWOPoHL4vZKP9VQEz34S6CeHA2KhDloS7GhTVRVEMmFGbAP4qAlGFANDiZYdnAUjnPSqV%2FbVNZK%2BpVd6u3op00MT%2FXTvGQjb1x0sifpVI%2BSS1Pd2X8sgVZs4vzmU%2BNxIaibfejHiunr%2FWrtOBwkkOXEZkyAZY8zr9WCWc4SqOrBhwAT16I0eQYfiSsVuVRznQTrjXMBNT8QBJR%2BAwb%2FrDqayPibyHllsCf%2BIcjFMMPzD4Rrl%2B7sgZR1gAFxec9wDCCnMe9BjqkARpFCLF%2Ftqcyhoonu2EdLPjlh%2F%2FjiCEwWtqo9o3ePSvyY3lkdB0QZ%2BZUSLnnVyUJEN5JPvqJSoSuRfCpv457eiPEmveYuJULT3saA83ysYa%2Blr0eCfEeMRarAj3X29fMQ%2BwmhDsEihtdExH6qHK7fgWj1qLVn9rcSK96cRYyfQH7ZXuW%2FeTDBTAG%2BEBqONA7aFiBJSiZFmO2rX71TqtLHv8LpvKH&X-Amz-Signature=13558e3709099ae11af390320bb682886e3ab3b27004e2b7320b50e4284b29ee&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=21d02426e7cb34d174d50c5bf407d5fbd81516def765b3a6b205ffc7d3b5f210&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=aa91f40fde4443c7c1f2cc62ad3e8ca22ff6b2d7f2735381c623a1384118e6e8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WII32IVR%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T124338Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJGMEQCIBIZgKOB8%2BHa1ldbTbESWydFjHGYgwNeC0uR7fA1eEBwAiAuBFy6soGmLEvB18B6qh8cncU0G%2Fdx28%2FNLSAzlKCpDyr%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIML9NVJFHqrLhdLpmcKtwDzCuhxUSYPDbSEKYX0Jo9LxMbRWpraXfPsB%2Fxki4aQ8Q8LaWg9efKyfwIgMaBsdCa1difLkTup9UIVUFhKGc7%2FgyQ2zFgmw7c4%2Bk2drSR%2FZDAQdWBr9LQ4DgMKp%2BCVEAjVhoIf5CxUSSSZNZA%2FVkI7mbNi%2B3JJCMjnePlDx4LKs9h6XO%2BZLaXOY4RVrvgYpWOpZUm1OngD9cb4Sn5Pg3RSfG%2B0x6jTUxmeS%2BBna6GRuf46itf2oiPJNlxB5Esmqyan5WUCXPjynBVPUDJYfuGcOLMpWHmU4JnrZbt%2BHEiJ03cUBhitvUlYTeS9%2FruWGMGoxtb5f0SmQLaEWFdeF%2FUyCSOJ8Hp3%2BBoKMrC0PLsFtuIy7SOfZ%2BSGgb5bGxS%2BfLi2n4YkIMpgMHAvUvUEVBsB40oHSf4Yifq7AG0xVL4hcsSmUWmzLghUvHecydzDwGurXCA4EQlmv7ZG%2B7bZETio0YbPxIQUhfSvUA5ACUScUVZF4TbTK3NeK24gRLi2iJtPJcpkSQtWgh8xXysxDWRH3FdRy4D5BZ69aPTIBvtP2m6jhuDunm%2Bs9PJ7arHgH4QGuyOLNwXBZnsnC%2B5w%2Fti0NVOpfXbXUXrGbMVnWlfmxS%2B48cQBZmONnLXCfYwlqLHvQY6pgG%2BMOUyoLh1hh0AzVJJAiE9wULZwAJekuFwZHs1nJr2nE99AWA1YIWsLBFxfEhfI%2BPy7JguYaKogt1C5Lg0P%2FgEDuyxhN8ItQu76oYnr7rSU0g66ovcVoBTPtv9u1tH7WwjouT1NMuFH8VnZwqjaPFQenUjOTi1hdeSUHknE2XNPYAngOLB%2B6rlqylXPCub9oTNmDF352Hp7FmOsxR5QCsN0JYkeF7R&X-Amz-Signature=1e5cc0438e67868bd58361fc6d5a32e8f42c54b67a94906e3aa0df9c7d2533b1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

