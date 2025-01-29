---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666UW3K5EA%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T191902Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBeOqU9vr7N1aXBy1Xq\
  xG1rmgLY%2BVr482s16gVgmXsjnAiEAvNJtgoOUk4DAGLK1D2bcqOqyyHTYP%2BG8fEsI6asWKBgq\
  iAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDG%2BtsHOfgWBcHBp\
  C7CrcA7QWqbTPacHgfDsiucf4ACtBibd1DpIulfaDMlMC4rSZ4L7esiuwuMB4gm4aON8qNVhQuGt4\
  vrIxybIHOFP2eKBQcp3TfJHRdSeACdKsfFIHRSVYLJHyg2iO%2FZBubzqq33XB40h3w9lO0lB5pLl\
  q3w4IV8kga%2FznSBEkTY1hIP%2FBVbyLejGRrpnYnD%2FA5x%2BqOEBpayVtyze0RCroe%2FoNcF\
  Vu2Yq5QdOwSYbfJMk5x9yaG1xUZJOwMxhM0uiYJFFuL4J%2BKLXsifs1fV26NP1dCHm7kdLiWOjHq\
  GctUE4WClOhwt49d0gePZYyqeY66bujaxp3%2Bnj9WDxKd03EQK1kKbtyC%2Bcms635JyceckUv55\
  cKZrpIUHQcatbpWBn56FCw8IqCjrjMAyCXWc7J0k3G6ovlBEn9Rh8s1TPv3%2F148mkJIYYiybJkx\
  qYc%2Bd1l3TCtut305pBZVP7nQv50%2FVg6ZAM7TVNliZOkbfEp%2BHbqVss14qsKn6sGiBDkO7Mw\
  P8Ms%2FY1VsYMVh%2Fmk%2BlosVD39MA7%2BZvTcg2zmdxV92lIIpyDyJSqKAerl0RjomOakY4pZ9\
  gRPF0%2BMJ8YlgZYEwTeBrCPrZGsFZlOp3e%2FBYmAQcYgXsBmiqsTUEC0CE0v9MPT26bwGOqUBja\
  Wfhpu3ywFPpwHPt4zYioyvCDxx%2FBfjsR1qsj0ra7rspEerUv1rWvwtRKUxwn3kcgIpokht440Tr\
  koR5eyJo6dL%2Fe%2BjwNriLciYBM3iGuzxy9gVIEBHcRDZ0W3ktZIFJmmjFaanYHoreQUkdekJv%\
  2BhDyxeXO7VYUfyd76bGgSCqA%2BKERm80fNwZkBokQxKBnpDXnc%2Fjf8b5i4GJQvSKx%2BD7YLz\
  N&X-Amz-Signature=e24887554fa610d2824a33bcb70f03d2a132f4f897599d5bfb380d0e648\
  094a9&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4663XEHJDRT%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T191739Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIGeiss%2FU5oecBwKft1OfLa011QiwJe1XWBqJH5%2BRTk%2BdAiAezmDZYQj9AGelO4cx\
        qM5oSuL1NblTFTgj1iYtf4JJLyqIBAiU%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIMRb%2FN%2Bp18LSHRis4TKtwD6XrdDwTxsNfdhimM1DIZXxc3v0s1Il\
        PMiHYbKB%2BMYq9mSByMhDm3Xy9ynZl%2BSam2QBZqn6WOVUuXHiS%2BaTPioQjK1XJxaX3\
        vkpvYNtIj9Wa1VN6ygdOlpYhRBmuq2Z5cvL6gLOrc7dTVFEOpv1TIfjM01mXBxxzkXaj0sb\
        IRt06lxyTIhCij9dX4ZfFmgK4Me8pr16YT4B4CeXMG59qvVxHPajHpgz8PHoXcG%2B9Fy8o\
        WFdgYmQmRftBUOFZIjVrzqN2tn5Ex2SvwcnDpT%2FdFsEJuPxdX%2FRkHuGJBab9YD4d0Ox\
        tb7AhxD4GQW7p91GjrfmhI0fxMVDnjeAF8bZ2f37lgL9RYI1TUy2bce280KAcoKF%2FVkiU\
        ZQv35n8%2Bbc%2Fs0ty%2Bc%2FbIArsW5Rg6IxAK0uiJTx%2BdqdgUfryJKQy0sQFh7xbaX\
        p2Cb5gMLcTOIbH10Lr9YflTBZ%2BPeuudC050CZqhmw9VoPeVt2UHoZVfh54oKDWhRVMyWF\
        92K8sxwyHI7MXRCA9uftG8ug2Mtm4c1ObfYMoaxle34f0AwyLqsJTA8qFj9xhU3DZnHG%2F\
        hUeZCUz1kfv7%2FzimOE2i8tfUiirRlbN2dNJ3ilYKw74veOM2rn2NwssHSb7qdSqckw6fX\
        pvAY6pgGxKTyHrgyeD9g8gs%2BXgHBi1OaJDsaxC7Bvk5k5iqCZIoTRQbrMA72DnouwEggf\
        ebtuLt84CfJQCebBMrHxKDniqnWXeYa0OTgm2UQJY4lUtXi3TAbujayJS0UVA9dk5YrVogX\
        6Bx%2FfSpvx%2FuaBsNnqO1UHYRJIxnBnF3b5WbEyhJT08QXQLOIC5qhceMZpWxcC5%2B0C\
        PuWxEWAfQCvgEw9Bfc5i9r2d&X-Amz-Signature=b0e286930b09b3c34f41a301acd26d\
        e8a657b41ca79fc979edc778c3ae86e3f9&X-Amz-SignedHeaders=host&x-id=GetObj\
        ect"
      expiry_time: "2025-01-29T20:17:39.917Z"
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
UPDATE_TIME: "2025-01-29T19:19:07.728Z"
EXPIRY_TIME: "2025-01-29T20:18:59.914Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=98033c86a78925a930d2e301b5cc07d0cd9f321e30cc5597732c968565072f98&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=a377be10dbb2f15c9d6594fd160be2e735e426ba724ee880cbed152edfcee229&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=d11c25fb75d6ad81451b81453bf41f889560a53eaf042b6aa3d352e9840ecc6e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=5275fe2000f195382098879fdf4361cfbdce565b61be96dc7ac6a30ab0d5f118&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=37c96911b6a6e854f12f15c4c50b93a95fc55363b818879877202c585a5e23c9&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KTVQTPO%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDSrRmn2fyaDGVTq0ByrTM9wsOHjYSJjlBPwhhemURzNgIgFGGp5AiCEx%2B%2BOTsoBYNP0NlPICm40rW94y4k0Hoa2w8qiAQIlP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPvWoAgRg1CrX6i4bSrcAzz57EtCAjUPXTyY70idW%2F6AltQXf1sx7K2KNXjaHUKPLkVf5HJxzqy4sL3Gy9PWmRfYgMRjr%2BfBQzyVuFWT1wiKVQtGPRHHWzbXRU%2Brs8EQA7KPVSXUDPlzIAYjrYS2VmPpSfzUz1EvFW3yudXlYQOOw4%2BqjLCKjJiEAekgeK0n3%2B0dcFNXS5scnD2t5XdFN%2BZsSnsBI5m%2BK8r0IYhO1CrpkAaX1WNOye7W58oqCgNsn1HI5fb7qzERhzquKu75cAUfNw%2BAf4YlO6n6mmAsAoLes%2FdvrJz2zRo%2FURXyQmbqTwuLpFv879GG%2BrkSr4VpqePJDN%2B3i1wcWstmerpp9zc%2FezFla5Uky8fpKM%2FddGiop2hJZh2OWDaoqYDok%2FuJf5HDwUOrE6hIP2QC%2BsQqYUrXpRyXywGdb4bDFaRHIE47neNRs%2B7uVOecTz3%2FJeP6q%2F2UGIELE5MoO7nubboeUPyoeEF8u6etChm81wG2tJ9G5FE9GJxhtlX4VKQgyHJLp%2FU7B7KjFaUItPbmmvBvphUsMbk%2BNSpWrVdtrhmr5FVXffZ4SvhqKmhde0C1UCFiSUpk7f3tJsAzWBwFOR9PIwgvafmX1YR7ep%2FJiMqLHQbctHp3n4Hz6FaF8E9nMPD26bwGOqUB032NihGeqo%2BwSkEiq7f3C8HDzUVdF38U7sxmlDmgQ%2F5OjGGhff5jVqBOWrs4J%2FX5M9%2FUTgCUHvookeXZ7mtceCwWSrJ4Rrl%2Be8TIMkbZaWzklKJRJPVgA1yHDbphwiR8Qu1L9DW7vGZPGvNnjxSuNRVZCh63HykmXu3I53XpwaaGyVZYAHhpfwKl%2B8AjtYXd8%2BDUph1JDJ3HIPB4olgWDN3U9Ejg&X-Amz-Signature=364986452d768967e873e596e6704775ac4b13a673307ba477e5ea29181aa5ae&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VGIU6QIW%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191901Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCR8Q6A8ewoLn6ztlQoto1g6qVb%2FuehPxZZ9NZKiFZULQIhAMWtOtrcxHwQRwie8Fh95natsjbE4FijypAi17MtoVfTKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwII3TBg2xg%2BhFX4vIq3APLwgcakNv2cK3FETb2oLIzBhT9vX8RUpO0%2FlZ8lpJ4vGs1%2F2dIqmV2myz0SbMAcWtLkq1qiGrne4%2BrJWoMW8VgGKIkSwOthaZWteWJpEQzZ7uyHXOfi3CzHFEkI7mcRmH%2BYhAO3VCtcCpcItfYyeBchDmfOAbpmr4Nm634XdHfXd1%2Fqke2ljiJI5wb2cQllx4at3Idj6o6dyPu3phQ7N1clf34eDfBZg0q%2FKzJotWoJTcfGg0F30ISLsutrfH7U983fKbyehA%2FWdHdKAHrAlcQFhTLK4QrCRVJ7Q4%2FxesFnGJneSM7ZDZCbi2OH9Slag%2BvEfK44V3p7p7y%2FlrI5Yi4WjIMWJCxw8%2BcJ9mxBhzwT9c9DVqcTbpy%2BUC2QvUdUpDI9sN3mpPXKZV%2F9z1VXhdaDupBYk7nPN29TE3zpyVprC87rIdY5LMYxM1bKt6q7vL%2BRSimsaTVcjfah%2F2%2FvSp3dj1jwlSSIW7Dok69nu9QQkJn7MamH87wQe%2BQhDbw7rDvSWaSXg%2FiF5NeCWVAYF7GC4WlpANZ2TY%2FdCftJ2sNKVPZfCj0wX%2BJYlP%2B1QkEAPLVXTPs%2B9cYbKBSXRdGV%2FBDVZBMDlBE8QfC3V7nSXvxtpslsEJB0PeMsFowLzDp9em8BjqkAXY4fwFGHivFvYcdrg%2FQQFBPEbUHKlOWBd51O0tmbNMsW%2Bn4emQoP%2FFMA1LCCFKjSWL4b%2BzMZn%2F4n9z%2FFwQWcDQrDrylPPKHkg%2BjcQ1HOdQf55hq7x%2BrZbYrP6HW%2F7WGmdgf1wBl33tkLtyiqUBZg5vOaDcGXAlN2nkKPDiQpWph2g7MfByb40IOkeF1CFiWA3dHrU9KrUwh4qQe9R0Y3np6KWt2&X-Amz-Signature=2cb5e5a4797984359a84146d0ed899e9f8becda0cba6b79310caf7b904c3a128&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=4263a359659485621dcd9f8f823a13491b184fbe486ab778e4e8d792306a57dc&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=436fca8b38e30ab4867e05711ae54d4030026c7315ca17e39142eab6ea5480b9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466TR27LCTF%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T191900Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQD0p1o1ek6ngesBrlbhZshs8v%2FZFG%2F1gaz3NDFBjdzrOAIhAOoXE2hHpdyeizPPfyux3OYpoOgFWSy8yawn%2BN9LCm%2FXKogECJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyoSJ97Ej%2BOiPQoGNwq3APfqP4CTrFZf%2BMAl5zwm91wIPu9PjtsG25LrN6pFl9vJqLJqx2jEFUUwCIy1R14VVDndHte6Zk8mKlpelghzMdVsCCcIjrOQrQfMNgse0uv%2FJsZHVKCq04woJ9AZrhfx8qt4WARgwC1RYdj8XMa3mGlR%2Fz8Za8O5jfIBZf6HifUZlfycYBtN4qA7XZVAeCjxibJRLB74hac7sKwydLizpwARFFUG5ePyxMEqxz%2F9Y0YnK0xn01NtPP276FnN0cO5lcdWJbIkgDGObp4ES07r0FrO2c0DrlwIUaVmCqiOEKQyGsXTfl%2BMVo3CUkpMgn9%2BQ%2BtxgXYPiFqEeW0M%2Bz9QQfH19sh7vECihCutxXgP8cwzB2eMzIfhaKFV4Pd%2BigzqVVdYIIFggaNfxMcP7yrv3sWdAmRKnYK3Dzo0qhD%2BqUGgVW%2F4TWbY4ZBoM%2F9ILx0UGdkY0tlySA5qwAPhg8%2B1A%2FsZJSQTvmGWHWRief0Goo602xXXZWcW85J6T72r06h1%2F4o7tVK6RNCfn0zvwGBdlP03V%2BBDjxBdsD%2BFfS12Sc3eFczyIlC605Ji5jPCnwRmce7VUjFDgm67jZO75OFqdrdBpfDi6FdIbP0GqW8FtL0lKI24n3AuhXlAstSizDf9um8BjqkAZJuaq9A0HAOBHi9%2FX9CsqKf6dFGqtOzkTsipzFtw3sNLZ%2BwhVJWPaL8vek9j%2Fegz4rWUH7%2BZqUlfSQSJENuLJSwZJVgLvPdMNfV1lj%2BQAe5U47z62Zcm5gAcQqhaWlvlgfx4J26BZl%2Fn8u%2FpQVHMiVv2BqzjCB%2FMxA1bVU6vG1kqlsDVVuqDlvr7997Q0RfL%2B64UUxFxv0OWwtxMgwriwDAcEGf&X-Amz-Signature=34e320eeb485846f3192e57cc29d07dc675f91c6f2d6f97bbfbd75475b2870e3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

