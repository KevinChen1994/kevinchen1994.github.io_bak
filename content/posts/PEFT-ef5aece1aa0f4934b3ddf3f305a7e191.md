---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46665UCYGVY%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T042638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECwaCXVzLXdlc3QtMiJHMEUCIQCrYzC%2F62DEaBT4sHEQAqcf9KxIVQ6vAn1jm8ns1DoSrAIgJ\
  nva7%2FSusmMIftenRxjteztrTng6mLoD5fPhFHX29W4q%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDF\
  TixQ3LQe%2BjMFmsbCrcA55Y6w07d5LINsBPQTI3JOUvGV6rYxrghyVVV2qpvFkrRTTyi5R%2B1GV\
  1XsJl1KvTRxpGe76z30xrourKHynfhapli6FnlVvx15Fl%2BmjXcRXdpcufqEseFzX8jPnDsj5t49\
  AKVrV2YELr1DYfG3PwrnvdYWzrG60h%2BuNeW11UEkuIay%2BJWYGl62zT9lcbo77Tc2ahiVqkqmy\
  AmoGgmJAqv3OnoVyiFHBrS6UCVwluBVeJZD6palnSv1S8i18dmwCj31ibm8fXikPCd4WZWP53WXXI\
  %2FpZpGeZ9RtHOMms%2BKKr6RLzwMQeuykIntc9rTcZo6n5rFPX4NEoCMtiasVcbby63HftlGuSQL\
  GmDWNFNWDnGNaXT%2BDZ8AL7c%2FkbGirfHg1A0E3VR4Y2Qp8oltz9cCNme9jTPIrDNu7js0K9d2v\
  M17PsTcLNcxszXy9xgxmsCOi4gs16uJ2iSWqOke8iPLlgeJKQRSTxh8HDleIs4aZXOR3iIGKdJC3J\
  Zpj8CtpzpRaRvZxzABDrMs06zaLH64RQPOXKjJnMzlS1QLqXbDNeLLRC3YTyjrWId4a%2FuLl3oy3\
  sLYykbWNDlM9pCP0Bl1s4xy6YHXfbefIYoDSbUTqtvWoTWrhxq%2FSXpbLqbMLXDxb0GOqUB%2Fh2\
  rljY5KKXE3eXSXC%2BQR8C%2FS55iUuMt8v29n%2BhlUhASFuMNrWQ%2FEoTBZMUby%2F%2F0DmOn\
  tapSDgP%2BL%2B8fidJiaeaNLjvZgKkAdm9BrIJhBJkE9BbjlnVdNx5TbxG%2BTqQ76OAY6Wp7bxR\
  TiG0oABb8FSfD74Aq2L6TcmVfxxgW5oa2YkUJ6dq7GbHhEx6oo5%2FEqPJ4PdaON%2B0E4T2g%2BC\
  PFyPX79m4K&X-Amz-Signature=37bed2a0e103ecafcf9484c323520c131770cfbd70242fe640\
  c5b055c93503bc&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4666YWMUQ67%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T042527Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIGg6BHcI1hUR7aluIlMJ4dc6C2SEFuR\
        ybeno3HhJFAWVAiEA9RB2aMd1vfYh7Y766I%2BuZ%2BwpWyxn22CgI0X3oPcNKKgq%2FwMI\
        VRAAGgw2Mzc0MjMxODM4MDUiDFXQSIYaES3LwvcfxCrcAw6VbumkB%2Bg%2FXic%2BC8QcS\
        3TTMj0cCED7j2P90ojVRSzWmGse0%2FtvSlemeXfIqgUb3UrY%2F3PvX%2F7NOcdfy1W3M4\
        EzbOFTnsPLVgLAkCVKszHp5fCSUw4GxsL3H1Cqo8NfeoiLwT976C6w6cwdm7dHl1dYme5jn\
        3SBBvJUG%2BNJuYMAOqGefWSvYzQ6jygAkiYfWY6Q2n6GG8kUspUE%2Bm4j21TlbphNmLQ%\
        2BTmbu4%2B58q1WFJnH7KG6YJOb%2BTQo8sFSpBH%2BXFJ54mwh4dVF0VGMUanyinKkMCLb\
        jBvth4WP2WfqAU0AGAdeB5si9kuNv1mMpsLrfR9aO56a8icAAtPYe5Bf0s6h80M%2FBYws1\
        WJ0zTcZmC1wwW0PuIoPF5skemtA6nrfC2nc6vFkpFTzdE%2F5rUM1goSM7B1VTvNls09ISH\
        NpkkSx2MSmayhhAbambeqUdwq059xfq7ddnGze3INtMI27wSLisSvqGztl9Bl8Iqi4gOCl8\
        s0psNhRs9uAht6R7dmLnqn4xyxD%2FLZhIgsGXtPejGfFs05rNZ33QFHht6euDSjnkF0XAJ\
        Xo%2BHrL1tZrimlsZLQsjm9hSK48LXCVIJYeo1NhK0hT1q0LWHYsTQfpDac9On3xCgsjCeI\
        uiMLjDxb0GOqUB3PKgwRk6iVarSldCX11fnWg%2FV9dDanliUKLNpDQJTiCtKPONCT%2BXs\
        wQpDdZLpUS9cxH4ECslKV05H4Jd2vyWcsXujqLkdc%2FQN%2BaE2z7O5AQlFvy2y0eX25QY\
        sPqemX93gkr%2FBO29lu%2FqzoYWiTZIDQWUtoDfI9wxWjRnOSSuBhuPqoEAXwjPssiiFKb\
        HTUawyPne7gUajDXlo3NMtkYozkb%2Fworq&X-Amz-Signature=82cba639b40e7b55618\
        2dc4b946dbad746ea38a90c04648e72d8d9b9439ed35d&X-Amz-SignedHeaders=host&\
        x-id=GetObject"
      expiry_time: "2025-02-16T05:25:27.122Z"
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
UPDATE_TIME: "2025-02-16T04:26:43.366Z"
EXPIRY_TIME: "2025-02-16T05:26:33.593Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=4758ed95638d0179be6aa5435d9e912fc6dcdd4865b35b5eca6442213b1d9cca&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=5003f047b095b3b2823d0f4b50e9d083b85cff313b8ce639a1e8cba3f1685556&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=93e0ca2183f02405283d398315a97144c0e9edf7bfe0cad1913f937d86e791ed&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=6779e26a48e6650f8e3e3c04aa6a832ac02925da8d3732f110187c011753083f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=9f5de8a30ce60646dddec7402cc2301db98bec50dcdaefa44a71e955a9fffaac&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466X4CPNFTW%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042637Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIQDewGbSJbsWHn74c2u6H37jI694C29f6E52R0ZhYw38tAIgZTM1Myvm9TF1n%2FaddjjcKhoeF23oiDlBbkJ4pOLi6vIq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDIxzUaNV%2F8ntcua%2FWCrcAw7lwr6Btj4tx6QoATCZthxoLZUSQciCWFTX2eS2IAKflpi5jp3qs0q5FUa1bE6FSFXyItJQKAT2b6C4S9E6Uu2ybVvIe67jXxmDlSQIAciGRNYj%2BWwr%2FRb8a7V2gN7hn2KhnUd5rbhwLQ0Au%2BXRYDb3bVshagkOphzgL3Oz7TaYc%2FkAzG%2BdZYqdAILh6i97%2B1dSdb4Lpa4IhU94NlgXcaIyMHesgHUdiawM2KoSLTItYzfJ3uCBDD33oofeBy7dD3TxYsgbmtSgS%2BRjnEmx%2B00PeqJF43i8CoRsap%2F5YA0DVj28bQPcTUozzZB72hyhEolrMPV%2FkPI%2FrS3vVYb3Whkp1N1fg2O4PeZQPWNbvShaKmP1BCG%2BudkWHe%2F7%2FvSrF6ORFWja%2B5uZs2JJtcBGrj%2FvLrUwiabLhBBuo%2ByxkMZjtwzQqeNgszR5ahjNHoQNh%2FDWfXO1VoUxr8RW6w8VTzBjaCXZCYbl7lzpn3R5yK6WnlVnT9Ml0nMhQsljtu%2FBiR1rfS3S2EhCE9Bu0YL3eVItIZyOwMMxHUGZ8SqT8p7723A%2BM110Wlau%2BlWO6DPH1C9Lg%2B6U5Zer%2BiBF%2FoAmdqc49opvLlBeHcQpQtjUwa8dDcyvj6o4Kzm6q5Y8MNDDxb0GOqUB41h%2ByxxcQBb8bRpDVn%2Fbh5MUu5244Ek%2B3hIntbsrEGE2DnpEN9NiKtrs7RSasAfALFFzDMWtCmhtxSE0fp%2FZfP6bR1e6lpFeY4Nq5PhrqLFJLfdgPVh%2B0MP6dPaw6joKLJMAjolHV81VkJj8e7EgDG7Kri835fFdY%2B1akdjGK5AibhcsAmL74VLmTiotsZpMd41BKsOiUrK4y1goeFKJHwBmLWwv&X-Amz-Signature=7304506a29a9426282279fa5b9bfd23225bcc3beef745d6597d40b23b398c656&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YOMLZSBT%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042638Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJGMEQCICMYfINGosIoFZFQtud4KPSq9sNSXqVtqxBKtuSWpLYXAiBZ5y90U9sUZgt6nwzA%2BNcvsq57DaQAmQNIurt3a1vrYyr%2FAwhVEAAaDDYzNzQyMzE4MzgwNSIMqubvnbA9SRWhSi74KtwD4ZapaaduqH7gu2J5ciZ9Y6lEcZIHV6pcn0NQ57BXRBzDK%2Fy9lEqDA14gxdgUe5JqaBZo%2FhYQlDx4163xzAfMoqeU0bCivGgof%2BXoeEKVEe92N4Nm4FdV%2FpkJAiQc6XBfH2NS6fkmfVOj5gaaYuSCbRnm6DVLh3NmfXiksVsjBwoFc3zl%2BkI4Aol%2BrIk223Ph8WbqWRHo7%2BQ6bKxrapsLmbxx%2B5UUKuWwC7yfq%2B1tiAjLDZRxvI9fGlejQ%2B1MK2l4O9VvSL3GJmi%2BHSnXl7Fb4CJz04%2Bfue1n2NMkomy81Q968aaB8DERgLhBhUNa%2BByBDd11PGc0JGVJqyY%2BF8SHqof1x7KUwQ4XOY6AQol0I2YNjoR2OFDVaOVRmsoL3t17rQwnA7RgJN37LIjGEOt65n6ln47hWOq%2FpQEJI1hdl5QPZ3uOgnDSRQcD2bEr4RriJFZFRbI19RtU3mwXuUM21SWWz3H1QudfCt8YFYGdr4qXTFHZys2rBzzcoLE%2BQpjyxiK6UcPua50veAUdseZe13ydWD%2F7niw1zoOKCiYPHZhCX60diAOhNal4aPJbBT3CZ3cuayRD6pZaD%2Bjme3Z7nyt6ScZAfRH1sbWq0zU84LF3vSycGiEm81C9BL4wqsTFvQY6pgEL1iPMLiMis7dZZuvW1MxQMJYqYISvTevQjGRvMke3bljY0fAREAS%2Brx1ZFNNVfyfqmiFXE0jhza2mKOcIbSakk3YaE4nsAOJz9vegirj8EVvqP3CGCg4k6H4I8Vgl7VmfbZvd7dGxACen4oJYmIikyS1NUhG8cJ7L2CzilPa7BVY8Yr5btHnnU0zHLUmTN7uiijbY7KWF2uf71e%2FAVGN8VAQ5kNqx&X-Amz-Signature=1511d6eba10075f6f0975a67c3612c2eae2e7dd7c205d7bc9eeec09a87e02bee&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=c8fed7ec299c06adbc01587331a7f43a2b3ad0c2d824248b5e116d42a95835dd&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=457be5e6143a534d4df8c7f5fb048d22b8da3ccc3f338596a9c12f75b4ec7cd5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664LYAZTJN%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T042634Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECwaCXVzLXdlc3QtMiJHMEUCIE1f%2Bvq4UE1SnmRf9bgKZhvnJq%2BxWXTGe%2BK4Xip1u9frAiEAmebsXF4alYDwBkmee4d%2BbgaaMJstT%2FqcN4wmgkiLeFAq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDO8csXXsiRLn%2Fulj2CrcA%2FKs%2FxYJdTdL5iAP7rJjhDRVV6UVTSb4dOIxtFxqVb0c21sksgX5I5SoHTlIMIoaxGy1AXqVcfIkyvwbeaS0TeXtibbg7pirSgXD1xb2GnvzR2%2BmcP%2FDV7oAt811%2B95CVGyR106soatNWIDv0gPiEfBJ1K8N8nAB45ensIIeyKOLveKtzSX%2FmZpZyd2RwgqLGVAYkqSQ%2FAo1yDF%2BttqccB2CmYlcSVPwSNI53n6%2F5yKgfp5bBYC5aYm0WKxtdhYSvmRMrvPqGyGIgRly1xuFxuBIm9ubIdrYT5DqtmH8HcG0F0J0BkWbhBnnl3QkVO8mPhsn5aMIY1uEFjXvVSa3ytJyraDYzMe%2BbuYmGRQ6xzJtfrs0%2BmDQVuCN1kxTg5Mq%2FRWrv9f9AzbrNy7DJx1FaqO%2FMcGYnaKls9%2FT9yRFAgJ%2B1kJpCD3fD0sUva%2FxujNmsanvyyNfhv%2F7vyqx%2BbdKzdJuuLlFi78l%2FnxExEjR%2BoTFD06X%2FIEgHFd%2BHfxqI3RRo%2FlGtBqjoJwTkc6pXOQMaEiAs5l748i3Rqho75WaxwqQvaM6SlY0k4I0hpv2fXujYUcsyvB%2Bh8g0nr7HESO2AJAnVRkGOo%2BJ7X2EcDpT6WC6bYD45L14%2F1NPG2g4MPrDxb0GOqUBkUxS%2BFPvnDP0aSCLVPna18%2FUIBc54WH%2FrXmJLVWAVBBNHPgKxY4%2FZOymbH4bmLx5gydpRk9OJ7FOjjb3gkkJv9hkQ7Kbw%2FhRcEUlHp5mmvPItDjbiZbQV8GzcWbkZh1Xaz9OkHd%2BDd9lMFQMM8H4RXDEBl5NTaCEDbUkd1rjnJqD8puPdEo5euX4dwjTyrzdCAStQiWze16vP0%2Faym%2FY56Ia6Ojq&X-Amz-Signature=dae8f7c48bd778fd1fe0a07a27de58f199b9831f9b891c5b439ada6b1104cbc5&X-Amz-SignedHeaders=host&x-id=GetObject)


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

