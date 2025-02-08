---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662DTLO3V6%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T014356Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEGkaCXVzLXdlc3QtMiJGMEQCIHtfUgq%2BrxNuPGPIEC5uuaVClvblVMk9thvnlN37OnMyAiABO\
  f05mln05eakM90Gt3Pnd6KLJgFynVUxy8hViEUA8yqIBAiC%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F\
  8BEAAaDDYzNzQyMzE4MzgwNSIMbUh1piDA%2BhuG8kRfKtwD8csYm2RWw%2BlQyDhKbjghQFG0o2x\
  6dV5Z485qhPcimWZHDvjG3%2FVIcMy9e5AiTvm7roSjcgpRVso3r2bJ1lsP8JreHP7KggNjlHJSZa\
  2T0FUICtgysRxrJ9hg8%2Bt8N8VBzSgBOACRp7AKOgTmwT3wNuBx9qbhzV1dEs4pm8oq5CG4DqBxf\
  rs1r%2BfP0Rm8SfSemaI9T%2BbcAs%2BUTF%2FYE6STbIyRS1w38IyrTG3nKm8LAaMkYJBF%2FUbE\
  FXO1Rm3aZOyuAaL40xNawioHR%2F24SdOyzkAP7WDZysKBeWIoqZ0wwKsSlBygzVkq8g%2B%2F8Bw\
  qxcvi91uM%2FYLxWZsrKVVZdgHSzZWAf4x6u0K659aWB74NaDecruJKnzPxB1q%2Fr%2B2x5VysMh\
  vBC6zF38M%2B22ipxpa%2FW3dnsYbMl%2FjisLrfENHzPxv564MLnlxz%2BLKN%2BVLxc%2FWnrAh\
  aZxIYBSPV3BCHURXtgdcLU7SF18TisByToGm7NDfiqqLOPPMcotl%2BWnezG5ddTIpCyfRZ6exYFZ\
  lcWMAr3TDkoG8eEhpWigNAN0lPkZ2Sqlj11Illfz%2FZKbm%2BTrdKiCqCWuK1yeXI8670BfFSVHj\
  Ec8E7hbvAPpNnd9Gd%2Bc37Xdg54TeOmNlyBzUw9d6avQY6pgFfAMETYwauRdLK8EguHZKz3u6tAO\
  Hvn2iemQnrsiHEaogq81CROfU216ULkC0A9JF5Luto4wAx81A2SfRf4amGs0UB5%2Fu5ydT3k6zcQ\
  tqIiEmaUoPlNc4KmU%2BANWxiypf%2FG2HZSnEIEizuzjNH%2BAmNOC1LU%2BjpyVL9SSvmFwVnML\
  sudI8l09yXV7EnwtJD%2FiboHXVXCGKW48aHM%2FGj63UIyyaoAhc5&X-Amz-Signature=0bed00\
  3eaff20bc30d1858c93b8fd54c7631de62f3871726586dc44b3599518c&X-Amz-SignedHeader\
  s=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WGYABPQD%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T014250Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJGMEQCIH3e5lesbNkF9XL6doAAFbIP3Kd%2B6\
        JL9PVKy0dmgX4wQAiBR7fLpPLB5zN2pIYJH1Nhy%2BzSmeeQ5wEBSZGnkJSi%2B5CqIBAiC\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM2NmR6KWOdY36QyL\
        UKtwD2I0Njo3RBZP3ZkqCVgRii0KFNq6HtsCD%2F8NOMcpxVkTgh11%2FYaVxXwyKp38LWS\
        NoqR2wPCPZix3esGiDiP8U0ky3%2BmigcAtZMihHNzQyhocnrOou8RxrQFoudbbNHDTi8VN\
        y8bj%2BY7pSPylE36OgNXTJ17hbUa%2FQEXH0JDAmktwMsJfKnpnyLlqWSSOQ5KFl3zpMEb\
        56C1vqeN7rhyfzLpGpGKNWR%2F%2Fm31LIaMVdYOve9tp4bXjePZq2R4QFJ%2FYlwMy6SXM\
        98nsjzVXnh6LgW1UvDaQ5w%2BlKFwyFVDb8p0N5l1uwIqx4mHmYYw1IlHNE6zTMCsz4MZM0\
        S%2BSrDm%2BOXWeDT9C8hWCgJPGa2aXHfxmoHFSu%2F0UvVvXxkPfiKDG7TiAAQOCNWVywh\
        yell4Cw44d8VolTC4mxRxbzKfjyxt1dM%2BYmtE%2BJfAfQreu11%2ByWiRsIUupQzahjzQ\
        wwEP4HvVFr%2FPlNLd2ON6edXa39lp5h35UD1u6HscmMhNJ12d3kt7%2BdA4niGuyZoqZ5Z\
        UEK5TB%2BZ8M9Xpslw6NvKMsg6au26dMJQN8ACjWFyTE7S93y1aqwnQeeKlnsl3z2JZTA0x\
        UlGisEPVHrxeBGwzg3GB7hqAZLEj%2B4ZoqsLp0w7N6avQY6pgEoJoY4KA5hqUZ0F3Pt6LZ\
        dAiN4gKqtlxIt1I3Od6%2BbGPiIqc%2FFzBAd7mdoLe9Z6%2Blc0nkwDWjLmraa2cQnf5d6\
        4D%2FAaVd0lKQnLeOssJmDV2FtZaDXYzm8mbcqu%2Fgic0UjQl%2FeRYCri0ypJJx08JISI\
        pUN%2F12QYCVHHcyRh1wuS3ilCSgl7wrtgwcJMkg1qhBuxwBWMJdYWlnYtBog2NQH7KO3UY\
        F%2F&X-Amz-Signature=d49ddad9ea3259e2bcea17781588d161cccdce04056b6c4c81\
        d88a0c1ba29c28&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T02:42:50.623Z"
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
UPDATE_TIME: "2025-02-08T01:44:03.777Z"
EXPIRY_TIME: "2025-02-08T02:43:54.115Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=c77e24ef6b94b812104498576784cbbf16287a74b91cd86e3d07b4f3eeb9024f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=4b64c690a2acfca8e85785a6e7b1f615d1b45aad66552306b91d2ea43051756e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=666d462c8f20f810cedc08cd60ad9615df310f9ee7c1b11f4a4e35e9485d425a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=7fde3abefdc7aa4bdb4fcc7aaa88b28247c1a5ecec6f7790f92d20c48845c464&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=828342d884360d8686061e846805c2326d7c70eca34e93de2c356e89e646a0bc&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667TGHVVGB%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCouFHLfzd2AQJal7ue6qhh%2FYv5En0EBB9pSVGIEoAzQgIgNJyrKDYZco82qfR0PkFiDJex6hHRI4iBG2LkRLXdP4gqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMb5L7Yk3g%2BCbIeVWyrcA1yVDKdBdv%2BIfyFm4brJTkDrLLER18qs70zk531zAHuFbr2RD1T0z74Bxg1eahhW287zkvQ6Hn%2BfncK%2BS5UBmZ879RgrTh5eDtUEqFu0j3F%2FuuItvHBTQ3%2BtFtGZJOlXjvY8uP4x0mg%2B47ynvlUZSYrnxFVGAQfTvNRwNUjMzhs1JyLRA0mJPNeV5xMc43MrA4%2BTLmP%2BZJBQn97QIop2doPZJKVJ1MydRnQ1I66SD%2B0fOLgIJMQjVvISt%2FNguS%2B22CRFCLuCjYRsoLLcFTawkpaUOuFd2xRCvezQ4h0Wwo5tzUOXITghaXXket4b7Vv6K%2FdtCO71qXqgxurDu%2BqDprOz%2Bd6KFODnQUYLVnqHyGDUdXB5zlJlXER0iTTyiCveHNFliPvoz59gpPk1pyoSuHltwDnUtEc6zkgo7%2BNpgmpR7ckICwAgp0d0pi79c%2Bp1P6kP%2BnWVMXMCsrhF7632MO17qFPRGzNDxEMZftO4H8HKHNTUVP%2FmZ%2FKRG2etoF6VAZa9wYItX0SkxUdGHXUre7tLjmd6p30ihLjVl8jKG98U%2FOodf5srz4Imo%2BSnx%2B8CPrDEV5CziPt%2BQr%2FPX9L4A%2BKyobxuEwasg0SFmXkzrcbYAcepVkRdUYnwa8sFMIffmr0GOqUBgq74PHsnuBV%2FqsYBizd5CJag%2FG2GyGLOBwSVyAhA%2BC24JMvl4IX%2B5h0063ehTd2zEgeViHFPNMQnGY5hOF2HeZKd0afL78MpprB3diHS5dXKYD9jALjs4g3iWEM0kNQx5XPa%2F9dl3uDVmjm8dh8vuboIM67a%2B3MT%2Fewvqkpi0rJJrgwkpHmgQKGxZcOMKuDCUvvWTb2XL07sp9w7EYs33v%2FehzZa&X-Amz-Signature=f112e8c1d4af48563def9facfdafe85ca8d916f35f2f1147786068ec71737466&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SAMSOG5M%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJGMEQCIDUIzpNfVorJw77hMchmmliMzWFYTosvRUIY3z7EHslFAiA9%2BrLInfynyY9%2FMG8k2j%2Fa3H5cxma4YORNbcOY7QHp0CqIBAiC%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMfxKgXDeY1vYRheWEKtwDh%2Fmxkg0x0VhUCS1wXcItRYXypjr0wrQFjDnQ0l1%2BLiSYoiEgyEjZeAoO4gTZ5gVfsdIK5fZo3BzZcytajcj5IZe1uGATzMW69yU7PfX7CqGbO9w1oPxPU6kVN59P0JqHynNzqw00WDtTz72GFn0t9WdpB9puizuhJOY3WMAEUxCq0BvXfojyI0OQu4C3mDOxg5xBARAA01NN3yHKs6YvJ8Ea3OtdBoOF8UGMpP7TFseXh9QZDSrRUOXWnkiZvS48sKLKENs8T1VpD0kV2qbj5QDyuf93UgXTlgwh%2B6hGb482vJZG%2F90NcBlA24q0CXGSY%2FWzlePIg%2FfRI8UhffftuzY3Lk6WAFeYo%2BZLdpZDLPCSPdE7LhZfTZkcpNdSO7TCHqrqN%2B45oGRchXQoCOZ5uX93GkUik%2FauTwGXVctK4X93ugBO%2FRo%2BJC57xODlr2mBCCbYWkQvZ7bnHjXJtohJwSUmMQxZUSM41JkSp1%2BlpvZuIXo5cvZvUWueaPT7otYtSaXWbisSGO1Xd1NaWCQWG5FvVzuvQ3%2BN9dVlizWjrRcgPv2zOxvZZ9P%2BNZQHfTy6EY8VQOkuHsqIP4%2BDmqCv%2FzExpT4OIhOBVNI6TtLAfSa437fzoxR795xpSF4wst6avQY6pgG4DruFPVWKQPQeBQlEPB9WQ4K54SwFZoywKXSduWPGvpbucq%2BxppsSaD%2BDC5Za8zN41qK1prqcFLL7zDGmKT6R9pelbW0s2cZOZlnaLwZVm4sTNu3k1wuQFHaHXXIlBFi69ynYoG%2Fe8aiCIcvAYBDhVdopVBgxy1gXIzAjcCEqmB%2BdFzEFF0OO6Plc6KFHYtYmlIjKq5SsmTnJWvXMbEa%2F0KKWARm2&X-Amz-Signature=58d46b972b43b62c70780a8b30884c753682fcf63446ddf7d09f9f40ccdcd07e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=128bb254f5ea352763336a065b6f6bb4309a797b545a42b9184f47e7b8e8f998&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=b9740772b5ab1c6426a4bde368f8e2ea0049f9fdd4c0589986d1c5261c63354e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665M5263PW%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T014354Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGkaCXVzLXdlc3QtMiJHMEUCIQCrz9dcZw%2BcIsSg9wbqmKdS50XjYofA1IYwzYekc3u8KgIgE0eema1FsjREy3tVhGu%2FfZrcdlP3tXbBCb6FSUWkHkcqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCO7lpV8ibLGVENoMCrcAxM4DzuYySVyqo8%2FP9TrCUKa5oJFu5jIRNOws1kcJTQNJJwv1uAc9UXojZn4mQfMS2hUP%2BWG9Zo%2FMwqXPGYuVYsCKZrVEQgQ7WxKMA5llIkk%2BPDmCiv6OYMbDFPGu%2B%2BsdJNWV6boXErBkHi02Q3exYoSGeRiE%2BeM4YxId9MZuC%2BK1z7x3NyAolMm6ndl2sDv8RNlm7NzOZ1lgK7eB%2BnLXTRJQyrftjeFUMnX9yggzV0cEXgzVVI9ZaxMZ9JxJrx6IuRmcJLKggkJP6d2Rod39d4EchN2LGayB7pn%2F3s%2Bu9chz%2FT%2BEU47PhiL7d8bRWjT%2FfiziLl5hCgDM1qApvGgF2%2F19Mxrjhqyt5T4oxDGX05NiAMqmrnFW7YkXgpkX5R%2BMNUiiLcKIPmf%2FqMjNZXyVqWpqGs%2Bbog9p%2BZuxK5jnk02bZqkAxaUHDMBBhQTn2Y4Hscuu8MA45tnjI1Wbkl6ueyiGoM9MZhwqPsP8fXnPqvnS5x90lDG3pL4oXoUMxQ6hLVL6wzR%2FOkJdHMorLQNiCaS%2BCLyW97arxH6ns7U558hdS39WF47IZWV8fIaSSu6Wb6bLmgvOnhTgAfWygl563mNAnuWu17CxohJgKlSWG7vrJZeKlMvAmcwTXszMOzemr0GOqUB%2BFfsuqXdQ04zzpNb%2F2N%2FNeYDEODp2YO2y%2FdebaqZ4mNBvk6TUW%2BsyD6eqCv8gpLOhtlZZIsRp0%2B7OZ63I79%2BMpc%2F%2FpTsY6H8LgOKvaS0m%2Bgt%2FwPr%2FN%2BgS9l1r%2FYR0IGEb%2BXYSA%2BIBS6mHSpcFSXbNtWCS2Uvk9BMbYxZ7M8N7mdWRbR3BHKvWb81OqZdksItWdYTYEmwkIB3Ozuph%2BjzkFanh%2Bkv&X-Amz-Signature=74befc170786666bd78d164faa01fcd22bdc977179af791169ffff4447079c4f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

