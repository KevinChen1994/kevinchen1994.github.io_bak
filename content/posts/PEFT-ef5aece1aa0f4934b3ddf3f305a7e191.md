---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YPEOUNSM%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250221T191840Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCZY%2F7U0pmIszL1M\
  vkPcRJugws97fcH16gGnHHW8oVy8wIgEnXSA0Qh70xkxJwoF%2FT%2BU6HpYcxh7g9pRwjxYlApGC\
  MqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHx7z7QlhZX3PUP\
  AWCrcA%2BIi6Dejz1RATwlyeB5xoAKIKV47Wh0Alm6JPlOJp7l3DBn76jZAYZ37eublBAgjjZ%2BT\
  ORMpMkudenJ9bxDTev1NzVd9E3WoozUe2B7ti6EORcb1MZ6BbWeDteQ8vgGOqtxT4%2FvtBYwnXvd\
  P3Ef60xjRipScQQg1TvP%2BiFsEXBTGX9zX0%2F1kfAz2YMa72lyYNq32IzIPFpB8nzlERgRjvBXN\
  yqpucecRrPjkuD5ag2iYnit7q1lok1kSZTMShprSf5ojcut6mZ1S%2BEEU71ox24%2Bel42Wl6Rkg\
  tI8GQkg0hZFQB8TTguJxopyI2l3qDTvVfnShsVKVE%2BhlQtwZkZEWJQygYhrC22q6fWMizM3Yl%2\
  BbXjEPc6EfiMeoD7w330GyLix%2Br6YS13Znpv7c%2Bqh2EK7AUsUm262QizI6nRAL1ciEOhBxyYv\
  SJPMHoEPGgwsG65BrPVSFLj5msG5zlHnDDOEpDuKAQu2fbgF6kcMLq%2BcVLbvGFnwhH0ue0pj8GQ\
  5XdGns8WOWZhYVCpUPT4ZtftDAMV82rtavwPsqDrtsl5N2GvkdmUd1dtdID8ZAGYcC8MupLaqnBwh\
  Gt%2BV4axwBH6J5wlZSce%2BpZ%2BzVwcH1dIZLAqLp7R5sweQYAAU0MKKd470GOqUBtHjuDOgFqi\
  N3JSrCQknSv1RUhlIuQlfszcjRljSNYSl0tBTf8mt3uuBTVo%2Bxp1YI%2Bq%2Fo%2FUQG%2Fujhq\
  N8%2BtiLhUptslbH32okZJ8Y1e9%2FcdkOfOwBVf%2FFIo%2BOYtR8hQctp17mr5BZWOO7AS8x%2F\
  OaNZBLolWgWgThuNmwd%2BD588h%2B1awccRUZUf2MNfrTQolXDLzfDztnadrbZCKyrlvwp1QampO\
  DUO&X-Amz-Signature=7b5a116c0bf64257e3d876f6ee198c893f7d282d35dc3d1677ce05d1a\
  0e8729d&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VL2H4I7F%2F20250221%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250221T191720Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIEXLBD6nriZ801u0MzvL7SM2MJStEl%2BWWcclGVSayUn4AiEA1BCB%2FZPtFVQH8CeHzw\
        XBaDKjV02qT%2BR5bqlcDmxE%2FkMqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDD2Ocjhwc2QXThagISrcAxg9V32PSuBurS88pC3GWPfP7J19Jm%2\
        FWZG4JZt%2Bi3EaaLVjN%2BqsUtgDNpo3JxZqK4qTyfOwa21HQBcBNmJbTgqkvRhKNTxk%2\
        FinVN1XW9IjSYjvB7Wt5nLmSznGg1SOObKC2s%2BVkxP0fvFaVDPg5Rh1bEUxQgBneoErc7\
        Or1UNrZP3y%2BhadcAZmQb2D86Wxe%2Ftu83oQUflCwcnyXzdK9VWQuR%2FCU6Lf25qXkly\
        ncsG5gtTE48EYNIB2vDu3eVoBGa6GgmARbxfQIJNpjaF5HxmtEgIWMNXySFaSWddbutMrnr\
        ltUUfTBWSnGbtKecCwPu7PuDQVW3l%2F3UHtij5SMmkanSbXWS6NfzQLZJB1yIjTGJ6kiFn\
        736Jwb%2BpM84GRHtNH5z3MhvLfheaqZRHWQzxQVnP6Rx0b4QL3bC6Wz%2F3%2FcaEW%2Bf\
        sVTEADvei1qy92VKvY6ax0Olksq%2FwsDTTo4dOO3zV1MmpUOIK%2BfnpsCJEHqJ3CQVs%2\
        BLGBhayzzStSDR8XXTeJmbzZEcLbmiBDkkXPVrn3NePLnw57KbSQ%2B8u8jLp4rQ3NWYKLF\
        5567VVwGTUR1XYiMIG4%2FWcvSx%2FJuItqckbmgiT4NWvQ6olj3LSKf%2FqGcpH8aTUIjS\
        %2BKVqAMMie470GOqUB4DB4VKkqjyrEvLDO3RvC8YE5udsLLLKWPNjc4v%2B4s6m3HsWwKq\
        TmrCCJ1HtS8GDs3M%2B6obeVOAnrtI1Y%2F%2FzUeBP4o%2BRfZt2ir4QoGGFDjP0rwUOW2\
        eloLp2m%2FufwxRN7UUeZ9RZ4DNSHL8EOAnIjFi5NmUu5JYld3c%2B0TnxuNactFc4EKsZZ\
        hWUu3pseETl7r69Vjnok4LYsNF7vtpVSxO4Wk1pL&X-Amz-Signature=b1773de633445d\
        fca2eaafff2dfd65ce517aa32e3dc51a49f00fc76de5940518&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-02-21T20:17:20.183Z"
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
UPDATE_TIME: "2025-02-21T19:18:44.264Z"
EXPIRY_TIME: "2025-02-21T20:18:38.007Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=367a0364ce2ec8d8d743406bc3566f51e74897f94c1f40d50e98bb3d2e037c14&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=dedd7df1b789d0540db847a2bdd994574fa86b94a3ff4bb645be654a5b8bb201&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=aa11c9b96037f14ac428a27865fb22dcf7e2acff03d0cf476da264d34e35bb81&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=b862e79598c68df7c2f34ec4690004a88b957992ca38513d71c9eb58c7b8365f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=be64365713860c148ad929780f446a521cae6c9c1f2cf3eba6a14f80611e4f6e&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667SSHWMMK%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191839Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICpGI2PszdQFRsNfZ3%2B9KlY2A1dsaNMnjZCdewCL%2FGkrAiEAsouOblLJWcsxVIooiTDmmtiEg3xw34sifMd6ma%2B9XSYqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIowoAF8Otob%2BxbTkCrcA1BOfQmo8ynTzWpqse%2FZaUW%2BAZEIJOfV3HKC7hr1ZiYPEQkamt67fekNraFDQiSU4sSpZzsZ3ZD0AKx%2BkcnN5QjXX2SfPUbVXspeXfg6gdfQ6TbrqUhed3rjRhNkPJE8i%2FMYS7AAVrViFNS%2B13di%2FWsQe3KQrNftOskG0lK5Rq2iAD77U%2BeqJfeOQOq%2FJa6Nf7VnWGAWrjPE37hu4EGR8anUVD5YWEp7sYszpa3Z1jdhkutVT2K6u7lrjtneMTSQr0mwu7rI%2By0VKqoALIdHbccwa4CYJb2Osouyu8MQcxJ7SkMsRfd2dkO3LqAvyn4%2FjgSCH1ndU7w50Ccmo2BCOmDdRbQ23YMjB9aZorW%2BH8ipbSAuwWRak8Bwd36WqgsQdNYm628sG2DkuVRGF6c3820T49rsbj1Nry1%2F4H7ekAGk%2BbPn%2B9DocKsC1UW9MEBQw%2BsIO%2F6cubm4jApscLh0BjGmYjMknm1xaMq7IHoMX3gabh55UdYWKFgr5owXUX02jIa8gHkivuBXzUduGBvaOerN8PSz%2BsLtxen7jKeIJBWVRYmQ%2BwwZgWeant7yz8JnkzM3P9F7HC0ys5dAeTiMx8qrcswr7RbhMianKDnrDcESNnahVMfCXOFmpNVeMJad470GOqUBq5SAB66v4laEKoxp4zGgih94vgcze%2Fg3NkpRyQSyQWdSFcZUwhWHC0bprYFZQmabEZ4vltB%2FhrLz5sxkIW3GqD45w2x3tQxzPeu2w7MCJdqvkEkwoNIQV4Lyf1ZvRMJc4B6MQy9jYTQcx6k%2B124LtYmaO2GHcEwFThjiNA9HhAsCtH3FiwSmf%2FYiuyWlBFgCLqqqDY4Gzb7%2BYpVs5jcPTey22CoX&X-Amz-Signature=d0810cdf19cf59523c4fe4d114395c921c4b6c56b9683f40d231ff1c67dc7d1f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UDXJAM2L%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191840Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH1MoMkzAslIaOlJH%2BmOKBdsSE9qEnKKOO3jUjUUaHQ%2FAiAz0qthgyy9J2LQ%2FOE2ih6rEJT7QikTycArRVmHe%2BVPIiqIBAjc%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMljrCiWsbQipYnJFGKtwDCmnljS%2FlE%2FnXV33U7Ia2jJhGcEunTONODVByLQitP2e59YmkbnCSFx6KJGfmSY9%2FLO0xladEEBcbvV0gZ%2FUf%2FNZYWMxztnfrqGYZraLuneEAJSw8cBwkgKPjfZGPfPFn%2Fq9rFxz0fZPL4Nf0smqkhR0we4jLWWdQCMqmf59R1Uy9l4jxdlCggbKrW%2FwTXXJKK2oIQnUtCJf%2F49fI9R4PUsJ0Am2FvH056tbScx0tJfiMAdy73hevHYtK%2BD4MeLX5WEmW%2F7z8GFInOgGUMmiUVqDLh8wseLBy8SSEdhKyKTkXrM2zOKL6fIAnXIuTkPZ%2FGBlU0U1NLKVy26SL61DXLosmWoKEU3ThSHMI5fgoocvSEcdZcsk%2FaoIRpKMUX5%2BNwIEqBGtC%2FcJBwthOrjiOzZsouFs3B53hRNYsV57mhIS8avyLrFc%2FJO%2FhF8XJLbEFRlam6ucDNSC5DeVsQ1dBPxPRJayqvlG1buqIr9mRFYucfgB%2FWdWyx2m3OL54jWvHNKWdMD2S7vcoi0v%2Fp%2B90t%2FEGt5VsAXp%2BniXxEHFpkYlZBqlJO%2BNR1ZxOy2pf%2FkkYhaGKQ4c9NnGqFaLmDSryI4bbia6QjQ%2FHyc9JrUa1yAqQNAM5fm51WOV01xMwmZ7jvQY6pgGikgUX0graG9FSavPjRquDkNqaugfDPq5432V%2FQIZEF4RvHIKQgWNGxvtP1P7uJNekZLMD%2BoUoEvDo6QJlJRSSSc8FSdSFwhe3xe24J31Lou%2B4eA2qljpA3E0QW%2FyZNBx2oVc64GZEiVW9A%2BZAdxPy1w9%2B%2FQ7PYLARJ4EJbhAR9U2CdUkDE%2FAhXnz6Hy1Vi5LwDWPEE%2BxuDsfADb2ao%2BBJY7rHXSuV&X-Amz-Signature=f6cea3dc5353a267752ce401cfd05e59541fca0cb0a8b72640c2d70ced2aa613&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=5d73b25702364d8bb11dd5af3a1d01e5f402e0b3742cdd87d2ad7414c15102e0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=e6f22b1f1c5c25c85e42858bc15dcae6d41d08d6ea1efc3c653e3870968cd1ac&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RWM4ULP2%2F20250221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250221T191838Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFx6fjY6xr4Z7cLKU8nAcFu3zcsyufAM8d8yCA%2FWkMfJAiEAs%2BpNli4R%2BURwbWvXPHcpD%2Fx8OIUBeuIhhopjEIUSaNIqiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPIGfhMASMKPuZed%2FyrcAx3LyKDzGsbngYbZj%2B1Ll%2F95yjr%2FC10%2FOdZ3C%2Bql326bkr9EOAwdF0dt%2Bd6xEh7ELlECnCFIosBQYadII4dpoiMyiV16V%2BNc3Uh%2B9bKkm1at78jYFnn4JlFbdLyc%2B%2Ff1gxlutYTzE4jtnasZ4o%2BI9dMCRR4mxan727CHQeUEcAlhjePQhGN8nM7qtt%2BDnJH2fUbHbMdJIAZZPbE937yRzMIkrHKdQlKfLqRnWFuJw1%2B1qi3O7zuV%2FHTmNl%2BqypvtaL002LlTWtliHuXVtkHGoweTl5N176%2FHQX7m%2FssI%2FsVjW9Cu5r%2FxnD0hn0cDC84em07HtZGUafqbkVbffmRBeCSZhWk2hoCh6kxLSxkVjIM50%2BZ7P%2FStHFobOFetP42V99AeFuNTPXvMbGotEnVFswZ93cp7sGxPCkI7t%2B8NxwOZBGkXNP7QjfIwoVxLuWVKBj8uyO7fOOda20E5csR%2By%2Bz289pJ%2BAknk3KtE7d%2FcMsiNT5lKqWgtEPjU2GynZ%2Bt%2FNjfP3LNTT8Fji3e5O2%2B4%2BFfONbjdKzk4AecfVWVbyoparwY6Zt2zCvgWzLKDD5EgM1LiT%2FGoF5sYnwzcH7gufVfTd%2Fimww6oc82VCDInQUD1Sk6Y5uj4h9%2Bpq6GMMSe470GOqUBseGCpdG7ocWM%2B4LTNGR0OTxCvjrcDDRRo%2BYCUPnmP0DK%2BOg%2BNklqXkxcr9DomKuHyRgdQoiyiB3Y%2BnHPnaKV2SSujRiC7%2B2HCIjzwAOJljlcocLVRDNITMoqGwEQNJxrdh%2F9v%2FUjQHS4DK97ABCjB3j7odxtsYK1SLteqEbyjh3JrW%2BUlYswX6rFZOHfdi1ngK3T54ZoWK3Sush9exJL6fSMTwLD&X-Amz-Signature=9eb9d259cd4b698c2680f8d8cecc66552af3861a8dcf5090631b71ee0b199d88&X-Amz-SignedHeaders=host&x-id=GetObject)


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

