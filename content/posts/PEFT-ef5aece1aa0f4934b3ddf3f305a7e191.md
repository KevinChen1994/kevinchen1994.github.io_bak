---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TSDN3ETH%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T222200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECYaCXVzLXdlc3QtMiJHMEUCIQCneKcOcK9dDxvj%2Fwnkt28jY%2BOEgHKWhO7GKqkmZpefrQI\
  gcaPJgYmYrs%2Bt%2BiOxUPsGKDWLtWGzc6KT6kf9CVCpjK0q%2FwMITxAAGgw2Mzc0MjMxODM4MD\
  UiDDdxRSZTozaKRc6VWyrcA8wPZBW1B1c%2Bg0cuNtQwvf44IWYrKx%2B4bCc3q0NIQsEq3d6Qm8h\
  zwdsbv2ovTh%2BMTkfsLTp6oSKdLSytddTx87HW4Iol1qaG70lveiBNZTLGbPfWsNDBdx7rSxrm2v\
  gJE45tZKabyB1NB0W6sksH9UPRi8B%2BMfBozkaaNZOuih5Psol9F3kD9YZeVnQdoDmATHXz3tOSG\
  tbhgwbYijLtIKqCKY8g2hAlJnT9Pe0QZlTU5lM2wBxThCJwUBpb7czvzaPvnUMI2EoGwqeLiDUDkG\
  bTtG2vzKhtiUCmL6BEV%2BKe%2FVbpdVQs8Fb04BJb%2FWlatZ87JI9tBvN53mOnegmQ79LhbKMrZ\
  9kofCJ%2FqENp%2BohHywlU5fgGOfnian7n1%2B0w7yYyWt3yHi2S6dxmILFZ3kAYUNqixQOcH1Da\
  QXU052BIJ3QUDuOYS4ira6it%2BgmQ0v1CsvQf7cmem9SxqhcCr6sw6SyWespP4%2BQ8FqKoONK6%\
  2FCvUczAZWPtmEVMVvrRGOUPxDqKBhVAeI1AThzapk2mZ9TKLPvUIrdmMMCQ9HLvnkbxr5Ts%2FA9\
  k89lwNn7Yr%2BNgMq9yJUJkf19ieQ03LTmU3NyeCTrU%2B2CL4JuLdhTPSEggj2MxcnVdowqinMNu\
  QxL0GOqUBqXd7PQOQCz12OxAQf7RiH0QoFUH9zhRMi7KuZHT8K9zeZLnGmYp3HslWmvCjv658oisd\
  gPTdRxAm4WEy%2F87fdaNl22SdIumtd9Dp%2FHKliA0FPNz5NFTyt2y%2Bw2HI0gltby8YybrhA3q\
  UZ%2FRL8rFpqmVAIimCLa5Ead6mFHGSuZIAyS2MthboLWvOk%2B%2BbiDrJUu%2Bo%2BlhM11G7qc\
  4eUqcbDYN3H%2FUA&X-Amz-Signature=801e3fcf4cc5828b70e64cb071ffa328872de8be2e7d\
  6b29d5efc85bd9c70236&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664UDBETQC%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T222048Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJGMEQCIGzNjb58ZLTHjH0FkFbnBlBhqoa481p\
        doMlNEb20Vh2jAiA21LNgWJv5A4%2BuZDMGA6%2Fpkk4t74fCSOSDdzVpTHv5Vir%2FAwhP\
        EAAaDDYzNzQyMzE4MzgwNSIM6dbFLuVvfekq0ZUsKtwDE4v9Nt1luN89LdfyS8fisSglrg5\
        xBr%2BCUAaHxkETFA5l0LGKleJbqdYO0LBeax2Vsu40xBoWY64NoGUERoUO8xn4YwKK2crp\
        nci3H33RMPA0mR2gEw427fM26UNoCQtN8t5EaCoozjABgmsUHodYqyMo%2BM4we%2BPbwEV\
        CFH6Tme8V3sYvmYOx7qiBRH0etVsfvULZRJBtrr19UM%2FAU7ZOMHbxZyjIA0LiT9Rsmena\
        v2NITeKyA%2BP3%2BtYJ5%2BgPcfCO3cEv%2BHgZG2DjkH3yZeBhtnHPlH9YxI565dcJMMP\
        11sptvX1v1uhOH87JhgqH3ZoKH%2Fcv68Sw46KdpUVTdrar717Ahl43ns6pj3uoUzinawh9\
        %2B2ooaMS7UYmQEqT0%2BqnA7%2FvmrnGPimRoZgS%2F8RmBNqwd6QHTfwIgWjkc96Uk8LG\
        W6O23w1fZ%2Bzot7N006osC2jo%2B%2BPpFpktZMbmrKFGT578xRgMTZb%2B3uKmzw3Kcuy\
        kvXex0hsoUnh9VRFv8FWqB1T6TEzRx2mefmUe19n2CwXp8MvMyqQvWuLsnAdqR%2Bw1%2F3\
        y59yQvnPD%2BUgsMi%2FFq1fXJDzpbpLnFNtVVfKxbeGr6K%2BtHOcFO5ZoKxUW5cVAjMkZ\
        nlQxWdn5vP0CMw0ZDEvQY6pgEV9wFjhePLQYO7G962P76%2FNWAAQMqqH8Tf%2BU5GCUJ0y\
        WWp16MhZo2YgTY%2BcSH2r8unPejPNAu6i%2BTJ2DjJLwCEIThO7AHLiGaZ5d8y1uqXr12g\
        %2FsvP%2BA6hU2wCOqPMnZ2LwLvt%2FRRCBxoCt3jnv4d%2FkeaZm%2F5KW8k6AiM2vkAIP\
        3BPHfFJqKIZl0oBg9ADz%2Bor719iZdHE1gB1dsrua6hzdq%2BJFF7j&X-Amz-Signature\
        =1bc26cbac2cd79aef3b440ea97646d4c5f3d87cb1a78909a1bd97d170aa8ca5f&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-15T23:20:48.699Z"
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
UPDATE_TIME: "2025-02-15T22:22:04.995Z"
EXPIRY_TIME: "2025-02-15T23:21:58.157Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=f9c228fe371dcb0c6aba980146fb06952160b61ccece0a9bf7af2e18131863f2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=556d0e38003f8e8711e13815c4c2e190ed84d5cab9761dcc1d24f63b4b223e68&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=e0b2f93bc38cb4e23bbd5b62f4774aa3e5c695ecb0c6605b0ec205f0ba48002b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=f93203944fc825914c9bd0d00721ca037b06d3038d495f00d0f1b885d1e7c418&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=a03350a5a948c81e16450946292314b7c9ec39bc5301bba81cfb66c2c94f84ba&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QAJEKNIO%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222159Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIQCD6jGXw0wOThHXy%2BGFiBNenfJJ5qqPOHFwuBsH%2B%2B9l8AIgPaO8kaIHsLe1U%2Fozi1aWTJsx9wgYl%2F6%2FPK1N5PyPe3Uq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDOcKHdv8ZY47i7Z2cyrcA2gxwmSa50jmb6FRCdzwD9jcXgjZW0sHalh7rcGPsItL0kIBFVsXmF3Kc%2Fk8uLkX24E1HNYkxjO5EWCU1eD%2Bfm21UF6OER3A5ssa2hJszlvgC3pbiBllYxq9ggkCkWnO8KyyG6ewFkXhRR0d5Hiuy00j6dL8mkRaJnXc47Tq1vZK9RjPmHd7agAJEzM61r1AMWXOqthW0v%2BE%2F4gWJvEpmSN0y9z3h4CFNtQWz0aXuxzTUSKJCooFclUMF11Fh3o2wsidkgz9y26EucvyAZwnuR8IxspZYGm%2FtH6bGzu1QNw6Rk%2FLsWgKQpQr%2Fe%2FRneN2kZ7VwelMWOcPyDbT%2FLXnYdnQG5bmrIbC44KBFU6mPDZCJhpTuJwPhA%2Fcl1ThP457OKRZWWFDGRLY9CCpWx6tz%2Bbu7DhAQAOi3QCG1NctQnd%2B7Dd67pBMNqRIuTD%2B2BKZCfNqrTP8yvGMIYIfIqRADGy209NQ1zCxtLVXL80zZ7pFppf77wnGnb0jv%2BnNxEqvKtSdxaYJDT19mhEsEl37xu1qMghJYq6BXs%2BNdULsMibqvEx1rw%2BZ4I9PG0LsvR6BIxnbqRoqj8J%2FsXyJ6O233GqjWd%2FgQl3sG9VL6xselFTfa2dUqswGZym00txXMIuRxL0GOqUBZy71EbneF4dRRLO58YSN1xqjeyZl5fM57DCIJ38rtUVTZpWKiJUFC%2BLHVq0B21lV%2FoKSB8MdO4r%2BpmUdBjOEwgkKEEO2K7e6dleyEyZZvj9QuuO4mxm%2BuIs503ZLAkbEFC7OeRLQ2jfVhwWEEcGYdBg4eexeqQunk5HHUKpYkDdTL6xzfqedeMdTz2IlnSCGVchs9kFI%2B3WX32yM2OcaxlcYEKA%2B&X-Amz-Signature=1115885806249b41e81b535405f9055647a788c7e44ed3fe332b942d662c55c1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WKLO5P4F%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222200Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIHrCEhUQ44u45nfGjDttViORVttdBbm82BOWK0yA7OyIAiEAkvz6GHYKWQB2F367uxJIp2TCci6NTDDzaCDaFH00XQQq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDPyv%2F7m63YNB2BaRPircA1LkhK%2B0%2Bz7YCbdcjep0zlRuKXmLebn4D57S55qqCvHTkbvwLDvxI5FkYd9UuZiXfsoaWQ3xhAMDCWu55aZPVdyHUtByY%2BYC7niLUPFVJ3KnV9inlMc4giFHcM08kIQ6BwjfW9g5MHQ0o0s%2FhOTJNbvSzYClmwDVXc%2F4Dl6zmSN0X67aNfgUGZYZek%2Ft8N9lncQJ3Y9Z5Tl9BL0oo1zP2f0FkJKmFXYDefbSMPqVjxFOaDiT%2BV8%2FlIve%2BOk%2FRI09fvSHvQnBnOgBvwqMbYYafg%2FwcwRff5Prs1tEG7P2JPVLE3LY1ujTieCHsDcqtfkwxc3hHPlF9f%2B9p81mm3nsjcJJQYtQRV3qnU9nLTcaAiTFSUwwu%2FhciFvegi09YRn%2Bv3P11iks8xdLgBre3Nipe5IfxW1ga63cvJg8OM0wehGczlBue9Smpc0BUYJlqg6cxsgMkFtp3OoLo0U2j6mB7ZXMmeHvYBEwc%2BPZu3I7FWI7I%2F%2Fdzd97r87z4fSkHLCTdFAvmJItKMEzRimYKAyhtSyrjEK%2Bs%2F4Ac8RRijW50M%2BIqIRA8esgES7WhcLu5UHAWBVSdBv7%2Bekw7xzrg4tUpymoYCKhWn7pvCc31MsrGqWTBZU8KrxXMMHm6%2BZoMPOQxL0GOqUBlGxRySowNW5L%2BqOFHK%2B1hjzrWShJXr3%2BNZ4tPqousbSuE%2BqRqrlg5bz33c%2FF4W%2BBrB%2BPSW4o80izwGo%2Ft4%2BcW61oAHulNb835rqXB%2BZqtTHdN7zaBcF78U3STMf0lwYJny5qK7RmsMDm9bj89hMmvc%2B6t4gjq08aY9aj58hHNHVSaJ8Autj7t4Czbbf9P8GXNEvhnLKEkvxA%2FG5GVPIYvgrYqw22&X-Amz-Signature=94556b7eb5c325a9a82fd02052a92feb4f16d9f5851a95f115f282daa78f8c57&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=374f19ebb6b59936599e2185c6cb722087249b66c99ee8bee360bfb045f10f65&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=fdf5999d07061a042e18340e4f8f99fdae8abeb3e3bbdddd9aae8cb93598ce1e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46635DKJCIQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T222158Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECYaCXVzLXdlc3QtMiJHMEUCIAjM1VE14hKRWLceyqPkWcqbbSkhashmsk2IpMesWGJQAiEAvOIQdnxz1jwLQ2JrrlER9KO9AEAaJbx%2BoJy87BqEoNIq%2FwMITxAAGgw2Mzc0MjMxODM4MDUiDGG3YnZdYPXOvxOmtyrcA6uK63Fk1WDj5Lmo%2BxYyo8LXup3jOf28wQTCfAL7qSk3T2saHSDCwOxVmeriCuLeFkBFfZkshkNpK3hj4P1tn9OieT02JijtOuqUA7IOb91vjAk02JuTWe3gNQv%2FHuObvnW49W1aYQafvFLKoIl3VV8ZABM%2FSbFha2W52ZlcP1%2FokLqLUdVoAcQHuBBhAYm8vts8ILowz9aOgtlHQe4so2ATEe7gHj5YGpwc6FiEk4hDI2PWFZjxTyPfZREOClUf2xP%2BcEXuULwX3PWbmYO%2FW%2FdTJb8cJq7rmONPI%2Fcn9WTZsCn4eoQRwNQ5JEEE3vKsj2s%2BTroY65GZvfXk61ws7zvV%2FUKzE2p4IM5hzOMwRF%2FAHscpdwbf7RKghAY7UeeF3uKs64eTPnz1vac844Ch4gTL0FO78AQIBregy%2BWKMAWzYIV4CXbVWqu7VlNe%2F8%2F7fW23ncUxdVcFD%2BboWnSU38zdnwIvqBDNPkSFSfoeBkMRwzFZge3%2BqLZgSvnRLKwup9rUsbjJcePJMw8VFDSdcpbYBpPHNu69QSUoRmmaSarxBvxEPu2pHTkKpEWe3d0ucvEY2xqbrorVrCk%2FB3iIRp8aZEXCJcZ7i20Bwo55bWqoJr511jU7zzLe4lnWMNyQxL0GOqUBOnymHd3DuL%2BefPuw1eoJNcvQH0DHN2Xtwe764sIZ61i8fyEamw%2B6kdqAY2JuYsWCUH6jJysZ%2BZhvUqCs9Sy0%2FSaeOcHOyTbM0GCTWryRpFvFum6BdQTzh2ubRJ%2FvoYuaNHDqFzvx6W0D5PMZnSLN4I9z3iBwZDOMS9PbLwJ0t%2FmLrhHBeArPi2MhMgbqiYrULAFi92sxhGpFPbcTOdqjl%2FGGtreP&X-Amz-Signature=c65240db4df8d8f45e8e1b30c6c3ee8ff3e87381705abdf9663efea0116c54af&X-Amz-SignedHeaders=host&x-id=GetObject)


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

