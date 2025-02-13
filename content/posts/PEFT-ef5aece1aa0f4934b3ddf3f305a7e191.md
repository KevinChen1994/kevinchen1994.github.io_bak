---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466Q5ESXNI6%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T032743Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIH2mn78bbTZPRYXsW1L\
  9ZXuLC1sov3%2BLyY7NzPsierfmAiEAnj4qyhAY%2BLlTe68u3E8ZzTIIzb1tolgytAxAQz03pL4q\
  iAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCpZUzG24FsqN\
  VpaPCrcA%2F1IOqELI%2FXfNtk42f0Zd4SfPWFg8u5FLKB3rDSOUfk3vxldZxXLrxsV7X%2F3zfO3\
  ixueFDew0771hEZmkr6wEfTuefW48D8LSAATnVDuf6Os4dhqR7yyNHk%2FyHsKbDQLuytJtXV5zOQ\
  CvPOpzGsIrfxcYBSsNtcNvqC%2BoXEOIlneXZvXDZX4iRrd5t6r1WucGx%2FZL4V7QTQUa2BG55Fs\
  UDYoNiqGra%2Fz%2BBPjLuhqAOBsZvc3D6FplyEKVRakFxFxtfW2OQFmfDpuZ%2FZRxomI%2BPyUp\
  3pTsvZkIGqs3IVOKyZa%2FHvPefc2gxDGGY3RAiRSWQA2WtmyolwuzlCebpP8V%2B370yCYAzEjyr\
  yZgE7DvXnk%2FAowoO%2Fq7pc6%2FAzKUwPEcYMzXw0SVi1I%2BJ3cwgbKcrG%2BqS5tcUmXYpGop\
  FKXdc7uyZ75YOttYdMYL5JBUPMZyXc5rZpMDB5rsWh7lB%2BXSFvL18khQ29jl%2FKlRevY6ErZr5\
  CAry0GUIOOLWpWVyhe01CD9WdrnL1EMPZQIms5hI5CSeQWXw2RtWeU6HfpdBGI%2FQMrOZ6xSU7jX\
  l2b2MNbn47nHGWmG2K0dXlVxtD3Uraho6kvvOUNP%2BHIOa5FnVm7EM06lbehOErewOOqMPaYtb0G\
  OqUBfRV4TPO4ZxkuXVxtMS8HHpJS8Fskk%2FGCle1G%2BInMgITv2Sone%2FmkkZQ%2F3Jbj4Zet8\
  6Aoxi1g3Wxh4mbiZMN%2BZehbH5r27Hf7zmj4v39k15jbWm1O8YljlpcfRx5%2FOtCZfYfeqIAIPs\
  Rh6q7ao%2BLROnIVIw%2FflbkN8NAsGF8RwrlGvHL%2F%2BpQWPOOVJgOZ2itV3JUlx%2F1%2FQDB\
  %2FE%2FkQhsMulvOgoyaQ&X-Amz-Signature=ee7e828e43b226378244f4fca290b62d64838a8\
  57a04069a60b47cd58ab5598d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XQIBY6X7%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T032619Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQD6MUQn1BDUOsZH4NdoJBUPzwpolf5sz%2BcVv%2B6%2BKJJICwIhAIG69TbpYbsgj84u\
        njjPA3wGNfjk%2FT0ih19vBogD5J0UKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQA\
        BoMNjM3NDIzMTgzODA1IgwDln2ujrYyjWMQCWgq3ANMpT09UOTrXKqm%2BFDKDdzmiBEHPr\
        SYGxjG2I7yQIIIBaAdPbVMGLAriAmoGigw4G8HNckA7sTABQ8uPweZi6Q9V5R4VLztN%2Bk\
        1hpiCNQwy%2FYZWJ793AqTWd7E5JOAkzaFhRkaXy%2FXrFw1FAVjzKLvgB2nIgDoM%2BPN3\
        h1eACVRCHd6PZOZ%2FDzV953Qeri0YQuxNs3qw52fZPE7uszAP7H7D6pE%2BvKCo6Nydu8x\
        t2S6yQZoNe1ErImtB74nNUw%2F5apabnWWMhaS%2BYTFGKGLsPNZgHRSdzwb%2BK2AgMjnd\
        QsXsvEzRzcjP5wsoxlLkGhtYmo84%2BmJ0EeX%2Br%2BBzN6EOyI26YBduIMTlOZlYSkbj3\
        8QhqkpoPzTfBaERsuOtzNI4rDVl2970MUnFNuYUr%2FOP7SmEqk0kqElYU%2BuIV1gAQ0er\
        ayqy7cuddNgX2DC1UYTFtr6aFNlc1wDFHh2nlCBYR4Z13%2FglOelcZ0MsM%2BOR4H2JVmk\
        nWLeciZZ7TiWCG9Ne8j2xCgl45PH%2FR4pYpqm9sNicf0Bw7CVHpiyR5R5mnLCV3OiI0N7g\
        1kJeThviXwzw6HVVhxlYx6vhlyPGovMMVHQCrCmfdvGedVz8MePprKhzuviLsYJb4DLoFhl\
        o%2BzCymLW9BjqkAcB3Z1oUAW5M54QJ3zkRde7Y9dS%2F9kHKfftgBwsCBFeyaXhhAfc4LD\
        ryk4NTX0bkS2ruRgMl%2BqS67eU9AUwfyrDKGXJUIWUie0SunoCOdAnt6oYkPl59lNGIYCl\
        OH8EJpM7vv6MbwQHDnbcp%2FxJkVJEos2oDVa9snA92Ji0Qlmbno3Eh26%2F8yB5NkuJlCp\
        kpwjdemq4PE1rhoVsJIJ1k559UeOVp&X-Amz-Signature=be6c2d8833f1dfe6260581e2\
        c62adb40fa243704e8de35c0eb1783ee3e6b3e15&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-13T04:26:19.685Z"
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
UPDATE_TIME: "2025-02-13T03:27:48.802Z"
EXPIRY_TIME: "2025-02-13T04:27:41.798Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=c2698d1ba11da6c1193d93d8ab5bc0d40b9106b8bd7376773e00fe043d95c697&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=37d76fec4754ac8b769cbcb84bd9008ffe495da7a6635baf1b5a138af4dd0af2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=96008988468d95230b52407660738d08c041bc7db7e2b2f37b76c4d759678738&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=809507273d0ead953b7459d54752dc971de176245cf60a298f21ff107b5ac8d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=b39f5918abdccffe6a8cc20f839fd0d4022a9f6dc9c23cf7ebcd1f7183530339&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RZJDEE7T%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDV%2BYY4XzxqNbqpCurJz%2B%2F%2FGYmk4I5B2q3OvZo8A0dbjgIhAM4TFNgIfrJjVTbYkm4AXQ78LiPwAnMogxHl%2BzqoMaAiKogECPv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxyvS7o%2BprlU%2FRs7H0q3APJXS0O9WiDXZ9Uy%2BfjeZeEFzY3HulYbgcJvTdRbQbVZISWBP%2FoHKvyJ14llaVs4n6ElL2klui0WiMD5ZypJKNAIWQA5XBG%2BYobfOC9Y1stymUkD2MfRO6eibKUf4maQly80Nw25FrHf2hBos9IZAFI3M0y6TEAaFcBzFRrhkTnbubDjMgH1EEZ0mGoNAcktJLeWcZ%2FP5oC2EpGR19RWwGxCqIFn9yYW6xT3SUdEgHTu7Sani41PwL%2Ba94yV%2BTKm3QbHYo7aFn3u9OfOqM66OQ8W%2BhIH2o%2FziQxzyk6pJbxaBtrGJAGWb7oDM15IE3PesqOARL%2FOvvFwDFVYjrA0Jd7mKoU%2Be6UZFe1dp9406dkAMfUxE92p5qW1G8fCPR0%2BI7iapt4qKEUUGiAmUjvmupBE3uIIIUAcaYhbFl%2BOur2xiBbroz3jclE6ypjOFXd7Lsk8ZQgeMlf61mvDLO5XiwvUTOjPwtIo2uT3N7td6tUFlzmWBXGwutuHdvPDO5KrUU4WSHHUlvs1Hyrgu2Gq3447T%2Feav5pGuyqcih7j7zjVinPCFldR2O8GNYk95ILiZuW%2Fk7PStz4WcwVy%2BchqTncPeLa1YRxnDUdaOz8CNFHaH0NN0gTdmzb8xSJ1zDmmLW9BjqkAZpMIcxawdI7PyTtJIKaxKB%2BcpcYKp7M7og6qjag%2FPfcsrYYVV8FK2PRvbH8ahZB6PKrKwO%2Fb8lp8vr%2BZggzM99uFONic%2FZYOxz2EMUTy2uR%2BrfS5WyjCYU%2BHaXdlhfNowwxlpUUKm1znm2xupJqvVV4kULSI8OGQZzm7Pe16GkMv4HrWMu%2BJxmmZkG5hDarnQmIpsQUVIhJ2j1MzbUkfntpz06j&X-Amz-Signature=d882c027bb7b120933a1bd2015b0a85d3cd2063fba36de9ec59eb1ce64a5626a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46674LNJ3KX%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032743Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFn0Gd1%2BJ9hlZbNHI1Vavs5zzoIvAj2QZliLde1C6p%2F0AiEA9JamGNFiyqpbUgMaXRUUDhnblF%2BlKq4g7YKUOrJ91kYqiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJIxspPyrgEz0c32CSrcA8RZKJjy4%2BYAIPkRXG5JmQo8RE0HThGOmTdZNZ9CxhXAeaAbfkepf7QqAsfCWzNQC4oGno7bWYAL%2BGn9NfuB7i9Cp%2BJcyxsD4fzwJhlhuwlCQHFbIaROgafxjtrjBGF2fsevKf6vl9qAG%2BB4qGOfwt6lDE%2FVkABeVf4QsUgqhZTpGbBkPygwOK70kBhiEOB0KkgAhlxZg26wytoIKOyfpA%2FqN7a6AqK2yfs%2BZ2iV%2BHUZBFoHxhWhrznl5W8SbMjnWZKy4TrNG33o4wVm5ea72LvOE%2B7GHghwVmvofUAa%2BiFyY%2FdSodXtx2grisKPLQn7Ib4BW0rkRSg%2BWoehuqj2cWJRKRq3zYQdUqhPtbRZ7Xf1QIf4JwOZCKvOU2RNcs%2FKoZUZpZQjPpEzOnBdm7qiSftoNgxpZbtMo%2Fo5X%2Bnvi3%2FN4q%2Fi%2B9XleNKDrf0UNJF%2BRYyA%2Fs1SUGt7I4DErUTLwDGUrM6ZxUuwXRnpagXZHbg7%2B2ALUd2B5XfVOp%2BYAw0WFO36J9KUr6JLL6gE8tz5bBR8%2BVhgygmJaOuJKkcxvBkCi3wJjcdkg2pGRf3rhc26zv5Cp4UfrWWK26IeTBvF5o8JXOC0oLNfPLiY8rdS%2FzJ3eQRukAnei%2BgAFcvbMP%2BYtb0GOqUB4mQdSqQLL6sfrlGicBoZhyPincv5zCU0fz3ZEgQbS7QcSEMcx90q0LdoUjT2B3QFQiop0BxTmXcAmQrg0UGcD73%2FzUjOTBqQIN5Tz1Hnsm3W%2FStJrgU23DfeJMiF%2BkS2uNRF4nKmdSVxhQxjo1pP8PgStf%2FtwT53I03BmWYDMRQIGn1sCfKcASzOQTUHJd344jsWcp%2FpuACCAKv8qZbONkFf3OZO&X-Amz-Signature=fbdd247209bc14f705e425100fab7a013fc03e451537de736976d6f7f3a0b8f7&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=8239633cb9ea949c9971c2a2bf0402afc0628e8492bf0a2f0005dfa94fba0fd6&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=a63060368f43d0fdb3cee41e59003d104183c5fd4a46e2258da3222b58c03169&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664OF5G7ZL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T032742Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDggYliFDUQ4197kqHukGnNSPwfNpAy4kcv4hcmAmi0wgIgcsraqbS4lkLwxKoIz0EmLyxLgkrd4RL%2BQJuTCK%2Fq5d4qiAQI%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOstJOzQ4NaeH0VrByrcA0Vgh5tTIwgPwEvS668hlMAWhMkGER4Nca%2FJY5RVllFv2padNMVvROlHAOST5lBdRB28KjScjh3uJrxelTW7vmgoVPHv%2BR%2BMuiRwLlSXtJRa0%2Bh1q74TomGT%2FzGFw3kybPRJyDcc5VaqOlkk6AwrWaw4p2XQli%2B71q5jCoyhsj97Ip6gwvoehJfil%2FrtlDDv%2BKoljpb0unVisj%2FOepH4Mqlnu2aJKkA6lMmD8JYdDE8E2nkyVYgtNQF8LezVp8rFvT2h4IDKIe6zJrHr8YIIsfQbk%2Fnl2aTFZn%2FLcS4Od9AwWvXHeAabcHT1GMFxyNJHaXODPTbSdjiAqKs74FocIo%2FGpblSKWTC0gRbtyAbG4Wp8TiBptSKTU1wlfMOWTpEU4JfbSaXWhY4lk54WatWB%2Bq0%2FseEcyl8yVyxaX%2BrzgcDddet13HxCtHiuwHPmWjIM3%2B8h6%2BMswC5gm1YHf1ElzCrcs6STRliNeAowLAKZuQBn0wGKsY13TUdPL%2B8spPYIVQlA4Nhne9LMySmnD%2FzapJE2hDPccgWhaiT4fisKY%2FQA9bgC7TXxrN46T9sF74isLiu5yjVAdo0%2BTgYfN3saa9nc%2FXpF0JGkdJILs6Kb1z9GX5KNHyNnjyR1mXJMMmYtb0GOqUBMRzKdaOoJ%2BFwAVJCYCnhF5maW6ZwzdAcdAhtC%2FOcFrE2gSgLJRKKRLSHMLDOzzySvORCE8tcOzOASJXVlEW90wbPxJrxt7TvzIa%2F%2FrNaTGhc06s1sSL1%2BqOCiUrmnSaTABCYQ1j5fE7o80p812egyUCk1tI30qK4p5i4DxAiUK5Aqsp%2B5R2OPM%2FKe6zJHZJqVDdVETLahLWLtDnHgkxGjIK3aKZn&X-Amz-Signature=93cc28307998af97d1382a6ced945214a4a072e6fbd02752698ad3ca1c0c679d&X-Amz-SignedHeaders=host&x-id=GetObject)


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

