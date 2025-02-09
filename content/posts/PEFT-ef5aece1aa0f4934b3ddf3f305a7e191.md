---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YBJHHRMK%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250209T182845Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC8m8lGaejTpFAXc\
  xPj4O29QWuCHz4zUK3rfnsq93BVgQIhALOywq84DCu88qW3sAOwoy%2FLtp6YaRYog77N4ItZHWqx\
  KogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igz8QrMRxTQ3xwFBA\
  H0q3APPP3MSaGepxneuJn%2FOYtH%2B7R%2Bgs7L8mgPmFTSbSkW7R1jlCVeb7MgznhIR2Rc0caOb\
  PeqJ6hzdLeo3ehChuL7SglE1OAduFCqTr5392GArJcDG8xOChp4NGRtBt%2F8aC8joPjqiv5v%2F%\
  2FJ6kyj1EhnEGhS3t1F4eXz1Ugp9eJenB5fofNyTEOI2N1gEaRi7u074t%2Fxs5beGuzhZ2dOYJGr\
  4wwZLc6vsRj55y8mDN0hskSEkxDIzchGuPrncu87PyyOD3a2CPVk5dUf2z8COiVYK0KDp2eM45LFN\
  q6I4OqWwKAIqb6%2F0Id3i9ADtM1BINTDU9LKeu1Iix0XCcHjXHsN9aA3T35J%2FPD3h7GAhpn20A\
  eka4BzKIIrhrOhmi3RghLkl2%2Fiuf62QS5kxQqtl81XgSUM4vQrQwa4Mce6X8CUnCDmMKA%2FbSj\
  RWdM7yWYrs1Bd7v2HrAnt6YnlZ5Pn4kutfZQR5DVrVCFtxpNGOyPIKr7QJazB2Mq0i1cs%2BB08Q4\
  HqUEu78EzHbCvobPex%2FMq5Jg5jgDfxXK3FaPXJ%2Bphn7eJrf8vrHf6icTfGL6HcAxez2f9dUd7\
  imUKkSv0x2WqY3YXG0hNoU%2F9c37PO2ydyrreXBWW21yVF1k6xfvgjCsh6O9BjqkAfh7vdkgNMpH\
  0m69FSXZfKsyB5Y7YRFwbwSplBBRs6ogGKktovxJe8TipxgMdg5t9jKwlaLCo4xbw0jc1c8F3yLGK\
  Fy%2BSDd5JqU%2Fk2LWDYvLgtHbBQTHVfoWeKOSl8fcT7Wahf9FlMnLv7MFiEW3x5KwzkN5VdLjid\
  iC3pCrxVyRFOYcHssRdMcRykPM1G%2Bh9lkcMHDPwd1WPONAGdldL5k9qP2I&X-Amz-Signature=\
  bc30b01e7acfe060aefcf8ddea2fe016c0b229dd7cca69ceaa14a4a36e419f95&X-Amz-Signed\
  Headers=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZOINYQQG%2F20250209%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250209T182722Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGM\
        EQCIEzzi0dsWa2oO1ptvaOGL6K1OGYI7ipD%2FFbRrY1XbnkxAiBeH2P8amTlKi%2B%2Bxr\
        fz6Cg4BL2NP8pAwivpbN3aAw28liqIBAio%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaD\
        DYzNzQyMzE4MzgwNSIMm4r4EDLpAveZxArRKtwDKQ621kXecUe59RUxa5wbzNP3OnbzbVgF\
        AhpVd20YR%2BrBbfeWxxA0SXYSyBslQHihIsBFaUQacJ4quK%2B0gkC%2BzKSfX7fEt%2Bn\
        ZnjDcQ4QAjfwkJtlfKpqgARe3tYfxGusc2rVp%2Bu60U5cljNOAgmQQXtSU%2B2wXNrvbc%\
        2B5jv1jeT3W1QSQpfF3a83xpXCqH7NzI0GpAbGb5n2op8lOaeylsMtoDFOXs5lwSS0tQkqJ\
        rFLygk6IxL2tHbFrwmN0vPXyDdtwOdRieAmgkb%2B3D1XAQcV9rQUwJRCXzMl2kMXyvF05Y\
        2s8KEHaUhF59sk3t%2FtIVtM36qrwIcc5hBQTEJ52bZWTkZLNarsd6CSQl1iINbi62x1wgB\
        TyM%2Boi%2Bjpg4NiRK5l8s%2BcAwWn5OeZ2T2UUqTs%2BOIVOk9jTr63POwO6qIMzzyRvF\
        Su%2F7c%2B5SpglSK5eTNSKl7TfgNhkmlC0%2BZ%2Fh1lQsSA4uf3kB3%2BWk2ZZcBeBXzK\
        i1fJrSBRD%2B191%2BN1Yph%2Fa%2F4VJfWzCCuIA8RsJK0c%2BP8tB9Qz2V4SSftirlsvz\
        LXaHVKagslXFyEkGqPTr0PMAsK5Z4ZfL6oMLCqXiT0xafydQ2mY5iCrYD3wR%2B7ZNOLdi4\
        jcnnRrQJ6zRIw14ajvQY6pgGoTK8jIy6FOQVw87zyxS%2Fi9IdPDgCbnfdRfQ0zY3xFhr5G\
        Q7Nu%2BFEZzHUB7%2Be4TADpQMqvR9D6oYT9PArpXMiZ2VL%2FFNfCT6DssXQjnVYpXerRz\
        oE9yAXuiNEi9D7Sd5fOBh5%2BXtpF3SfxrWFd1a1ve1pQBXZ%2BUsEyg2KrPTQdA%2FKdOF\
        X6eTmbueFoEUZrDlDUTU%2FEoFnfUi3%2Boc8agW6Y%2FxbMe2FL&X-Amz-Signature=47\
        4157e39f46d8b7cb51767496e94909ed695b1248650544050675544a873612&X-Amz-Si\
        gnedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-09T19:27:22.472Z"
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
UPDATE_TIME: "2025-02-09T18:28:50.561Z"
EXPIRY_TIME: "2025-02-09T19:28:40.951Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=53fb54b8361a69e8c01b1a90ae268571987b7d11fbfa0a1ee522fff3768b5a24&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=571fbb69f13edd097ba7af39fa9b98fdd392378ee300acf106018ab9caba164c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=12e8cc12b506fa2e879f3759ae4ef3b10181decf5250089d20e42227c7b86299&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=98cc2e85852515816d232dfa601b781191a417f7d8a8fe58ccb6de93799f4693&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=2ffdaeb1e0aeae93d2bd5d92d1dcb66b76567f16da1328740589dac94470eb6d&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466737SIDIB%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDfmwoxUvwK2CsElImHhmzh6uRReJMHZPIWX96TZcz4UwIgNSyYEI4Z13p9b0O%2FDpNF7Onw3ajbNqy%2FqfmtA5AZYhEqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBVeK7veNMFl8Rxp8yrcA8lijt5k65bY1KlESMU82vaR0QNnLxEzZ428AFG6KCWnejrsfs97IpgCEU7sKjP8o4VQ4MZld30b0EvV48ziJp5274cJ1zm5l1VvbyL%2FN%2Ble4BIArPgq4qXp8y90POkN7Yszc2hxvTXuSprh4ELF7YoF2ehuwMphKi7n0vkgsUGOYpp8os3%2F%2FCY4mOnGMFNBz9o7iKUTOhp1Z6px4RTIqLPS5Zgmgh%2FdlCBxAmFWd%2FGXBgsev28ELdy1p5zra%2FkugUhGRXfoQc5o0%2BJSJUJyIJ%2BRB9RSduxaSvLioIqByC5Www9a9SRboher0yL4EaM3%2FKMyBNXbEHd6zCRARQG%2FBfsV%2FhtVeZ0LBaxa46%2BoEOb24r6M1PgPlhm69SwLUumFVpgy5XfzoC8c%2Bcx8kLu6GjKkA8Qri4aoekKYLrUJiogH8j8lG4ymvfRcc6SqtwoxPBgkR9TptvAbLV3pM07qBim8WROemVfp0OoWLM2%2F4sDnTLpcexCiSgnqM4mc85FtmBSfCqceaVwnmPp%2BQPzDS%2BOo9khAfqCZ9mTNMWZ93cUnD170RgUHiB8F%2FdZ3IFgFQrH8a16Dz6pEKe9gWGf1HFmvHxDhP6%2FZ5EExTQsC8ZVrgUHBCH3LqrJYV0ziMP6Bo70GOqUBcgwwEFjw0UGojyrDWihjhvoeKIz6jE%2BTaoPKdytnOW8C8%2B0u3iIV8TdXcqApR3Bx78W5HMmTdY7B%2FhzqkWZPxuopwU19T14f%2BOaSHNcdCazw5WZcZghcbE%2FZQoHX%2BL495is1htzWWqZzT0Llzj68wVDyDQxLCslZq88QXAqpSIwI8b99q0c6w1MhuYqFQg9cqrjYYI2bB%2BLatVRSfUmb0sjvrFKC&X-Amz-Signature=ecccc511bc52e7483d196203817efe4593c9867e32225f495a047e904e7e0745&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663NGNACK2%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182844Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIFlQaIsGUaotneyGjISXgszA0fOcbUBPmAItK6gq2utOAiEAv7a4FqOUP6uko90%2F83zb3dQCELavcQs%2FDpG9SbNL0%2BQqiAQIqP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDPLOwYMvurbSfY9tryrcA7y8BIgpZMDHL%2Bw0VAMcQ4B4M9szz5vN2LMd9YE20aEjao2lvX9e5nK24Vf12NLhIVGMQGp8kHgi6BCQlVB4jPXHsx3VMI%2FmFbqrhWzl0lKJowf9UtbG%2FK%2FfbmCnxGDka6UY1B1PIkdX6TtZjo%2BeRNTINJcUbWw6trcdPQgGXIhiU5Y1M64kbzN029eY1rONqvNdfCLbkqCpv5qFigWjIRDPFcX9%2F%2FelyNXL%2BbS5SQS7vivonxhifWUXqqWMR7adNCg5Kuujf7VlEP8bUNw84tbBj23CpSeb30qy1QIpWfgmxySrtcclpnEwl3fk736c8xglDI5RwX8OwXxj6H4Az95LdzIi3voTbPKsNiWTCq2YP2Nzc2a4a%2FUFh5l9TPC1vowx5bt7nj5I9h4vXHoDrexRERcU4HZaOXf5LpERm05%2FDfFqeJ%2B8w92Vt8OGtr1QUurwuwvGax%2FmwL3YOo%2B%2FpYB%2B7qs4ZX4GL0bQPQ41OvUotWTBAmB78ws8nF53g8txvm63YflOBnd3XqE8bvgKDlazbhaDx2s5Hq72uAxRZs9ryGyPx5MjlzvLvyeVhx8dtx64kjzdgGSuqgnf25OAytho9dBf5CFdKYoB1m%2FWi3gtdeohcBaWCQNu3oEYMJWJo70GOqUB%2F4AEUxOPNwJghrI4T4Va3uAVLiXxem2%2FQPnO9ENngEI1ZTLEeKzmYklpNxKDC0936NsZ%2B%2FHwtRuQODLzyrE5n22eOy%2FcsgNcqGf17NhmCu0juxWspgktyCuVWEXcWUH%2BeUVwlkCs8dB0%2Fe3RcoGz4aLvebLY7GzCiHzI%2Fd4n%2FfxWtLionley4yzWNlxpwrpv4mIXHxwoN1rba5KD0pVPAnJEf6Vb&X-Amz-Signature=3f8bebde487d31435afbdce8b37f60978e7b8e8bb1aa92eb3bb2d7ebda6223a6&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=b563186f96bfd2d0ee427859faaa48d66baf17672cc21191d7951373ba29a5c9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=2526053ce295a4568fe0bbe99b9dc223b3e6273913b387c2b82d74b05a6a1ea1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VEGYC4KI%2F20250209%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250209T182843Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEI%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCJG6quwIE%2BlBQXhnQymThfflFHT5jQEl1J4x7tgfOs3wIhAJauPhu%2FLWbhg9aveDibYGAzkAW0lh%2BZVf%2FsdMzruXqiKogECKj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgycO7NKR6B858HuB2Aq3AP%2BqCn1VCaHOvVxsZwIpZP%2FfZbjck1hPBQF%2BKDMxin%2Fw4p8nAESdp2gEVTUNDh98vPqez7uuFPMB0BpQIsDhet0XfDcYAa69J3wDyGIlBauTibtmMTDnCLT0waV8LC%2BPG6VQYRZyANA8tcDiyapZO8GJsJ9lCEeLqm3gI04gMIZpnd5TUkODIEszOLueGOffA9eDj75JTYIfOtXdduJS%2FouOLRdRWsmWjrOc%2FXtIeoifi0HDaUXs24avYDwyeuoRwR4kc8rApQ5IhFm2zoepBzAFdKEwJWPwj7vUka7goDDXdD5pftpP2mK1U26Ru7SMm9XpYuVk9aRALSBk0OUSEifsSAN4RgR9HMCsmYZvnVgFTbnDVd5x7Z9kMevKwLLno6LrUHxorSu8P7lwgBAFpflWiRdY2PnOm93Q3kDa5%2BeN7dVR47N7Yff3oa93dZG0KcbSdt6u5JxbC41YFF%2BLRW0oahPPVsS2JcOqc%2FL8iRO5kQViEno2QCm%2Fb5E0VXduJgXYq5hWXgopy1KTb2qVNNfyimaT7U%2FiUp9CzAFvIk3Sf84QGyzvu%2FQqK9gZB51aztK94fppuU0K1jLqkoJScGSC5WHi9m0uCyLCtMcWaEBImA2sAVX43swuP1KKzCZiKO9BjqkAa5QRRtxhbiyM28AYGlTndUhd8WzETWUtPXMD%2FY0N6ToROix%2BYFanzlB%2FCyHWaZ36Iq8YqoqpcKRh1D%2BwwAl343URyIzywSQ55hJePCN1gjYR6ydtP2XlozYi8xW%2FuxO5o7XuQTVdB7cavx7tKxl6D7j%2FR8TpW%2BiXHkxa%2FjKpvdceEVc1NBcS0e88YHAuLTMApLMQk1RzN0rmtAiqHlZPjj5psJl&X-Amz-Signature=ff19fae2f9478ea3f4eee94cf0cd6fd543f61341579b2c1d86c761a7dac80ae2&X-Amz-SignedHeaders=host&x-id=GetObject)


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

