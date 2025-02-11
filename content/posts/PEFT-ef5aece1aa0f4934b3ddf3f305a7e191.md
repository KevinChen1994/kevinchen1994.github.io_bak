---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466SLXO4YNE%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T183111Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCID1tmRL6aHeTmNY3wtt\
  rie%2BGDx2JFcUphkF8%2Fp5sCoZQAiAGCNXt8%2B06OZXmO%2BdVgvDCVFNazWaBbqu2mH1rgddZ\
  CyqIBAjc%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMlACj3piHGrBDF\
  B%2BiKtwDrhw7jMZBquCL1fDxqv3xz1fJhc3ruIApXSLzF0tQTO%2F8HrJXhpX8sIvRBU6YtsxMOT\
  WOuJk52qkt%2Fl4owoZ%2Boj6gw%2FVAfajxS57TjVB%2B6akGoWYtmzhO2%2BI6EduEMUAZuPM%2\
  BZxTmqd9GLB9wM5%2BjfYIQMbG318ntPw%2FT8C9TuXPdGVrr7cV%2F%2Fe2PvyDH063pnNoVhk%2\
  B7n1I9%2BXbD%2FzHiEQMTFQ0oNYud8WNcS54N7ZKSIanw%2FQhmOLU%2BYjlF0yFGpwlCBtKD1Zu\
  NN6AMlLwWz12924igjsCcidYiWnK8y3rHY1%2F4pXtIaCeF9EXPT32%2Fwk%2F8Ot7xIFi06c3OIE\
  QAoB1q8q%2BVMmp%2B7XCC29chKo1mQJIbE%2BQkjn4XtDuqDACjfbiFJUz9u3rJ66DWD9Od6Joy8\
  UzabMXDEoOpp%2F2DEyBXxP9ZaLqjNA%2BuNVktUBbc8ETdpFBXnElR7lIn4ui0lMLwpIG%2B6Yp8\
  1LQ4CHfh8PPQrEY2sMEYwjDtVuGSYZZr3%2FEXT%2F7bOsOeLMWj3HGJxdreKATgDyV0N6b06MlFO\
  thv5nz3hgUYy0MGvg3DTJreNxUTbiCncvnZxrp2OGhV%2BEoxr9oszVBZVsLuZ6mpf3mtm%2BqU38\
  rvva7%2B5pYw9q2uvQY6pgF8Lab8lkwLvQOC0Nt9khIZIzz4s4lpeOhPjV1XszSMmEXDGTH5wdmJ8\
  JYFLUJ0JvcNY1q5vqz5uCCoGDM4FZiOWT7hU%2BnkaX4tCMl6mCZ%2F0OiDvfZ0s9%2Fr1T4L258j\
  Trq6wPPCeDGx6iDSjJ17uqquXF5hAUIHOlfejh5NTVg%2BIwrO7MTbFW%2FoXXNjx9STi2RpROC5t\
  v0ADN18Yfs%2FummYMNjl7Wza&X-Amz-Signature=e423646e1a7dd31dba542015413d09a6fdd\
  b8f70139c70b0807d0f5f70e00444&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665XQWZXJC%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T182953Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDssv98ccQvc2Tr312aPLSgR9RNvlTJKbaY0y9NOCocPQIgLHGGvqlD%2FiLqEVYrk7bt\
        yGCngHANqXn4zJagvaqpUGoqiAQI2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDNxDBCWL7j4Gyj5t7yrcA02tdq54X9GlgJ1Dj9dy6KgspBS%2Fkuf7x%\
        2FAJmlkEgwr2%2BJtVsf61UC5wMQd%2FIuUwKl95IJgAeXN59uQENiEUxVO%2Fmss9B5v81\
        jUBQzNLaacauSI%2F8EhuOrzLs9ceCECX2i43TeF5eQTw6tCEYOJxSQL8ATL09BIHPCjvWO\
        qr10l2KFLtfE2gOjBaVYiEVBRAUC9URXL04gEHfmKYerWgIm58B4iGU%2BnPeV3573oh9Jj\
        Xr1vgi7V7odhjDeVXMGOdn3X48gQk3T6Mek5hVbvxbJU0QfQWpoE11hEUUxotGiJ8SL9SNP\
        E2kbmOsBOkCnJO%2FXpoy4eG9k%2FxCwmw9Iloa8QtqqobWM9we2ekF9FR8hllhedRODji5\
        KpBOGO7tP%2BE5s9JriaAqHKeqXkLU0GTzPY5iM7Z%2BCaz4oI%2FbOTUpHSIrplVJArph%\
        2FZ%2Fp6IMORlhZkKW5Y74hyvt%2BbdNNY19Er4JnU2RiXBaDMs060VGzPUSn4ZGjCVAoCA\
        vw7gI%2BSjXXsIdoI2sgeVjABilXINtLxOJGaJzD8HSVrfgxGwPqwznR%2F5cHGg0ysAK75\
        HRurLhswTnhxdCbr9Y4%2FlFI%2B3fn7AHVuFTFxTubw2rXxp6XJpH8JMAoHEydvyWxUoOM\
        Oqtrr0GOqUBysp9FsoLblANZz7Ynhw7LEK3NcNLW4wlBVgBeEqyMyFz1H2QZbqgzlc7oXnU\
        mF9jGezYiiVbCO4G%2BQr8yeuvgmdlp3g8HdlUC4tFSgQVB7a3HxtM3J%2B3jndRnaBjhGt\
        a2fzpCrVWvVOI2oeTQJ6wcW%2FIn3PjHRB6rYVuSGs3vnV%2FxHExNKuUUQ1MvMxIQXSH5B\
        uIxnISWSnOwnhfKkJoKNS3%2F1NU&X-Amz-Signature=cd0086bd5be25b11326bb3ddfb\
        bfb9175c0121afc609b3e3d3045aae35f79071&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-11T19:29:53.642Z"
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
UPDATE_TIME: "2025-02-11T18:31:16.117Z"
EXPIRY_TIME: "2025-02-11T19:31:08.522Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=e18279034cfc693037e8aaeba5ba588a0d3e77da0f6356cadc3e68d81ed82e33&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=465ec24ce27b641b2ec55c36aa97e0f47e2df75768ca425e27defe782dc32991&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=854f0f063a9c6f20fdfe7d5f586d20cb7d769401ab8636ee099cc43f4b070ee2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=684fb8563dd7edd4914887fe61e5e6b18bfbbf37592792228b7ebfebb80a4f20&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=6c780aba9121f85dccf11126633fa6b885fea3ca9432a98cc9bcd51845f99d47&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QW5VYA7D%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183110Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIH9FPcSQE%2BGew0Lx1L0vjgwbG%2FEU2m7q%2FRQzoXRAC2i8AiAckIUD17GJnD1OYxTUr%2FJ7P%2FO73WVcZon9xtgssI0LpCqIBAjc%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMKaO6J8erSGRl53oCKtwD2H9iGmvw4z%2BHgTJxW8X23ZQkLXAZmphDUp5Zoq7txJiVsneqYd2%2F4D8husPRpUb3sA9c3hbNtc3WCJrL5jl23sJDGFiVVBgpaYVWi0ZLGUnt9kqKPyr3mBpfO4rH08wQa%2Bw1j0l2sCK5u8PzkO6nrXc40WyfxZGyXn5ad5S%2BfiazEPx0sAwycU1bv4XSS63eHNAp%2B%2FWpTNkTbYjaCydTEX81Mw7p%2FC8Y86hZeNSOEPxoBGC0WnwPRTUtNK58NLQSyTKlpC8A9vI%2Ff0B%2FBfBdwMPSFXWp7GtScAxSQ%2BmuKYIK8XSURYb%2BQ2iwy48KIAWXIlCdYrhlStFY1V4I0RxhTX8aqZkCjRR3LTlWil4IfhJMgvuAjbG00cCWEoIXU4IEZLBh4nzuE6dwRT0B1%2Bu0fby2Dtb1zINzckP81DaBJM%2BhdKCNoU1IH296H1tvNGgO%2BBce%2FxuKOJ%2Fnw1GgNYpzOEbGcadOajLyKCRb3MCY7wyOmSfx7HGEL9Le22AT9noAZtcvTeeby3xEZIQcFS%2B7%2BOfqWB6seQOZXF2XrBMVG6nZKnhNOTk5TTiK49SevkDfmTFZY4xcp3oGuT1iyoXZ09SxuUnv%2FBE4El3Nx5eyhnfpmmn8t0abS%2FibKhsw3K2uvQY6pgFZjF3FZhVf%2BVWKOTZ1Zh6a1Yg%2BlkMrNPKzrfNjfBi%2BuitBZw4Qk%2BqfBej3U58qqB2WKK%2FhJR6CVCJKFNCgBLdkRZZWxXUDRpgN%2B2TmgiPNQagDQwzIYhhyBjWLMLRRWVmgigAUS1tTGubBC0RmpKEctlhSoNdFcwGdLtFM6NMCUbN5Pqu9Y2sJiewGQaxkommBHVVzK7gWt9X8OL6YFLK20eMera6D&X-Amz-Signature=4a729e234202745e32d0156d1aabb0b4c9b6f0aa3c3f74335305f9c696da2f4e&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466R2QU4R2Y%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183110Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEML%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC1Nmr2cDwx1RjP%2BQWqTgCXRD26vroPDClYVGtMSErp8AIgcQEDrqMDauiZ3D6jIFoA6TIFNaPMWaB6g%2FSJ23VP86oqiAQI2%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDACU7ISZSzv49%2BjyzSrcA5W0Qis%2F8LIFwgKtJVroxVmoGnt16o9uPZxTobpgNjcg%2FJOyY%2BsNRdV1y87zvkNjPovsbNLSv2yiYvcRntIKywHkJMAuvLlwm6vEktWld8XjbkljGAZgqsKQce1pNMu0slh84DUdvRClBkPpqBSQW8yLT95xDZl9Y64JTZRR6ufuAfzgbgxGv4bY0C77c2ojA6%2B%2FUssraqUMSPZyVlt0cR4zYiLHRuGfiJQJ2EysfyARzZ19HSrSjGiGLZaXgmCjSEFQgbYPMoC4isNaMp%2Bgq2GgYC92TnnsdKKwjjZ45oFPm7b5nZy1mLlD7PZKXU96NxejzoEJeG7JkLZii9l1hvXw%2Fpjbftxi%2BTctTOgkhta5lDQkWhlbOXOTVghEMntU%2FQpeH3tXp0ScQA9zKg2HG5p%2BsbDL2RbuZVsLEaovjRpc0DcxE9f0bdhBkpp4S7JdeYgAY%2FL6SL1fohuUfZ3zpZyutrHKVJ0HhnaoGFRMPh%2F8i3qqbOQQe4Q%2BE5VdsgzJZ8cFlZ9JS8NDyOBOBhRPa5rEj%2B80R3RWAWgrpWll8gNK1H6AljE3qH3v01sOnhwppP1W8EbvJh35Afh6%2BNJuhxOY3EycTlg4H8N7SKxwVKJIy5hxDefbTIrK9jBCMOmSrr0GOqUB0%2BN3HyUAnOvPmbhrELEe6SP2ofcA7yJlWe1hlYQ0z1wDaF23j85qFuHkIaDIjHaPp%2BJKwM7bFYBDsoUqA2coAH8A4KDUC0QiYq3LNw1gl823h%2BWi5ClbB%2BAO9x%2BJLBXR5hZzF6JkDtTXskaUxC2KT13Vrt9JVrbCHWkKpoyXBpV3yWCjidsfffTu0Kv4V6wQW6zedol8H78mkI5ZdTLKPC4z6%2Bb8&X-Amz-Signature=e133235213176def5c3b5ec0323a87d859f8965afddd1ec5e9929e064e18234e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=20f0e45616ef55f50f688e8488e16aa92545e14067a6696b78af5ed34d1a684e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=9471b09e454cb85aa0a75db88b868336b59c741712d23ea74b1d3acd2e9d17b6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666M5LKU3I%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T183109Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCID1%2BEdC5PrtZn%2FCdiqhE6b4uLOCdx0nvoP40djwiKG8kAiEAtCsmzIHfpBjOXaqv82kdLVZPWs0fm3VFFOAKe8D4wR8qiAQI3P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDP7L13iGJ2AKXWhkISrcA%2FUwZPO9BS8F8E23M5ClsXD1%2F5LYt05zqKinpNQW3CcSROj7jvlWe5aog4xDA4lIsF2qaHYdWdwzsjhIwrkIdhQ8xKrTk05H9xiyL67wymYtaHAix3Qha3lmIfjpsKtqdMXfePQY2HEkoP0Sw1SraAkgdQVm0ZzhokvUa8zwAwo%2Bi8RxLXsCORqRXSigZ8LDgk6apbchpAdKTnTls6GzWpVJ%2FX4sXNOn5RzUHet7MPNuGrSoAK8kQ1CfEQc8y%2BsQbhj9VEdTFWdeRYVwYr737iEu3aO4KCNmoJ%2FCFqMkwt%2FCXHPb6WJ69hV6wy4HREnfHdF3Ng36E5wUsuOKPvFJmXUULdlifRRAcqmdHrm7r2FFrmv5WWTZ3Q9V2L%2Fsk9CgF4X7wOk6g%2B17nOyhlDOmC7HSlHbx1%2FkXGq0EwZaUF1f6wM6LmyVY3wDcXpuPFbpVBZzbytoR%2BWOMy2Wfetg8d1F7%2BE8Qk5b0tyaBbytRN81yimjUmWQDlE1nZujic6FAWVMDFdWlNf3235lmdTqAQI%2F6AmRTWvghobAqXsbdeTUTjFwOiMOfCz1c0o5bEaNPVJRCqBK2mUlvOY8vcMIVZquCB0EdXpB5d%2Fc5ZMXvE4r2sU852hjkan5RcR2aMN2trr0GOqUBf4tcSyHRaOMLE4N7imnmV8jr%2BW4M3s2CTnpw5LG4QdisOIS3dA8Oh4hF3szJuFvWYT%2Bstpb8aqMM35T11ccFBJo8jveCEGIFAphx0OSyhhJ43XBCGEVSh5JvquHdXRXxvitT5agM%2BLYjRSW8ua76RQpwhirJlGVRuO3UWXZPCZynNxADdukmWf%2BkBI8VQSV4j4wF74QjN6Xzi9ZPrNPNcgOOp4Ln&X-Amz-Signature=50a7febbe83c8a0723de465838188d110d8dbb8ab498887fda86d16a0e7cc648&X-Amz-SignedHeaders=host&x-id=GetObject)


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

