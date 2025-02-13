---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666W2K525M%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T102600Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAdnPl9SSoV7nchi4Dj\
  mXYOcYWW%2Fqh1sclsJveqmkj8pAiBEJHcH2%2BUdT6GuTBUule4dVTHSdKb72HYxbvtm0Q6Spir%\
  2FAwgTEAAaDDYzNzQyMzE4MzgwNSIMYjZv3CGtH9m%2BSY7kKtwDQZVnA3JCj%2B%2F3UKBHTVNL1\
  xbh8GNjcG%2BwTajJkwxuAObNEwdQa1laNgLi3cDlaA%2BW7rnKOKIifZUYO6wzQlGRaEhuXUJSQH\
  vTtb%2FJYEuaEB2jvofb4Zosdm21tBCfRfo111BsTmFGVc9yOOd4VHRRDxcAd9hE2cuyjrEoFfOsh\
  MlCony213hf6FwKFkHfaI97cRZFwwdkrTmxtQvqbwFr%2B8fRG9mKbPNK57r6JAwHjJ7vToboVNfk\
  kmobIJ3Rm5BSfVg%2FnolxWGTOP6F4oSQcQZj9KbmjYZU4%2BKQb1NTRWwmgwfeRVnmpsXPHjwk%2\
  BDHyLzxnJaYfii%2FJkC43HTENELy%2Fbeh7scjMusJxKpdo0kNWH6NQNBjVm44jRC5ypTc3FNWMY\
  q0s4ZA7Th2fCtPSOX5%2BfFaANPyTJ5dg84NmQtv%2Bk39FIWiIHT7N3iGWpjHOv1oSr3zeRFTRAg\
  ArrOfY7%2FaSzm%2BwzmttI4Yp7JQsTQb7DqBtVitRwO1l5IPdCHOJZhdBOGUMnCSSI5YX8L3hbx0\
  jF7SinY%2BaTDEqaTxz4DE0UxqyavF5jWTOklT8pp5KRDAmOlwjkUQAft%2F5tJHZxyMAaWXh%2Bg\
  IW7bZ3xjpCix5mH9omBBzz4wdRipYcwmoa3vQY6pgH2Aj%2FAEujn547QhoFHq117fpyMaPiBagjm\
  2QB%2B7mC8yGVPvwrhr1iUKv0RB5EKTnnkY48%2FlPfSHtRSmCVhaAHLKczDot%2BF2MHpPIULukk\
  rNcOQwpcmlyUZpEz6WdVw8pXcg84KnFXTxdIhUWhuXCKLJhesIQSYJjAYk6gtMfolWRHDMbVWgE5M\
  gjucwVTZugaWl0v37Xoke1%2FN8BFif9T73fZ5iZDj&X-Amz-Signature=ed1784d870c1b6b19d\
  eb242deb26d357c084d178968c2962eb34d795c1b59326&X-Amz-SignedHeaders=host&x-id=\
  GetObject"
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
        redential=ASIAZI2LB466656TRUJV%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T102436Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CICt5j5Sz%2F%2Fi3ejNVStgCTJH0skCtFTxGlOI15%2BLWfbacAiEArA25hc4pOIUhrz%2\
        BBeqeke5HiLzZvHD032DjMpqX2iZYq%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDOJOlXZsdyW\
        qKRNMiSrcAwACATAMiOyEmauXBU9KqRvi%2FTMm%2BAygRIlDIFuSsZzOs9AzXh3gCC1rCg\
        5tePBaEJJf7fnxvwY4ujuHnX%2BnSt0l0XC3rObICnQj8%2FktE1HUHLT1lSgwbGGpaFUEZ\
        DdO2BiWLzLLb42ZtEqF9nl1%2FajnPKuZw177Tq%2FjORDEUkDY2vF%2BwPMKIBrzHa17dp\
        nmRNLp96aYFCqBRcTdYaNVHt05pIjs%2FV6c73QyfWE1ILUgjxYZsooa5m%2FbRSnh6NxhR\
        M46IR0NBrgZd40LPf%2FwvOkQ0DWK%2FJkKY8LD41rtEKd1EvhcKjrblHfIyLktfSPiNrJP\
        3cTpkvcPlckurYV9LECXCki6bSogq1XGTvPdxDX4FpY5mXtxWV6KwzkhikFNOpxhvzKnJqZ\
        MoPHh9sZr%2F3FIBK%2BVXR4e%2B6Xw781y7YipMUNKJw6S5rxm4o9HrpCiGrdlhSzxYsbB\
        9MBBE%2Bgcn5lHBJXxAppeahRFE%2FfCd3anDEaLPIXeeotJRfQAr%2BlX3jdyLHkomM8Ax\
        ik%2Bredwwfi99gs8rYCbG4j3LBPpzA%2BREHoIvZ7l%2BlhSQwBS2gvuCS0NL8QFjxOhCP\
        Zh9kpXubMwO3yrrp7Xd5SnFjEJVV9AHA5Fizp1OCnr8i7bMJOGt70GOqUBgL8FmWzAZCewC\
        OZUOPvzFZvgdcMnhzbLhFpW1zOklNXQIEotq1h2%2F%2FT9g0%2B4a%2FP%2BAs8GtbzvaQ\
        Z1OSsPxczWyeMDnzLIUGomzErnfryhiSyFmBpEfP6jZz%2BNOYW9nvHnF%2B7lvlxJ2krpM\
        WF6XSSWj12o9WMZgFKKM46ObTynWhOfUTvhIvl1KklkG%2Bhk%2B1dMYt%2Fo%2FkPmvwvt\
        pKbQNCTmvGGC1m50&X-Amz-Signature=0896295b9b638dbd6f2dcfda34496d37433f8b\
        c1c25d22b9f48f7cce51296c30&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T11:24:36.110Z"
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
UPDATE_TIME: "2025-02-13T10:26:04.166Z"
EXPIRY_TIME: "2025-02-13T11:25:55.440Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=5344b1d02fd7d30be63667cbe2a986e927949cd61d44f6c0734e55fa0b189a4f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=9ce9c0e50e686f88b6787d066ba0aa6c9497f6c713e1ed36d9c3717b13004bd6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=6f6810b79452b8cd68c978e0c4f21b802c3017317305388774dff5c09fdb0ac5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=fc09207532b6d20fd3d845bb39dce3844a52a6ec3e9402784125b0ea72ffd5f4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=364af156dfa8f6b7788a2fbb64e9a2ee775a681c1aa333b0257b49eba93aba54&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Q7QM7T5N%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIANYY25c7J7yusz6jXdZf6XygZxRI%2BFDRcWPXW5EbUvwAiBjywk6vGO564sWZx7dFtbts%2BWJ4OIMsEZ5bwEiyFFHzCr%2FAwgTEAAaDDYzNzQyMzE4MzgwNSIMWRBxtTXmGngB%2FxcAKtwDc6gI2XzdJ%2BPwikzq1AoIURGza4dlgyl7aoIq9zH1qePEhkhoyUCztnljL7xG1eTGh%2BpX4OhlYIabcOb68p13CTlHUvtzlaxHJ5pRBClG7P4yEEVbmL4bxcl0BIk8ZkIEk7V5YXah1iRR4CGAOlpAqPSxEKydxMjJattUDp739Yd8hs8HxTuilLEN1fBaOtIPXDJCTek%2FD6D85s9qcP8OGnfwse0z%2Bh%2Fzc53XDOC6IUNoeIqJypoJOjqWtNViRzYzlramOR5awt2g5273OWWLN5cJO41Eb84pL0XcXqaYUz0MzucA3mah%2BV66fXfH%2Bm%2FRhtr0dES%2FZi1ZLHxsj6B1DFI%2FruVt6gyJRi9gZ1mBQNDQTzblbGNnI%2BlTIyYL6xviwa1xgsi5b%2FS%2BSMkJI9SO%2FJ%2FzUTujwE%2BiKnU6Tz%2BAw%2FNwBIfSftZRGwbETMzlktDPxDmz0eG7hO151Bb8hmEWXqDaOoYGevdS1MdlHzuOoqAvokrdL79F%2BjqHghSdcZIBifSb4u%2BuWBLjUoxqrTImRt9KwxbgSTrbUCMyMD6P4B7%2F6IhIXHmu1pfucfQgAP4Eyh28S1OJe0IG8GElx6i25PQvv3b0NP8x8BTbnXgl3zK%2B9pWTSI%2B6LGHh8qcw4Ie3vQY6pgG4q%2B2qwocPreJ4kUPa2IKY0ubO3wIAs1%2BJxcXTXsxS5D%2FS6X8Nd7WNPA6ZQFNgYoCutRwaynGLdHebFP8kprKo3gQvzypfaqWPXxZ%2BgDd5C%2BylSLI0KTYcq5H5vmbs4SG7sd%2BNlH%2ByxVQZAhc9JEgn8RQdgt4Q%2BmfP4CA11ztGDlCtUiGqc1ndzGImooGEqEE1XstSgTb1DqJWtFXu%2BzWmZKY9HVaH&X-Amz-Signature=10d6a656c595c08a9128e7a74f38a1717e79087d353669af9900b408984af482&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RFHJOFIU%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102557Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICW5VQytuMKzkkRseJIFD2I7qfzQ7P5ds2q62j7tQgmHAiEAiNrDlTaNmykf0bDiw5v4qqd8nWPEkGh3WUybSbwTqF4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDLsy8t%2FFH6KuNS2JhyrcA6X8tMw4cxRGDY9x8q0x6Lgu18UAo7b6fLTRxVLHo7KuloE13fl7NzWcfHq9ny7B6%2B39v4K4tM9PV4x2qrlOIJv0zOsUowVhjbsWRv5hjCwwJn4NBhBYn%2FQWHNTgyK3nhei%2Bajwi6zeSfHtRgjzNgd3CBb3qQKA3ztpgrBT4ChANdpehNSD9G9Nru1NGWrRUsV6CQXOFshvNAOSFmE6j%2FiJa39k8Ht7GfzKTE%2Bjhw2ZaGdbEL16hyg1nTCS1pbdI2zxX3bzAzRi5nL0UiNo5uy4A%2BTRiHmJwx0wY6ZXB29AVidXNkFh%2FnaE3D7DQWGIQupAtIhstDrd0lhnQ%2BiYwGkx5O1KRv3vAemwUzDudwZQolbLIjdKygr7GDuMPh01PTLmO8daJC0bBb78%2FN8NHyo198mWPtrQXk9zzYM1azTWe1GJh8D2bo4291ImwH0XAZFoR2mIBnuTOVPL1H3ogU4BfKD9j1PaIYZN%2Bkr8jLB04CiZ488%2BD4xQXA5O4XbwhkNJTvyvHj2xpGMqMCN%2BHGqkdzbBNtixTglUufMfAUAwSXkm58tV8DxBkUZMqx9QmVp%2B25ftvhvaXr4xh3QSPKXG7pvRqPCfAcPdiw%2B84q0KtWPH5hU2OrUh5%2FvBiML6Gt70GOqUBVgUuYWaods7EiBds8a0iTWZ6W11lGXcBQLMijOZdzD0phqPx6UMlqUAQuy%2Bv%2FfFuEFwE02l3Bk7GWmP%2BLOfVr%2FCsEwgfRRMt0w3KLuOoeL7a0a2g5fvjkpdjnWitM%2BndvY%2F%2BZbGFa7bsTLNgBUvZlsbpZf4WGV9b%2FHgZZbV5L8KZ8ECB%2FViJJo2Q%2FUx2%2FJe0vIze75AdPoveRNoQD1fB%2B6XvtpSj&X-Amz-Signature=36252c4ecdd2e2294a0d5636cbbfae51f3268adbca36a87c7722a2d9b9380e3e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=629e0b4db4451f6ba0c8b7d208360c3a01b681092677af29bb62cea3f9c8cde1&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=7afc9bf54fdc244f07c8bedfe570966bd9b2d9ac4561f6da25a37c36d17c4f15&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663T6EQOF2%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T102556Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD1E2ONs%2FjVIHaMRVaMJ%2BmcRi%2F0zvVfJ%2FiSjfw6gkxJKAIgVkA%2F%2FIVb8%2Fwa2VKpmr%2Bwo68cjwozoeegYnAd9mPSaC4q%2FwMIExAAGgw2Mzc0MjMxODM4MDUiDAfvry4bgQ3V54d62SrcAxMM7e7xi%2BzjWnh5Ku6E9k4x9QMsVpnkJ3Fo28YHtr5hgdm%2Bmpo9Dmdi0D3qyK9Q%2FFnOVSjx1aFlq62KId0BJOHe9209cXkoF%2B2Oki%2FRXsAUAA8R%2FFeSiieyY%2F0UtwIRp%2BRJBnMFICgSv%2FORNJ645IxipqoIVZBRCOBYOFLDQeERrhLJidNKc3AgmzbHYW8ONRIiEv4yc9rD8puw4OCCW7mFgqdfGfgCXpD5BircvTfnLWBB%2F2bz%2BGcsdUK7z2arebZu%2By4cmuDcRC5Pr72tD%2F6dItBz9UkgQZwr49KTbSIqGJlEElBVGIECaMbXHur3ov27iGvoY6OazDRyVQUYRawAK7%2BKf%2BKwQQjQr4d0nAMyfrDmPGFJxF7pczdtWSwhU4PiRPYowsMuju1%2FB79Q43PCTgTEA%2B%2B9KrvYhlOur0iY10ShkcQ1ngL2cJ7Cfxqjm5BZUFySlrZgcnkzt5vN2332Kv994RsXi%2BEsF047E3nUyXfGpTv9Z76pDwL6vUTJZhF3DRdkFHCHIrDFXDbKxKOmhLmT4O5dp4SX6v3kjJUAiNrtWjyqZqVoqwSeLTnZG9UoKyX4H4eslhX8RdEKz84xYVq4ebwSWhWAPXtS9KRjt%2F3UErWG6JUt2zwWMLaGt70GOqUBzaRyTlGFSzR89IK0EHz87%2BhEPjZngNuREOGnL3d6gFjc9W3xxy0XhyjHlKxPmqjex4KVCqCJSMJPoVG8BFVfshnKmGLR%2F3CbjeEhQOE4GReCoX%2BvE43v4SvuhpQ3JqFrwQ%2BQ6T%2FTIYHBKspFzqQXb2L3nGHHz4C5Td3WqdwDqyeiX6VlDLsgKWIi6GPww8I3wyGcWrOqLT8KbAe3vMu1%2Fe3mUKjf&X-Amz-Signature=7d4f80ed106ab65220363095aadae526f1449aa96b23741ad0f7f75c4a610262&X-Amz-SignedHeaders=host&x-id=GetObject)


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

