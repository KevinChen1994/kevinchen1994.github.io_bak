---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466X7V3NARD%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T102430Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDj6VM8VfPIpwiN2F3\
  5Z1fqNf41%2FnNggR0qBNrAO9ECswIgCD%2B4HGDIN72kGtcJ%2BN3V0bmH9QqRfto0ZI5BVFHkLX\
  oqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCLEFCu0tkBKe\
  %2BQyoircA%2FWW3JWGaSTdr7C21Fre9Ccks555s0KfOaZq%2BQJAcEEMXD22HANm8EaEnsSRe33v\
  ESTxozmdbZbUieAcCdXAxOMFgS%2BvIX9yHuHZlNHD41ZLh%2BxHCJObubIMVhBHcp2Lwv847Qvb0\
  1ZgkvspQAGzcmXOJE7WrflYIz9vUCRA4vs4pVrM8unPVi2ed5YFAUwzLe55qdl41%2BIdFsrsWbnn\
  kde8Pu3KFPJ1zp6aB6Bl4aSznaGzJWJzOVkeQI4FyTg9UIQyA6jbatQmRRVGyE7SJxvgSTFjuV168\
  0CuQjFpgjKRoCLpeuMYc2At5InIecHfe2ZYzitmkmY38WaXgDEmES0QjCJirqu3Ka6bKdV9%2BhyM\
  sv4wuBHK5gW%2Fg6tGLKN5Un146eKrjFJpFLcMUMQZLe%2FRy9KPWUOSPQ90%2F7CMCSurRjPtiz7\
  gzM%2FrEx31nF%2BpaxH8%2B5HCfdAhfzhy1JL23R6JGRoc7Sz2%2Fa5Sv4WsHc1K7t0nzoxlfI7a\
  qlET%2B1P2X%2FumSh7JHoWLc%2FJrSsJKtfux8DPBJhjgk5ZG%2FC%2F4op0X1vxIA8Y6f%2FmuB\
  MCCY9Z4%2FMMFoaln2au94YagGX7ddHWQJvRYz1H4oVyb3%2BJDa5VvADaCUyGj2YRYJFpHMJnZ6r\
  0GOqUB6iDLNJEHrfvgPId8E%2BfkRJui5BsU2GadtJYiXQTYNkMrtGXQVFDh6ZcsNo71jAAlkG6Rg\
  f5FQv55NC9%2FeOVwbfb3798bT50cvliNcl4UKFRXsRzs17HBBYJk4tmTTJEoUERpmX0p4zzPZ56%\
  2F%2BdL6zC%2FOMSUibR%2BnFV%2BQRy3ztuEVZJpJOtVq8tPhDj9IGXcOjLUi5N3FexnoSYbshFi\
  wzJeKCK3B&X-Amz-Signature=0f70b5f8ba24d7f502ad21ef11457821e984a62bfdffb3e1161\
  5152d00673ec5&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QLUB7UGL%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T102305Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCLOztdQCoVShSeJ2H764wO3N8d0USGaxzLy5YJk58VEgIgcfi1f49wp1EtrKWL5GA8vU\
        %2FFRYykVEFXn6NF4cRgGMAq%2FwMIEhAAGgw2Mzc0MjMxODM4MDUiDOaJmF9GmdrvlbPR0\
        CrcAxb3ryj8aREUa37B8%2BS%2BNEfJ705Koz71QlvnRV3UbwX2%2F8OjDM0pnvbDE%2Fu4\
        IZ9W5YobrQ4r6vNl56YX7cbscuJ0gdp%2FyqSGOrpP%2FxbiKtTEe7Ep%2FSFksLp23fMxu\
        ZWEO2sVR5bgdDVNASL%2F2KAbou2jjD8ysDllsc5L6NGzkKGHxFqVFR3RQDhQF5Myv2N0D3\
        IpHpE46kJAVR8wGtkQLpjdmJu72kfnCpHqe69YfOluTMQWTgGSLCjiFjJGKDWLhKlORwHRS\
        mPVjM18XY1JxLimTjYUqiHNd7iPPKMdVb58J9HjubKAwAQNIEw2q2PWgndofw7FshGDA2Ba\
        b7GOgsmo1yKM1OLllKZs4eSDx95dCxQbu5mFQ5tE8EXhTFc%2Fh21w6x0GUAjKPK3gC3QAB\
        8U0Xb5036fUogvaOXh%2FPqZDEF5iW15wCmYTnioVAHuwGEIBhS0nCXpCf4pTiMvSt61qoM\
        Tv142FWkE6IUhEWbG%2FYt0aThErDTmeB8hqAHcsbXex8RLimpKvhwq%2FsCvZM13zlU9XY\
        KdiqpZjlcnx6b0iSgCkm5UQwM75hgXr2ToRySxOQ%2Bis5323pFKQMZUB2etgA0ZpRdnfhB\
        nUYA11JsT%2FKOkxpqH3j%2Bn%2BbOIRMMfA670GOqUBew7nlj2ivvS%2BwWNphZi91G%2F\
        7hvWMgCc6T19eI8xcKtMPUc%2BkoX6FfvfyixMwiSWrpZRUXU6Wczzq7AWV0ksNoiFv3JSZ\
        AjoRy7FCy48BQ389PeDdBEWTMgikYue87isYMwoJcMwNty%2F%2Bt5EGY4jgw8Janu4JGqk\
        CSSX1lkvYWNIkPdh5OOeJWoRKGg6Dhyyfsy1jDPd8cduKVvENGIt9XPPLeWO9&X-Amz-Sig\
        nature=a32d440e426d2421cf2ac8967aab35a025379e8b376ee8ca6b33c85c2119022e\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T11:23:05.668Z"
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
UPDATE_TIME: "2025-02-23T10:24:35.801Z"
EXPIRY_TIME: "2025-02-23T11:24:23.069Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=b53dec3f8c9b382ade7a664d72fba596166acd65fb2e638dda2ddb30934107c2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=81a191a7feaa3cfc848fd5595907f35fc0fe60e5806bc5d8847d787cda79134d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=b934eebe939e1376ecbf526b409a790bcba5702be9597568eed165b8a73edae7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=837a2fa38e1aa6c64b940cef0a228d1496a36184baa85cde7bfc6393086cf31c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=f1869e177e139c41d498e4b09cc52f3ae334425505e9cb7f6e2ca8b4d2a004cb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WL2KVFNW%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102425Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCDztKU3VAY5bIm60nly6bNzpnoqqdvK4wZIWOzv5gj0AIhAOnsMAigtF2VM1BzZe7TBILFnCAzoOCOjuASBrieRkpTKv8DCBMQABoMNjM3NDIzMTgzODA1Igy2gPvj0Yf87qGg3d0q3AODS4zc%2FV%2BgOIhOR5g1ELAwnYL6fUQ6ya%2FjfpI62r7OuKv5CDNL%2BaMz08fxNtGOQqcJQ8cSHIGn5DuiF681gsfQLznYCqIpfMGxhwCqnYyTU3zBZTzRciP917sTDiq0e7xbkfaMaPazTtOB%2FacsHy0YrVpDWqrJ0PXWhYJHQXmxFANHKRNSntCYfQ2YdYBgR0xyqEOclr6jvn5CF8enV5RRyqZYxQdqupnl3h6EgwJNcOuwhMUbRzGLT%2F9t34nMtxuktdsJjNA1rPibPVoc5NHnm7cWo8fZRb5a7Kam4JPDkVmwJ14fovD1cVZWOGupc2g368U40TJxT%2BnBi5V42Yy9sUUBSqxigtObwDAqQvyaY%2FuHMhh0rpAVjVBM6RPkk2ZQQ%2BbGgcAgGA5qRRCEF12xgFyrXOnmIEwlMvCIwJqfNSdjrgZ%2B1CRhcd5A0ogvBe560EcnfHhFa%2Fxzk9stqzMxwn2TGCS9hYVQ6ApPbs7j8NX39DOJYkkQbz8NN3EPQxBPQrduR5rlYphF7nAwxyC5rSE57GwxGAcbXgbo8z9j5XaAUhTtf8Zh%2FytfutO%2BYscarX86Vea0ln%2BBLuTG0Z0pKxrMing5IRnpCJ81sPoqWT6nb9E14nRn2R45JDCP7Ou9BjqkAbn7rKDqBu0FQtMH0JNIS6AMpxerDvVi0xnT1FCdlsfg9OKLwGLw8nlmQZgAWCgOqSVbQFrFEOYJmjQDdyc5GPy4Yimt2xlbtqsF1AwvhuPkdfFU7e02GJpE4ltEq%2FaK16SQhdub8Q2JXGPaLpz64W1OVdE%2F9XUe35%2BW%2Bqj0DbJQC2y2gz1vBvv%2FilrC6tqRgmxoibXqIBdp4RUQ2voiYYIpGDLr&X-Amz-Signature=2dc2451126de9e3e62c15e17bc08fa905c2b985c24e01b2378a4056d16a05e93&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SM5BTP5I%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102429Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5WHtAKukb%2F7BnwsUaCb4liGvj1mcdjFHsu4%2FNfMoevAIhAJjMnRzzxuNfsMRqY%2Bl578zXqHqpYUrmZNYYanbRpJmIKogECP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwpNN8h%2BApYcFqKIKUq3AMg%2BZ9lEdwfjUIUvpRCsSj7vJXx3Xcugiev0TpU7UrUNIHEySXFmReYXkYJLsVscHERq1nF5Azks1800suIHO%2BNBSSU5XN7YCUG8wR%2BeDe5yT2NKpMeas8BRmfdQisr7W8VCv0ynbdizOA%2B61%2FPE7i5DVC1jB6x%2FCXyL%2BbQmagcUfWdGr%2B8kfmWLROBsNNdzVPuBakK%2F5btLTql0XUW%2BXBdRzyb7BW%2FCwT2jCP6O%2BRAb45oGUrgTk0j%2F%2FEDf3Wtyt0Kqs28f6yKbHLBo7bCgY6LTQxJkVNT9qSPAw3N6kRkDgH5p%2Bgo%2B3kch0vJ5VxoaKBxyPhvTgs3a8W8OxyFjK%2BJn9zx%2F4eTlkFLn6X9QYEi3Y%2FKmsXR3xJMq0icmosLqyC08am%2FkGu55m55HCbpu08EncUYP9uy13vgKYGuygmlZ9TeTOIpziYp%2BXPYvaX38W3PTWjrfo2w%2BDtF5CTlnLEFMxstxHK45HvgdaxkbD469MeWjF0XHF59rNJ4%2B8kZspkOcBREEWjSGWAtI7p0PfU2JQSjLAos9xu65ujYLaby6LPAQnbeCbfDGmLCy4WaTJojaPoOBkwg0QiJjLozj75hDOB9pot9vG5jATI%2BH%2Fvx2TnDu%2Fh8IK2j2TT8BzCp0eq9BjqkAV%2BEVjXCKqfdf3YpV9lgJWryTXWzB6wg89WS744x%2FDow7YR7K6qstwAOQlNAK4NHLvgZKAtfvix%2FbVc%2B0EHE7YThj59obcTLjyo4aMrEHCO22MIunMC45Mtc%2F0cPLPKC0pCwE81hz0hKN0FcAmv4477bMmafNFrQES77EvsUI5jbO3t6cD7JamKb8p%2F1%2BJBKlmG7WYCb2GWcXCGpPDeS4iUfblF9&X-Amz-Signature=f0ab92133efe2d632b931d7868cbf18d32b753a76eb14836b2f66645248c8577&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=f8d7487f5500360f9f065f99e7c023e273447fe2e438d7762c833da3bf0159d8&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=4bfc74add9f44bbb30f75704471206398afabb69071a146f7d6e10f9e5d03254&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UY6QUEAF%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T102423Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDjDieyi9QVAw3fkPt8f%2FWs2sMTu4rvlmPMebVxqyJVnQIgEzZpcjyA%2FtbFouLbssp5PEt1IddSNQyvMbxaezuOItMqiAQI%2Fv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDHvpjhxoFZidnxdHqircA8kKvhpinN%2BTG%2FHfT9O8RaX1ACwEyDilj03DLxgp5w1QA%2FhkiV2qEC8ipJwUTGm0LH%2FSTQ5hI4IDuqD54PCfimyzmRMIP2tPdc7YMqWkmBy7gs2EtRehftw8YUYt1jCYCYmWXWnpElw%2BFj7Kjn9GnYNefTaHjznL5SZjmUDTnBEEQ1K38eXFCAMWeTnCu43OXBauEV2269381dLpWW9m7rtrYWIV06ZIQBMTeLzZYiepqW178kVHe%2FfjjQF%2Fxr3%2FmnPovK4EsN14pcCEvyNEyoTCI8il9bdieeFVVe%2BC0nHpclOO0Z3V3bgdaPywScC4AlW8LfNRYeag%2FZCyJqNvYdDrJoqDtzz%2BNU5XiRPj6lqOyqiK4MisbnCxwe7ki9DC8PScmNbs0OM5dq4s26AUXhUbHgApq1zbTd4if2dF8HRIWDbgjM8Jx8w4fyuHRMW%2Fgt%2FH%2BR00iafeSeSXMXVrRrno2ttd%2FIZ5sOGf6mVQQTIFbAq2vvdj5uGHWPIzUL7e6t8zG8a9Tr1AuFVd7mN5lQVsWdC8aAhxyQYnZ9nzNJoUWrX9CP6tU6aEN7d1SDhEYF%2BQ8%2B%2F8BL0zM6Fvd86CQ5uLYMOX5jIob5kI6l%2BUeAV2fqGsJD%2FZggzT%2BhUzMLXY6r0GOqUB44qTlWQ7FNU%2BfTe2seg8AQuxj4lF2Cp1GZ%2BtriHWkkxUpc%2BfmSE5MpA%2BM2LYGEPnDa6Q3Ul1d9LaGwcshgmWBXnnECCfLmhGEQh9sxPW%2B1rajUVkhVFGC2dx0ZPl%2B0j3L2XbyNZisFhhU8FbaNd2b%2Fv2O7JrgdO2K960RtBJN6OFt88QgLwjp2f46zZJUCwdtCfZjy3Auun66%2BN582JZ%2BhUrG5Ac&X-Amz-Signature=0d1e36af022c51135916db4d9ffccc34ed2d651a665a94adbf247f7a571960b5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

