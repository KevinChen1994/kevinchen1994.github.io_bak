---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZJ6FAVZS%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250213T142317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAPETiLDPpXwe7OoHpn\
  Dq4vF72%2FczDrP4zprvwXx9v7bAiA7wjzcD5IjvwOcLf6xCGR291RoNzJAAud%2By2ou8rQWfyr%\
  2FAwgWEAAaDDYzNzQyMzE4MzgwNSIMNzdq5qA79V3KB081KtwDuJzj2ilwqwwF6E6J2fdKC30F%2F\
  SE6b7OkFS8%2BNPR9%2B9KwiU0aq8EnHuWE%2BkIokkTsER6H91kjjkw6FlkY8xmeO1qan2y17cNq\
  kpSAmZBkFD135lTK%2BHJA7sJJjJETt64R72eyxJ5VZkT2HJPiOCLkmoXdhsIK4UkCoo0NeYdMuos\
  tGhDQ2MWN4xxyTZ1YFwlukrkimGS4MFuW7vylxwZ%2BNu6Zbj3rvPRV0IrALK41Y5P431weu8m8vY\
  U2ypI8eEwW76nP6vkQ9FNXRRWhh3SXSEaXhENS2pc9DJQHy9A6SQESJU7aVuPhH0ZY7X4j7HvqJmz\
  3zUcCc%2FLqgvCOK1ngnvDfccIfqoNqLgxgdy4KmUSRwrYgbR%2BgcEVi8tSFqKz%2FVQM9FSZ9L%\
  2B4NddF9MupprbNLcBivGKHSuT2Dn1YykpRQfZ0YsKCVR1avf9Gtw3mlXF%2B5QE1Vc1FFYfX8AvQ\
  gzcnp87U7x3D3eQq5o4ndP18n%2BmY3gH2ZcQ4z%2BXgXKs1NCDfAaWtSCDqGNCa%2BofyXnDcdkS\
  xi4qXrsBSC443bKipb3rB%2FShrx9jbcnCQP9HGEMbhXyVCvmHAcxcu9NeiZ%2F2%2BvrX%2FSwdJ\
  AR5dxo19KQXVdcnoNXDhbqLh44x0wqN63vQY6pgEAPLXpNezcDtnG7CrI%2FWtwQD%2FgZbRcrHrj\
  v1lT9ON%2FaiEgu3vCyNbLi1z3qmwX98mR0KIqp9WwQAnigBWOK6aZAhDKK%2BEwnlVYy0wNh%2F5\
  reOiA6l8EAP1EF%2B5kC2YYGzxb8TZKDUUw7RjBSxGPGeqGRozV86iJ7KzaPgbvpMTiroh7CV4FJu\
  HeUF%2FZeoVlFtsnszO9%2F0ZIVR7LDtjOYLNt%2Fbv1PHDr&X-Amz-Signature=4c4d380a272b\
  40731c813ce043aae4ecbbaa3328373e3836403bff3fcafffd43&X-Amz-SignedHeaders=host\
  &x-id=GetObject"
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
        redential=ASIAZI2LB4664LZV3PAX%2F20250213%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250213T142137Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCJcO8dg0FWcG%2BeScA4%2B2AULfbe1YMDuz7%2BPJzzJ4yWWAIgSsPg6DydbYXK%2Ff\
        n4sHxtxmaGLamdiio4QpOIu9yt90cq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDEss%2B3SEi\
        7KiWLSFsircA%2F8hQM4IuSM4JZUG6Y3IKC1bf0CP87iGYXRwr5O0cEl0JOrwYa8d2DmOpk\
        9AW8AIm%2BpCcHNeienkneqoB9%2FiOZORhigfeMPmPj%2F7AkYT%2B9xs1oHv8trYB%2F8\
        gVrdiwt%2BElpzP5IoyHmdEKiR0HCUrVpC00HPOeuNd34EnTCJ4uENQfbj7K08rBBfzGhk%\
        2Fnypz%2BxW0MywscYT81u3S0wL7ui5umJKGwpVqeisI0HLKtygIECv8Dz0goal0WhsX%2B\
        6DAzaoRpZBgS303AkTVotGprj%2BBHIRR5ZUFJIzDrtNbyYaAN%2BmS7aGkTJGjL3Zi9Wbd\
        f%2FcT3CBj1YbpSPMvkSJdVQzYm6OD3WzLgzqhR%2FqsKqbp40rwtQdx8BFajiGVdWRZHRw\
        QaCycTzo0kVa7QyYET9g2EE%2F814y0bTj8geRnIt8YRc1RZ1pcz3%2BgnLMILbF%2B417B\
        5mhdBPlFdFutf2EAJUe56rQfYLW5z8%2BH5%2FQo6dxoiMNFun91bYi3OShmo6MoQoSsQJd\
        ViCIwQxeLzdOhX%2Fqrq1tq7PqaliTrShVqPlYHEEz1T1ApgOmFW3pwQze0HLKpoYdvACJv\
        zsz71A0nHo9k%2FPb8rkISpUnb4%2BiLl0yaDIHIxhcPjEdeXCsrMI3dt70GOqUB%2FueeC\
        jvbxd2DTS7GzkxvhzxgDNeVOmpMOHMOYJGVXqVnsLxz8nyO0IOabUTaowvXSlyLAKLGj64n\
        XQlyaHqP%2FRvgN1t5zZ8uFe8QE5fnCkMdcMx%2F%2Bs0iWhr2DLjuBfKSWQGEUUORd%2Fk\
        vcVwLrZN6uWWnNnrJly9CBdZm7bhsfL4u18rcWgDVBynkNVugYAO4hevN07hdEl3iILAXgt\
        %2BypV3g3lO6&X-Amz-Signature=f03b831a0760ce032bf1ea92ceda10927ea8ee7011\
        6456061b230ceb153c6f78&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-13T15:21:37.541Z"
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
UPDATE_TIME: "2025-02-13T14:23:25.793Z"
EXPIRY_TIME: "2025-02-13T15:23:07.921Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=efb16259a4fba1c090a1ee1d963b02f7854d279b1243b36bc4ec00fac22f5372&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=a7b2e3c3a2adca0eefc21bccdc0031409cf592060870c8101a10cb5177a55282&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=7e4a9674aea7da433783b6dbf155fc9c8cdeb6a9d5d18c8fd8af1f653aaa4093&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=827ce6824da0c8df189f94e4cb9d1cf60c31f9a38f48400f666d95e57209ec6a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=661515b48ddaa606f9ccec51a2e0a7120ce3cab15ec54fff16b209df789c3d55&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466U2WU7HGL%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142310Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDBW4Unk71F9cuVv41SaleGoaw%2F0zYuT8fgVwFXr33ydAIgchCgVS%2B3CRp%2BC1q%2FUao3eSXaHq7mwGAuWhzGyVmkkm4q%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDIFvBJmEJyiA3DXfcyrcA2BXO%2BywPxKJd3kfDQ5nPN6037SR7fEhZRFSzeasD2tVX%2BTeDlhAHuxG13odwfsM9puJ5q6OChkm4zrqEm5UO1weqZNrNnSU%2FknnjsFKQWAQh59bpxexVZibJnyiUfxki7sAN6UALenZQG5I5rJK%2FQUg8iPNdWg08p1a%2Bvz8wEQ99idYtf%2BJXCRSRZhj1CdrHtTqIJN%2FiqIkTZ1KxNTbCZMCpO%2BODxxO3OcW2AdADOPvITx0mEdZC%2FzbLubqKG1UPlqUTQSoyqsBHdMXvBrv9HKecRRee4bbf1ogK5SITMnpOIqh%2BEUQxnQFFqWTqcnPYcYrDdipbLg7yd2ZhUGSl9aiEtU9teHk2dqt95WMwF839IGxUrJpLCD09ibDvSkW2fN1bNUcP1LZSk8E3Ozica1NDPSkeH1b6HoKSlytXQDXNvJ7SRUNILzmgBKzHWFEHTjDPA2cYN%2BYSWNz%2BLH3lJkM9U2dtwyvipVEtqc8Z6CXQQiHma8UM%2F6N6%2BySYHVHAPweMwDgZYka9TJeh8dG1Vk3eszPcKvkopoEt8AOaFa5jT4SQ3RDzILlDTPtVM6%2BD9KTlX03LkrbOmXSe12dmYmEsjz%2BWddlv%2FwYCcKSoMsBVU3BqvOy5RD46cl8MKLdt70GOqUBasVeVdQ%2Fmg26ORgk%2FqtoXY5mafDYtpDw4X5gEyGs30mtCvDQv53PhlBOBTgZ48tTDVg1TCKQNrEjK5sDLQotyuetVarSXLUbvlLyBrWlbnLyn%2B8CzFHc4GOZKxEP2oq54PxU7i74r0X%2BZ%2B2bFEZLSSV5lMpkCq%2Bs6iGYpRfGewiyU%2FaE2A21rzpcqWuEUgmKpV2Z2SKnB8%2BW9Z%2Bx%2Fiw3gQiO%2B0tJ&X-Amz-Signature=6d94ada7bc98fbbef5522163f901460ac4a253eb808490a21f4eb40aeebeccd1&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QNNYBJ75%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142312Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGMFcSJOZ%2F4x2uTE6rzNr5sLCHhnl9fASOySiDmN%2F4hfAiEAlTOm967HMQtrlQ3tXTZmj4l%2FOQONhlX95NWEiOZb8GAq%2FwMIFhAAGgw2Mzc0MjMxODM4MDUiDIai0tdeLc4pS%2BN2EyrcA2k9TocjopAgANXoP8%2BLm7JCtwm4c6jAJiATpSKPWxnAT19rAMo4Kj0BWHVkts5qNalHzKku5%2FpsImKUnOCP3bNRr3NCIz8wP9V2ODxCM1U%2FovlK4WQDwukML6utfiT3IGZz4%2BXnFPLp6MY8vZJjh0YcZnI%2FIFdh6MUVU8wpO%2ByaSZ0arewVanawVuArjbkcgWWhXiMHTLx1ZPSnt3sMkIYyRLMVm5jT%2Bz883upJWM%2Bt8nAFURq9rc1Hht5uZZHQo%2Fc0WLvB8MsbyYjisRdU0vcVcpK2P4dCUhsbFcKMZFa5nyX1q%2BtuOAke3%2BVFNujkLL%2BpCVVfzTTrVheg5OC%2FpKuFUC%2B%2BVr5bfiF8SH3hH3jCcH1HwjDkiNPnI8cIHizHxljiqfPlCmkmDIqHrtl6lFDxY3q43IUW0utIv0kfNJu%2F7MAO47XcaBnq2ZCDVrTW%2Fx0Ii5d5M8a9KDvMdpGw%2B0Z5USduU6DFy8VUqN16TqXRrC7tUj7BvcepW73YCtOAXdadqNmGxZwh1WYz%2BdXQWkScz%2FZPdq2uAriuznpdSps%2FN5b2rAtAksIvjznCYx14xUhs93QDBvDSiGG5e9vnoX6fo5Wvq4S1zqxb%2F126f6YMIQYgrZ%2B7bp4PBAdPMKHdt70GOqUB68kvHsweaQgm3ERLKY%2BAD4JsRejsx04%2FO3SuIzjWGDxZgvc6LvAd81%2F0otgofSM19NTDoDoHguDet%2F1QTdRm1eyL4U%2FA9gcUWp0LE3gCVr5bBjBbdeok6iipgUBV6kkWep%2F9mWLhmzWExKhiDF8do2OjmSfUtE6ZIm74WVZbq6gwvp4lHoDgpJ01AJ7Ic5Kb0e2j8d76GfhV1aq9Pl34zcCcb8m%2B&X-Amz-Signature=5f3e0d8a8aa1480b12a565a2c3d2b40445c4898d24ab32a23f47f68845779377&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=2132340a6f36c7e6e729e958d1916576f4dc981f7f48106ad432e91acd4fe59c&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=3342d2f6d9c7eb2e4725924ce0a35021f0741ebc5955c4d44091d7fcd565524b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YMLF72NI%2F20250213%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250213T142308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIAC01YUqbIDDG0GqYl11jesNZMw2%2BQ5eCKMz%2FJGOTMEeAiAA4CYNvy8s3jP9VaOufZs7cXixVerZTrra54rDwJOWlir%2FAwgWEAAaDDYzNzQyMzE4MzgwNSIM2tnShpQI6FnC8t9TKtwDfT14V%2BqXgoxFvhS7iEXN3u1Wsc5ew5zrT2bBNiU%2BJU7gmC9bn%2BmqHOBlOJSII%2BupfRoIajWdiEY41DCJW%2BfkZtxFGqWV5zBVHzwQWf4Xz0eKG15a1fAhg2KdqsIgWb4oqIFn17%2BBviYdxIVgHPzTtyzkGPRAvBAgbz72%2FHbMWBeAGOTQ6mL5TRxg40XSw8tFQPi73VMx0%2Bjg%2FaW9QFOu62HmVRNx9KWUuCc7pWm%2FEMxeeK3f4Ko162bo9G25R%2FoHrA71H26%2FgQjoI9pSCbgy6Sa7tfmvOVjs%2Bj%2FdpvH1e59Q72ksXFkGudQCzh%2BNzE9EynV7TJc6V8fyrN3BixJ8G0RQs3lpW1QlURF3E1dU2PCe6yjOyyOlVRwedN7rglFAifk8PLbwCMetFGEmPy0y%2Br4Olpv%2Fcw7qwduxruahRjRUxgOfmu5ZCJLiomAgTHcug7ueRKB0PP8gQvdpjQZlkAiidvciMmQFIJEPRJhrWofL0OfFoQ%2F79hIgSecXPEbQMe%2F0pCLbrs7HGAggf%2BqHPH73QSNGN2RyxPyko2ReZ3AfwlMMdNpCYz5lzEwO874wXLzFbVQuCBmETQaF8V0QXOs2cexIsUgctBXKYmNZodzdrYZmR1x9E29QO8sw8t23vQY6pgEMNkHL3X3qfCiCiWA3y34M9ZEB9hSlAe9suF%2B8ntX%2BNd%2BncWIMK1ymInpNhI5wIjpEZbM6bSXZABKNfluJ37y%2FefuODwrhuQt4qosUX%2B87HFVwYrsd%2F48MUuG%2FMdz7H91rD85EfLwwDgoW0YgovU4RN5RDbfP%2FvJOJ5c0UKxWEOwgGL7BD3fLWkAfe5nDCwzaxytg8r45lE%2Bis8V%2Fi%2BRQxTYwTNXgD&X-Amz-Signature=240584cc20e88cffe4a580e7a969ce442712e2813b30fd850ef1fd27367939a1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

