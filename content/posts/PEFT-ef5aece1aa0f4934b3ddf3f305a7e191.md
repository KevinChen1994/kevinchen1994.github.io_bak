---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466S2LUYDGB%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250129T014503Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHoaCXVzLXdlc3QtMiJGMEQCID4ol8y6ppIbPj4oXNZkgpG27pSR70GvGMoR4v4s%2FtoQAiATT\
  49UmJ7jq49yuN%2FFRyL2P%2Fgld1XupiIkkxizRX4gOCqIBAiC%2F%2F%2F%2F%2F%2F%2F%2F%2\
  F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM1EAWKB3jsMFIwdAHKtwDyU0FIHBCbjR4AtwE8LBri%2B8Lx\
  DDJlfIaSL8zVXaGJ62u3yZQKRtIzj5lrCu%2FpGD4MNC5GG8a41cL1Ob15%2BKfS1FJxFZSMNnjaN\
  2Ua%2FiT0tplV%2BHCYIplT%2BmwRuJ%2FKRSOFrmRu5eesi8GHWbFxWqsJuug0XL%2FM2oglYMPv\
  Fo7z5Aex8RBlLRznK9NIV%2Fzzg72I%2BQ1uB2jU6yXI2WoQUXg0TRLw3fVihWRp0esMF%2BG2baZ\
  U1tG4twt%2FwaG0QFNWy11feoBsbi29X%2FdHLeP2dOQ6WQ12JpbmbMdLDmZ9LYms1PAea6XNCdbw\
  PXFvIY3ZjiiQZi9FUDMkzQhH5Azx8SHYHtRpRrkSZVFHdyKsyYGUgruN5Zc7xvsYdFPaIMhjemSqc\
  t5QsFVDL7SdP9p79eoe8z5zbwq7NwZ4reYsSl7TCEl9JLJHUEdRaZdvi9zso6vkYy%2B%2FFi%2FD\
  UR%2F5h8pt6kosyK5Hc63RS9hBJYkb%2BmGj27AxgyTF40c9LOz54JK%2B7sjbUyKe3dFVUq6iphY\
  Ly2EEna5g7etwdM3R8ze6gIsWfo8O1P%2BucdSXcTfTTeV%2FSYUNSp3CB9cvyAWAH55PNTdb9An1\
  Ar8h7jr4NSqBeT3HAngAajbtUeEwwqf1Ocw34TmvAY6pgF%2BPL8JMHKOXAs5Ow58Wx2YGe%2FCDC\
  uhGA2JFIL4FwDIapVKTlvT5pMlhGqfE8%2FStOKhsYDW1xB3w3qAXBhhKbEXrFFLBiQAEC%2Fhw%2\
  FaDzTJiBAcQm4abBHSoUl1I0bdt%2FRcpId2VdKA3AIptT3DimHPBRIq7heS0x3tZnp1alwBdvJwK\
  sytzyxoedRydz6GX7IYvYT0mGvEouHTe7%2FBdN8nBdy1kJdRO&X-Amz-Signature=c146e4f3de\
  53c4c4b67fb496303368fde86096405e0bba49a61827f05dce1ce8&X-Amz-SignedHeaders=ho\
  st&x-id=GetObject"
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
        redential=ASIAZI2LB466ZPI54J5R%2F20250129%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250129T014359Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCIQCakaTnZY7Wd6AuX6bh3VwIza4%2F5\
        5he0SwuWoUkT9qeDAIgHcHxTC2V37VacLLMEDi6SF7IPo15A1TCDQAH3XxGw%2BQqiAQIgv\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDpOChBgmEkndFBLD\
        SrcAwc0zq3yDV1ZLse5G1SqlbOD1gKJmHeoBVHUQMsmd%2F9ok%2B121a%2Bcy%2BW7qtOz\
        ttV7Jmd3Bra36CSA9Ql4qXF0Xbrby8eTHc3tqePzPNroDeXbJSu0wLBwptYdMMvrjSSwcpT\
        YAs%2FqXdgB7vSWqDKv%2FPCz6ncD3xajATQatKepEP6%2FepvUaooVmQ7yrOvgxOtADMAr\
        Bp7nz9h1nFeRbI4Fsd4Fr2nU0wb8dMcIa1kR%2FMz9IxcNuilKdDNho%2BFmNN%2FGXh3wz\
        4nWaVMAVL9Kezf9az1RZnNuP5ejH5aDW0FLdmuSDtPfC7lsi6aqyvFlXa8CLz9n%2BdDYbO\
        FcXRv7yLRzs%2BlE9Q%2BjImMOo7FkW9IpwiRsYCjMXmr8NMCj4d46cBXD5wKdCddHLKw5B\
        jBYDMIklUsrGwKUyZN9F5AFBrEV4QDS9EkpG4fzwbO%2FZRzPSgFDAUDhoHyoOJHciKQBeu\
        K5cyczANf%2BXD7Xiqe4NWj5pnVvqOwHshWQO7Uhb1Hre3paZ0h9UuzlgNoESxTuG4fDp5F\
        j%2B2vujK19aIztPPe93LK83vuu3DQ64tEqtSAipbNVPYR8vKqpejwkbWvuN8YH8kzlukWp\
        uaxOEow88VASgTLEIhzyhgEVU1Z8LbKaMJmF5rwGOqUBHdBgXCZV3k7AnhD0x3McrjtFk4A\
        yhj4muC3oMhoDQLRyOaPo7tiPJGKxCebkwKzwK%2F%2Fxz0yUuE8K18SgHq4AIukKGLTTzz\
        fH88Uca%2BFT27HC7FehS3sBHmr5naJ5c2C7jkUn3imwIAfm%2BXZ43xNzR4TzvY8o60Ia0\
        CSfjmAiCflD8dwj3hq9KAdgmdoCMJnFCzopcy4Sz5%2Fg%2BrkpEXwJ2q9Wy%2BBA&X-Amz\
        -Signature=935954e63d643018247a86273fb9fae2c1e58aa20000d498f5a42bf20944\
        ad69&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-01-29T02:43:59.546Z"
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
UPDATE_TIME: "2025-01-29T01:45:09.787Z"
EXPIRY_TIME: "2025-01-29T02:44:58.179Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=aeecc88d51e7d4c17a0dbb693c81ba3f2b3ed5f5c758b624141ed7da397354ee&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=573c8a479c18a467ed18b2d27d6524d40ae1725f2c850908d1b6db9bfce7732d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=ec7adb24094db93be2a4c32d5c114d3841203e6a2d416432e9c6f6873410a585&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=3189b830b58fc113385bb9f9a478bc12c82e073f974748bc1ada81103c972c76&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=e3f56d036263c8396e7f0ef5ce172e3978af1d2907e2034e6153573f9643f0b0&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XON25MRA%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJIMEYCIQCI2GPNxbDOBvAKNtcCZhiopvqqvWaRDSI9xU1vFMetawIhALVx4wdZmOPKWwt6DuXv5WxMqGE2loLKlA%2BsLCrReblPKogECIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwmvkDcpKUd0bL34Gkq3AMZjIB0LmF5J%2ByvnFpu%2BUc3X5H2mGjM4hlQiMcIG65ztSc75PGwhn8QJVPaGvqBUSy%2FujHM03bnoxz3WojCeXj1Nv8a0S3xT6g5C4dfeeRwFuAYafBeNuqXMYDRduN6vN3a1ZhbM7M1DBk2jq0mRdI3Eol0Ebpaa5qRy%2FJuDSlEZIRM9oMsSoZTkBqCgJSK1vEj7QZ4Nupc1Y7Tej5w5kKYXmA3JrRQ3MzittezM8yRfFKPG3rjQMlpSoH%2Fu8WZiho769sm9uwPPV9i4fU9ygl54TxkgKDSt3WcN4aUjK868lz4y7LK44S%2Fx5z5SGJV%2FxL5%2F8RInW%2FU5kUwDwnwj08Vj5GYfxFeQXytWmex5V2cBtmMkhzO9dF%2B7JGu4lnNJ1h17YoGmCyrWxJ1LmHXJu%2BEn95bJrJxJbWi6qtf6TGvRe6l7E4ypmc6TmhXXzKX1ltTP6ngoOVPiKoAkmy71pjzMYQRm7jYjYkDRn5fMcIwdFlXy%2BV4rKtSB7knqHcDLm3dM6quPajaOBmky%2Fsd6girWu7btvfTI9O7eRfpr0iep21KDCmgE7NBYiOnAuQUIUWT9rUqqdNafYQNBkYYQjrX2JwOOoAUNxfvDq9yz5yVVAop883aCLypn8GoSDDQhea8BjqkAddfvKWFpkAzX3ruEzcEJxK3%2FkVf4zZ1jI7Za%2BLMBlLGn9VwYPytBwclr0kB0I76IT3U0II0ixhJs635SauTcDNC%2Fsx9Qoy653am%2FUrtPfbWZBe4riIkFPAkW5ejp6WB6I09hiCbjMynxMtTPEt9Nnw7IN1g2zm0fZGEGF40Pd95wGPE%2BK3xufTM%2B52HPIO6GffOE%2F%2BjsuXcSRfd%2BBY0Ll%2B6TBos&X-Amz-Signature=e4e422718082ca09843bc72a1e234d57f81ef40ed9cd15acc797161b6e13c254&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UKM6CZ2M%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014503Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJIMEYCIQCzwrfTwby%2F1ZR85jMyebmpf9JzN0nfDk7n%2B45jANHQQQIhAOdyRAYC81uc%2BtqP%2Fq%2FtPmNnMec%2B6A4HhN8EbMPPR%2BLCKogECIP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwY1FqnTpfRrdbQYAAq3ANqruAgAsQmcTORm8qqrqYIzFKijID8CIPCpfh%2FhabaQzuw2Exi5CqveEn%2FquAC0udMN60fetiKRugvIGuas6YWEuEb2hdxjoOvS0omm4b1Ht%2BqsRaO2tWJkQigaBllzGnxBWYcWI1sUaiUfNdaXpmDz6NbhBbK5q68j%2B5CYunnij%2F4j9vgcdinJqYLLK8sKS%2FKUU3jOGdcBP2uq4056M1%2Fj81VDPdrjgW1zq2o8xv2mihffLG8abQw3ym048ZN7uYpELRQrJ7ZYIWiMMy6iR7yzrsLZs2FdiBKk9binj2cmag3F58zs2ujvUjUaiaTjVLfE03QmNj9%2BIA2PVAKw3idOH6L4SeFyR3qV2Y1%2FbBpvT1fCOjdGDrfaOF3Whv1I%2BQrnmWWGoPZ5co%2FMwufhrU11apulMDt%2FG15tO%2Ffl%2F7%2FJd%2Ba1dd4VouMuPzJro9rnPfrPHPsY4cqSvQ%2BBUQSLp6gkNuEw%2BXYPuMx9Ai4d7UafHBQIm%2FbKMf9gg6EsCdyO%2Fc%2BT9ejyZDFlt1MckN6HCPJvhUJhtE8O5V%2FZpkuucV0B80JiOFEFLDrWNyTtQXXi17CvuDuWcVPPPmqAP3kKdNoHtVuVEBpG8cPxPciYb8QMSujtB76%2FYbv%2FCBZ9jDRhea8BjqkAfY1Fbu18yosB6D8bAngxLKmnqT1l%2BmFRxBrGqSx8KFH%2BlUgJqDNaeyiXnecjQRPK4OLhGq7wlEHMp8H7BsWY%2BsgSJlyjOPoHS46D4P20no%2F7SZl1yPnpdCnaw%2BLthyR4LotY67C3sbW4z1HLZqpdZUGI5%2BVbDPwl7c%2FBI3nNRw3uZZnOYBKP2WKovVg4vS15tARkwoarqMnvK0LvZ02Hf%2BvFWKD&X-Amz-Signature=d6ac48adf9a68c3445fc26224afef3786980ff0797994b394dbe68422afd7402&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=ade0583059feb9cb6e0d23683a9ed7d8c5de9b0e280d1e22ee57d0218da56a9d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=f8ae582cba94655c74c343be5f471fc6d7e24718929cd7acae587ded56f263cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WEFFO44K%2F20250129%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250129T014458Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHoaCXVzLXdlc3QtMiJHMEUCICc9tfTPhjJnCTBAfUatJC9vstRX90mtAy%2FiyzZw%2FQ1OAiEAsd81y%2FBhUhTpyZCZd9EsqfKOxo2kTohBuIxRcz11rUYqiAQIgv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDOwp5%2BC05YYPAFYxhircA4YPtqbNRInRFkGGQcdrnijn4imb9X0fkdo5uA7wrqunIRwMzc6dEwn%2BSFK%2FKkOznbZHPcdBEUnYCEIQhRhJJ5yCTf3vbnGxOQQQRVnhpJWMc9GWlKYYo%2B2dGwKVOb0GWk03F5LioXG9TXCMiM2RngELLlCtfjUTFgrrntXYtoO3dZtEHYqtTAuXMPbjMYwblLg4j8xCfe0J6CzbCRj%2FGivd3IkBQKSz6Vy4yg%2BuccKl4KQ%2BYU4Ze9%2B92qbqw%2BAnyIaP3lRlcK8iwrxLw%2FA7%2BKBKHw6wK%2B9ZCv44SzFjkZVtb9Y72qJtClUfphObSwcPcHjac%2Fpp6sppxYWosGaOoVn6geMD5QICTZrZQnBRTBZJY5BIA%2FqpbgLvKkgJX7WQDxbxvZ5%2B5MPhGj547lhpj46GwIgzc%2FBOxeI5q2cLJhelhqPQvWAcRDVG9W99hVtD9lyeReNFX5rntRslI%2B01zqE%2BWHJfMBx7xR697UV7dP5HxKDnLEkcXC9qT1jnsgPxchYWS59ETxFpGctq7PKq4Xexo4zb46aAQE3PJ%2F0%2FCM%2B6i5QO%2F4GdQR1eLNN%2FC%2BObzLHp268x%2BKxWejFKXhJDZA%2BvkdmVzFgDQK49sVCMWwU6%2FoE7FqAHrYHJKDITMMCE5rwGOqUBmMZVZM%2B4Ozvyh%2FA6f6bl1eZwMdnVpwHGWkY%2B%2FYlInbXMB%2B%2BZVtouo9jpnPN4Sh48XG9MBuiS0s3s1siuWVkLzfYfSX9%2Fj3KWpGvMgHqkDfijNh2%2FH9Rac%2FfjWfsB1bPsJW9wBR9iFPMRTO5r%2BVe7MWqhzOwzJMjxyil5GDTq2MxoG%2BFT5ft33bR6XsQLTlwd6TnRWAtdPOf7dbnn2pJjqObkG%2FR8&X-Amz-Signature=483cee04420cbef9527b30d438c6345af1eea31d8cc3634e9c9419d1f579e618&X-Amz-SignedHeaders=host&x-id=GetObject)


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

