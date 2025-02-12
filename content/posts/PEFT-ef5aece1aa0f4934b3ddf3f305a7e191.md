---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UUVTJEL6%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250212T232150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpz%2BBs3PdanTp\
  38OOW8OowJGn6ZRNhCrmdMDZyxxmdcAIhAMbz8j49keb5o65Qv3wz9TLQQD2hT8wz1m1ZBUylWXkA\
  KogECPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgztH9tQahKpe4yes\
  pIq3AOI1NURiOXqiE7N%2F%2FKbobVtyz2U5eEJ2og%2FWSBv2znLMc0ZOUnzx0ZX0Yk5RBZNvfyl\
  AhyIXP1rs7zJozb%2Fac%2B0ysxMkl66JUF0lthh3wjgifqdQDDLMoQBrajk8NDyi3zIPgMjAmS%2\
  BMmn%2F2%2F1zZmSMzV4d2FULKMvcUbmENhi%2FoQZFhX9tJLdsIaBUvmGSQfVSrWaAeedvXNNhz%\
  2BNeOVF%2F7wgYHsn0k%2FiAFm26%2FDvboH93hNWZkX6H3avbAk7ae8qNY6KPmFPPwf7G8L4dFli\
  OsLpZ3wCE%2FZpvikB4fb5MZ01nBhDjCsR%2FqslFqtkCbmSfGsL1BAdcdayxUYRXOLAwWLzkZXfx\
  8%2F3SrH608VYbSgzcHBFrXUkulrT1%2FXXgCfPrsi3HqUF0IaPaFBuawodWqOXvwf49%2FZswuiC\
  b7saZm9Kb7C%2BKTpEJ6MJUwW62zZvDqdW168k86d0zu4kmGNAuTb86%2FJgeRJUvFpgo73QuKWNK\
  L1oIV9OJjtHpUIq3Go8fr%2Bmf8OgDRb7aQxubWg8yH7K%2FpwwKDXvt2%2FF1FbS5gW12rAr3R0I\
  Zhr2hnSPwr95JUEtmRXejS3pRwBG1h3nCFjVjq2HHbY7D6Fhajc0FjH8PWCjret3yxdGy3TCdxrS9\
  BjqkAdU%2FmuzI2ZmFvF4sO7tqfUQ%2FJZ3%2FVFOvFqMYB2889yhG4APypt%2FDPd%2FMX0lD3VF\
  wS2fAdVUmOM0xHif4PN7vidYAEn90p2B53A0hGr6%2Fj3bhR9spPPtTsnfJnHSli%2F6NKmhHx32x\
  KWq9lgwtbaY7XiUMqE9x%2F%2Fs8y8j%2FBK%2Bm6dprAeWqGJsstsCowZB7fXpai76fYzMHn3DeI\
  qhBq02Gq6DQxIpL&X-Amz-Signature=a3b900ebfc634ddc9266f6fbdee1c4fabbe1918e40965\
  920206b4016ca41d7fc&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466SNNMAOAB%2F20250212%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250212T232012Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHM\
        EUCIQCWFOtZHv1wAaP1%2BBnoIxo9HXEJWkgwMXKme7qCLERanQIgKIa6QAv7FHZbi4AXGr\
        tH%2BL5vf09Oq1UnlN2O4oy5yKYqiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAG\
        gw2Mzc0MjMxODM4MDUiDMC%2ByKu8aeXFsAfaLircA%2Fv%2FQRUzfcTccg8AtmSsES0X8G\
        sIm3f4PwQkpxm3xysCQc9E%2B5R9h%2FBBK5J7daIRqYkdwSk1dpeDCEnyx%2BzVxzprVyV\
        RHDUygRd8Kov%2Fop%2BPFxxJNll%2BAiBit3duJzoh4FbQUL6mjKxCV26Wl2PzbAEecbeo\
        IfHBp6xg7OBcc8hxCrsLZP3XjHrFQ3cwdM527aMDr84vutQM7shw8EHykIzBZZ4xvPxk%2F\
        35MBQuW4Oe5Iw6QzrES2anOybcjvGg4nhISuwKT7wiKnZQlPwozNYaMQ80bOezEKe6DQ0QN\
        F%2BzgGwwufR5Q1lAEeSKILkQcCOKgyq2jia6AZK73DKmyMMlJu7Bt7f%2FxO3IOknBnmA4\
        zTLroBIdbmMEMzSMNbKVtMSGjW%2B9fYWw2dlJo56yhUBRzk5eyLbAdd1l381vBSU3PDS8M\
        dRfsdTSeAukHKVAOzcc%2Bk%2FfiyiTEfDisSmfgCmD7%2BoqhzCccbamxcUHjsLBnEGfRf\
        OdmUS5IGkDSoogZ%2ByB4bLGLgDPMSxge149MSKTL4DymSLLjrccw8IUbLqR4ot9nhpSDS0\
        %2Fm7G7aa2wUB43aWGqalDO%2BK9ShuqmKeRyhgtqRiMMza6Vxt1MD3%2FjDwCAA3fEEWhX\
        QX%2F8LMIjFtL0GOqUBUATEzc5zg7Y55bPtbM5Ar%2Fnlv3v0l9fJkMRhbJZNn39Ul3KqH2\
        %2FNoe7h9i7hJZTcJxa5g9AjnC70BreOYf8maRP0F14sDX2FN6nNrIBKJ6oxJVcP3jnm1cN\
        %2F4qfIyU4z%2FNrhFAHU7Mjv9k47wRU2dsCwyD9u%2FsP43P%2F%2BZ4WfyuK%2FrE0PoQ\
        rT0rsKHTJhsxgo2ywbJd0UxPbfI9cTmbnO9%2FXpL2vT&X-Amz-Signature=d6cb88820b\
        1c5b7074094235e59ec154bcbcc5b53a1741cc28f92775e386b7ca&X-Amz-SignedHead\
        ers=host&x-id=GetObject"
      expiry_time: "2025-02-13T00:20:12.694Z"
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
UPDATE_TIME: "2025-02-12T23:21:58.560Z"
EXPIRY_TIME: "2025-02-13T00:21:41.131Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=1276d1044c4c008dad0d1cedb60226d3b3329411d38619c182c553124e274b8d&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=bd9500bc27636499cdd3ddece198c398830822adfa36dca7f845e1bef75a8f23&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=f95afd87cf695073f4e4a653119237ae2380a40b4e777ed5860ed2c7669aab01&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=c446ebd7820c2e86a7d7fb99fdcc9d52010d7ef2f778183f32079d013403b0f1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=67f9cf50a9b6cc9875c2411af93117a0fbbc8172a15ab0de43b6dc8f78cccbe4&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666JIPN3M7%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232144Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC1700mOvg7rO4%2Fz%2BNM9xbrG5kIP6FB79GvVFy%2BiF%2B%2B0QIhAMEbkYf1FSeLpQCz6UZhKm4yh9%2F%2FA6pJmrTHvzjkXrUEKogECPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgyW3EC%2BPOURva77NYUq3AMQkAcdJ%2FDi%2BsYOMwV5iOE1TMgZuWs9H2LM%2Fr0iMBn1D50J9GK5DQpcEJGkMenKyG3NbsE%2B%2BM94X%2BaBqp7i%2FIjvF%2FffPKio2QugB4zon3qQFNfIORt0YTcvS2JE7XHEZX%2FMWKv2mAJEOmGxNKgx7c5VwaUt9g2TbVCRu%2FnViyx1leypB%2BXwY9Qk7w4SBIxWYSgEhuNnbMXmQAjnCe3Pr%2BJxM5P%2BcZy5jlBAxf1%2FkfvLBnSo1zTXoN1n8lhS0G9HLY1177GcKkq034cD3azc8vXl6FKvFuHe8NZaBtoXXGIsMF4n0MUuAhIQQ6T3I7mg31GB7Jvgnrk8S%2ByuAGBCEtj8rFaS6C4A0mCDQzoHpvPYKF1zE3cS0TscoooOKlUpaLGpEOVazhLikh%2BTk7UkL6hyl9Lbs5eNZ5oHvzAl9ekRJWMlhZu8ozsiz4pJm2%2B0WKC9RClnJKw%2F1VxnKcLDoEi7KyplXupMq82AGAgPXrXSGbQKnDUy8ef2hWAmEX%2F3oMwGZru%2BSUJyHxIXYP5vgVVrLfQdLQKIeyG8wm8SbiWAzSCXwKTQaard5XDaOJQdXCUKpo0DqHIdgFew7JhDFVyK8cmBRSc9RS6K58WJqxsr%2BhrJiEbGW7pJ5YXSkjD8xbS9BjqkAf8TPVO%2FtLh%2B5CiB4ZxawmBVhhFY0ozSpZLXUhCr6hnLEsDYapGBiWDyaN9P41aOZwsxss1RHv1292Dflm9d%2F%2BFwzn59R5cdLL2zSgZDduRGpwRyFM9g0CAdTWk8xpgc6zOLKDUOI8ikiKcJIR7Qkt0wP6%2FXZbJvbYAHWgwQYCp9EAwgTEWpgadkSAmpqojdFVpgnENLHo5cVb%2FlfnLyOulGwZrq&X-Amz-Signature=9c914f22ceeb838e019d9fedf4d06da33856357986ef72b4c9962091f2a5e485&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VGDHPNU6%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232150Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCS6Vzh8k0GbimS29ndtlrzPNm5HwtFKarg%2BEnQ%2FWva7wIgOeYb%2BHhm%2BridUKUoInUpa91bgwgNB1WVvMb3lv1uDR4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMOIpeeR1OrcG2MQ5SrcA1vsyOI4o6shmWRn6H0AbUu1Wa6SvxOYzVaMuZ%2FfIlYoMl3eKvprkanZvt8p2aqCkKIcYXSygpvHCb9FnRlyjtBi3gsMvUlB%2BIheUsp0j2n0aSfilx8u97a3mif8WvhJWsNX5XZY6yr9rl%2FxrFNup%2FF%2BkjW5UO1SU4B2N4sfMEMhEQda%2FrmcpCxkedrkytkKoq9AnyFlevYnviVOOeVRF3GFE6y4PJQ6p0Z80janpiPQgVvPbWGilaEDnX4Fe5myD3XbRjO8s8A5DIsp1iaTe6xsLNsaZitWsS3uhFRyi%2BoGGWA%2FJB1elzv%2FSIE%2BmV1AscMqO1AesQrCAXzyCIND1sQTcDbdevukziMZcS7HvGl9%2B%2FDY52PATUsEFBDXskXhTeg0JeFcgnTcNPw%2FcnFXT1DWMHRbUyKCnbSV9kmuOOvcF%2F7Rn9CZ%2BV%2BaqSoEQgYfkuiZYWKwLEsCWzDauICYXZ6T1o%2FKtQhIy9TaLz%2FnhYbnGu8P6cx4B2w2K6XJSIwoFzmuhuoNs%2FtKOQO8zbzNOPyOz%2BOGzA9ZOYZvXWCn05bx%2BVvemaNjytR5nz9FfJwvKeLGAGBgK7fbZI722f5KPr6xgcKh4u8DBsslA9xDKNebj0KbBixsgTOKfezqMIDGtL0GOqUB3QuhPvKZg3WAiEbgOKThIXLuCoiMtBBMSNKfW6Q2%2Fs%2Bc5uG5vBmIAtdgWWZ0tKEzhamQ8mytOv1WCDDPF8AViKsZaqgUG0x%2BjALV7XhoevVoyyRZ4LSbx9etyUs7C7Fye5J%2FvSMl6DpFHResK3%2BAU1KSlIEJ9imfvxKyToDILtMQE3%2F0UJWyoJwsB4fvwAvOvyYng3LZ9bE87sNn4sx01%2Bu%2FcwDg&X-Amz-Signature=9fc9c540d368c7fd9c7ae0d604d6112e10e9ae32fdb0d187f4300a2fbc5fb6a5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=b0d45e6b4ce7d0ee9733790ef143f7db3144a4431cc2219b32c295a70215219f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=fd4aed5ee1be6ed159471b135b50a9e8dec885cacb642d2ff3758c2559141f41&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46672GOGNVD%2F20250212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250212T232141Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAunvvEq6reVyTHPEUc5JnJhtRy14NEE3xkuxOy5DTKvAiEAneSB9BmOE7L6IAL6LrJA%2FY5xChvqcUHhUkdA9JYQXy4qiAQI%2BP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOcOQdBbavzXyR4tJircA42qWmyD0CfHrPd54Z3Zgs5iigj8kWyLNWJ%2BReUGk1KalT0F3K1DeGaV7YHymm5iHV4IWsxidCRG5TzFRq6jzhJc89evUgZwVGpr36ypnw6CUgZIgP%2Fc9Kpxd4Gmw7W5a91%2FR5HIGNPXBfYyFSWrjSy5j0z6iXpaqqj8AFyL5Q4iTOdTuNNOUmCQ40jDmyPO89H8yF4BWz411JntBt%2FnCtwOUzZxZfCd5UGwmbLkiXN7y1X9BHke%2FnNc9TtzmX%2FuO%2B839DiWjhfPtRwIYo68jSDbLmqj7nf61X6QhVQcj1bF2YBB3mzUevIleV%2B8tk9tQ8bpAiMB4NRzan%2BBXDUxpuIbwkPVxCZHsYRxCEFdv484zonb2zmWJtSVZRslrdcXroKtKw8sxHzGYX9wPJR22h3CdjWxRKPtbsme0WF22yNXGnNMdBnFFk2dXT06zwuHmpqA0Tu18g9oSj9YjKFJPKv0KmyHNO%2FhBcbqY3lD%2BQd1zhuCFbD7QVYEZRSJTnq2JFt%2B6pxyou9eA95iFs9bZfb%2FHpk4YCFRIx5wHt6Abx9euOq5hIEPXpCrNjSm9qSNw4866OOSytRkrOPrxKBNog4oh089IERX5gqubQ1LdKbX3YR1%2FUzMa9bx5N%2B%2FMPvFtL0GOqUBzvjlLmLi2O86LcghTFN4Y92c0bjy7I9eAiCTVL8Xm%2BnjHPgZFX5vrMfQxEnkyX6SilBZsrADdEeUCGubb%2BJjRqGvA0eyKxY1LB2mm08HSdE8tWe6swDmYpYTWy%2FY6zcMSyvNPG%2BAKoSuxKLxTbXZmDup8hABpoK9IMdMgYKkfv90rxlk2V%2B2g3UBO9yRBokpGreteFISU6eaixlK8VOMAl%2BGVGOr&X-Amz-Signature=e85197ae6cd9f0975b18759ac41a3aae706a5dd5a4bef6e1b536b2891df44b4f&X-Amz-SignedHeaders=host&x-id=GetObject)


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

