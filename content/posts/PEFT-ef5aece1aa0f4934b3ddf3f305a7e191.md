---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VAN2NB7O%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T063303Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIBs%2ByUyeHsDMtLVBu\
  blzsomRxI1P6DCvfcznzyUSKm%2FkAiEAgNoYdbx6tcmqLVecwfKijlfLwGTjrrEZtNaIZTmWTecq\
  iAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGTs84I17l%2F9j\
  dsXyyrcA5dbRuaiGePjwZY8baLMxBeJ6ks9cBlhnAiZGTSDFYRnJy4xW2uSS5a9A7ZzTutJMgPHp1\
  MS%2BB92HVuyZjFzLN9GYAoikldX5PxjAnwBny0Z5Ok5e7ZtKJ9ArUkZQTT7EFRO5DiU88xgPZ6J6\
  VmSMrStfc0DPQCTCmQ4zFj0Gh42TY%2FmEOsHQOiDZORvB1AVtuW%2FtO75i0UTSpkgCfhrc6qqI3\
  eGj4WkdWjvC%2FhK9jS4lgjo6An1%2F9AOpb9PmOXS5sCTxSVlA5a05tGUWF%2FwSXA2cGDGo0sye\
  IuGpLZVYpTe%2FUCegmAowK4P6h2wxwXu6GfH5o0nj7v37cTsMMjbth%2FW8zifZS%2B4BLaQ8XB5\
  aK25WXx7LWEFQRPGwX8f7upblqHLsNEU4C%2BaeLerP2MqnUHiqy%2BzC1s9uuOBFo7NNNw8dAeW%\
  2BrmtxGw2uPcpKG5ZNFWhsp7pOMyTgfyzKLZbhzp3HkACOSEGi0aY4Mj1WPXwCHyDhoTQMryP6xax\
  fs%2FEOKcCpiEdDcKASQnK6ysJqQAXRZUAzVfVJPFx7VhAoGuW2ha00a6L8gf81iDr7yVyKp8a5T0\
  zqs2eb4d0lDc8O66NDD1Tka5DuWrdiUrN5uraauQyL%2BFKsl8lzJ7CMLrH5b0GOqUBtGeB9NfRsr\
  atzrtC9PTbAKLImMBwuRBkGnB3r52V%2FxXFU9UvyXIWb8%2BJDMGMXARebuvq%2FpB203EKlKx1c\
  A12Szp1zvrltDTau%2FTJMHdmjGmOloXpYbnVvjqhk2Iqe%2FWaJPv7wV329rlmXvdOzQTOrCp6Ai\
  1MmeVvHGFDOXEISnk3FOC3gmQ7B1EvBqBVAXFfvA%2BG0%2FWRKd%2FggGf1LyznGXcA%2BN4W&X-\
  Amz-Signature=4c168f10a7ad47177010efb609167a6921971a4beb6cd3e1d4d1c484ee498d0\
  c&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466T2H5L2SC%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T063133Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCBQ9ldT4Qbj20wtfuTGY6mO1w4faDRCOnP9uMixgraQAIhAO6EccIzlfuHZfPMoFIGao\
        OgvjdTanwfVbH%2BTcax7cFtKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1Igzf0NnCMZp52FqYF4gq3AMGllng3nsrsUjpchkX8tbqzAA2%2FPaNQcGc\
        ZKPMQdASVVI0dvkWNDoRl8a509Bh3vkzTOaQYE2GbB1%2BOKz18%2Flds3sWJI0AovKxYuI\
        DDlJhCB65BrBYwtQ65GVGWn78ZAvb2cFYOQSFxrts1UDHWO6HWgO17%2FhJuwhMMf9F%2FY\
        EQKhq6Aoau65sVtDiQmf4R3euBB5qePGMZW9U8d3Kwbl7mIZVq0yuhkPX5IKS7e7eKXHEkk\
        ZkAAILl5rDf2gm3AtZW659yFfMY8vgQnCB6g2xNOKW%2FwjpMD%2F%2FAOgfqnwgoSuXPCK\
        xvX1D2eDfFhAGzpCf7W38QjVn4WAb2a4LOv7D5i6Spz9zIi74qO21mHc0BSbsZoemHb%2F1\
        n%2FpmtTUmRe6%2F%2FONVDj4BcGkiMEdCqwvU%2BVN7XbOFao70FjzwHKyYfMXk2VYaqfQ\
        0h%2B56E55MfYH4TMOIwUwRFVrzaiTHPgawHf6f6WwqvnMG4uk6as2%2BZxMgJg0zmVBdE5\
        2vmfC4NwE8QF%2FoSQTflVTD%2FHUYG0xIvSiOzbKwi9dWF0GE7YtvEyDqGLIqlaIhfBOxO\
        ikYwVNOB5f7j%2B4B7NrSEhxKnOpSnqmbuGt44xD9YNIOquS77x10a5iq5m%2BOPfx4S4TC\
        ax%2BW9BjqkAZavTUkWJgn5Sq8VPXxdCXAfPp9Kg0TDr7n4Rf3HCpZgu6Vj3Nl6X806W1jT\
        mVzpneGbsdsrvSMDVtrlAnK8xLsBsaXR6pyUGBD%2BuAjUKQvroq3O5UKyGdzLdjltNVM0J\
        0ApDZxTRbkXSqkD8owTDI3u9sLs8cajC4uHi4YawmibG8zKY4fZ8qr9yCt8jkCg4BjtIh8v\
        S81h5TiUJETyZTBkE%2BJW&X-Amz-Signature=27872ddf1bb6b68815b16bba61d45f1c\
        741e9ba9ac8d1600805e0c539369077e&X-Amz-SignedHeaders=host&x-id=GetObjec\
        t"
      expiry_time: "2025-02-22T07:31:33.223Z"
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
UPDATE_TIME: "2025-02-22T06:33:09.817Z"
EXPIRY_TIME: "2025-02-22T07:33:00.030Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=44f8aeffdca1ab949a40784bb1d9a02c6f6e8caf909e663cba4130f1afe39669&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=af406fb7857455b082c34bd689ec1291a38b5ba60ffedfd67dc2c443070cee0e&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=a9a8415b0ff9d868c5522d24644e5b7431c4a4a939b1393d257b7d9635f16dba&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=dacb5728c51912236498a407906ce1df88f15cf8f15467b2b3f77c8a97bec03f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=595ee2d1d79b89f09228c5b31c8823db7457cc417ded16de60087aeda7e1045d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466624NK34N%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCpHyFVLGQyGo9DM7PHcZevSYkRXry98dBchywWw6%2FCoQIhAJHo8U0A4qSMBxro5Ht147unwsP5PDMFZ76PBOef9hzEKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwIv%2FaIK%2F1%2Fbj7xspMq3AN0PgxtyQu%2BjVMYsbuhs7XcWxG6aTM52YoLlNHTT%2BYgbYf6x4kWpPRLY1Eqy57cu4DyyaX6XE59V95qCYIlygrMdJs0hRW9yLRaqjEw8zCdLhq%2FDRP6E2DWp241%2FRXAFt%2FPL7j0uKhydfk7xrmKbkASWUd1Wu%2FZcBf6EVLjqwoaQbZQ3WS%2BFrFnqsT7py%2Fp%2FGOPYPgqOtcKP6bRQOmJHyq%2B1tpyG%2BbYpMMdNHDQrlpBWw61%2BLPzqHgdOMi7UVYwGn7RG98nu75K6ouDHznDQ8oxMQsLXe9WrKYiWelIcPMr3fkQ9LxdQhe7xKC327%2F5u5g6FXroSPL%2BvsuaM6LYJc4m4iSvoop0KtutNbpvxQ5M8NimI6HIQ5Hi0Lz7daUfC8MnDGuWHkWEdv86mwWdOB7fCCg%2BAu4uIwhKM6V19zuvTtOI6endkd60Kod9eKjQgWVN9wLPodKDnZ1l5LL5RBYbLjwZlCimBzON7ayg2iNcT1s4qiLjIrBOtcsbFwqWd6Ta08cnJvF8Y2evOxdfwEcT2Y7azPLvgbHL4ux3vmLx3t0WRx9ei3SqjzugtJPGb%2Baa4fW3u6Spl3KOSGy7F%2BlTZ6an6L31M6VfYQmi0q7n0nINZgPdbLII040hPDCUx%2BW9BjqkATS%2BffALabQC4ZPjIHvBkScAkIFDTRnTUXzYhvY359nClOlegQrtB7UsKO6SFq04NaXC%2FQqxRE5WL411JRgqxSWc5koE5Vyp0a6Q5xAG%2FA5T5VgooA8pRgXbdHCK%2FPwzzZkyUfoT39bT5mdfrHfV%2FjOUXWgva6y%2F4Of03cLzcWDa49QZVZUH09Nv%2BQqk0VVoRbOC0s3HTyjKHjZSHxwGNota%2FZ0l&X-Amz-Signature=8a643766d8197aa7deffb25c78ea22833b2352161fa6cf11a1f63979c0da7a7a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZRQ4J2XL%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063303Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGCW%2Bv7vtOnxA37E3%2BYewdYaXPFQ9aicWMU545Jw4i9VAiEAgqJMR1ntsqfjpwaWk6aLhj2dRIgsAlnubN5j%2BvdHbtcqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDM7AoYqWFup2%2B%2BndSSrcAz78ggkljKqAh8Myu6YAj26QNoSruhOo1Ky4AEBlKVH55EmVNmrAVCkIKLxN9y9aOSPAM4F1EwLKjmrwdww6Gyqkw2w5Lsa9wY8snneGK5hRo8JgQf5G3NIMwGTSZXXapg6vEyvsLm4X8IkDBl28QG9%2BsdH3X%2Bq%2BAu0Xl%2F5k%2Fhv1pkcK%2FX73DKzOobT%2F4dFf0eC1LLi8TZMYYlqwYPKfuRe8aJ9S5fNm2gK5bCUmaKGFsA0wy8c2GlVzKylFNvORWLit5l1pC67s8NFncd7wSpQOJPyZHiQJuBVHF1J0f7JN5vW5gdgzxnyDo9Vr20ObLicy%2FP4CKrcaVWAB%2B2JjOqw%2BR%2Fn6FHT1gRDVGGI53xI0%2FjS99PUo71mZrcCthdgE5ddYgBeiLMEt4vlwCEBLNZGUT1TTKE2x2Eb8nPXhjan8GZHdbJX1C7%2BkewqGzT3JQD0y1qZSEFzqz7Ll8lJTS9MtF1KHX8KyjZNOeMti9m0B5SCUxzek8ddb2V5Xn0s%2Bx7qpQgmMRpDt6umKDIEOsjiMCb%2BFg91t%2FrIk6O2zJImwRVnHR7%2BxrVa%2FbjsQ4%2BePqqls%2Br674pbyM76uNAVg0rv61tVsXlMNQUFB%2FPX3MbcTEFjIOm4bnnYbHqnKMP%2FH5b0GOqUBDjwN3Z5DNRbbyYyKHH6A0LmEBjMaBzvcgJ%2FNiAm%2BpD2e33o9y%2FbSi%2BtNzHc6Q%2BhdLcCV8Z%2B7HjxmaxKgsCr5417ACx8RxspoFQpQ2fBw0FHAvlDw2Qk%2FM2bA52Sus8NRljGfM%2B1gkCrE7NhUUFAD5qhG6UEf8Y0sahyyE8YPxaOzyxY2x3pA%2F3V4TLwrlKYARnbimrMnqNi1MjkVkMYWgkQDgGqZ&X-Amz-Signature=8193f810ca54924d71e2acb554bfa669d32dcd4cd4cdc2870afcc45b9aea5543&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=3ecb06245c96ad20fabf653c0aa44f1f3049251a3a3ed40c3fc83fe0476182a8&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=afd0bedbc7aa63c32aded691a7e009d04a83b3fafc3f0ef2677013e31da52bde&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U76MJAWR%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T063300Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHxQY9iJx4oa2194q8%2FwsV2tOn2rxzfjvQKEowc%2FKBzEAiB123vy%2B8hdDfnUGgrB1H6eWn9IcsTQuIyMvTSVGYVyEiqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM639kQWPKG2PoUzoOKtwD24sqzRspL1Upy9LOhz5%2FzwRExvQZOJkDU1cjrqL6CmoiUYmIxnPnjqiT77KckFhfavFk63igYIP9OlbpnK3WM8lrbT%2B096jFJqCZVtQslqIWhKZ62mju%2BUJoaSuyhH%2Fu2t1j8W%2BHlb76UfFT6ytaES6hrMMHCPiI7s%2F%2BWqtmHVe9dCacqzL%2FR9fh9EoUcI5nU%2BLuhC9uj9%2Fv3NlyDQtur8gVZZYQLrXrsMZNRI0tEfCuAP%2FipFDyScCbUghhUrPRjsfPCYyWpHONkGMl2nxA%2FFn1zRrLvd526uqOk74N8oWZZewtRjzMH2mF0wDQ80UeZHL6TCob%2Fq5G3vPHq4E2Byrz66hC5LcLd5ZjRZ3F065i%2BHiVrCzxgk0XAJGq2PgJ4R568pcVsPUNNb%2Fa%2FcdXMtNJeyLiaGSoz%2BU1wb%2Feqf%2FeHu0BWmL2kRMULCABBM21u3uM6cAMyMNIhuQmonRn118ITgibsRze1JWCaymke7EIyFe%2FnWTYnT8oOwXhmoRe9%2BiIbdo%2BWLWZYEzDaABOxjCY9Z%2BWS9JWaZq1eZSn4FNRBhzgdk7Fh4vdXWE40HQa5IhBsj%2FiiGPCm4jGUpvvw3OVvikzSzoQ3hbxeMkb%2BaKhpcRVnAqQbhVLfR0wusflvQY6pgF5T6LfFlooykMymrA7DisabUljA3PaWbUbJnO6Sn%2Fvi2SDyiHYky%2FS60IBLcIPiWG%2FxHoiG9C7HQtNC25Pfl2t6v0IjlXXH9sjqkCVdG7NllsBTfU%2FsWK4QaytLAcYvs8Tr13DscwW6tXZIfGejFVIqVaKtjm5B%2BjeNZxsVr1Fy9t%2FLbjziy%2FWYPHuSehEeVrdISov00AHWm9ihr6HBuVhKvbNMW7t&X-Amz-Signature=2282b670b08a9ee1faaf0eb276958b7df45fc1911c22f76f0528286388ce5193&X-Amz-SignedHeaders=host&x-id=GetObject)


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

