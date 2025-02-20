---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ROAX7DGR%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T124708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD3BMpBOSxEzPiv1gg\
  %2FsAD%2Fm9ketRE47ad3zY8685kGSwIgIAC3B64RSwJDrox%2BU2Cqhg%2F0aoDAAiG5PPpHK0Fa\
  a6QqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDCrHZ7%2BqThW\
  BzMdfiircA0v3liKwyfz436M0QwTsHHpo7mlkv%2BjSLKEaZlTsvcOZJCUivSNO80yve9%2FcIaBR\
  kWeiV%2F6w0e9cJMffjbctUIr9StIm%2Fe1ZD38TD6fgLVtDRl0KYKdtWEjH4grQVT4t8JatPGAEC\
  9BJTW0GF7HtD52dY3LZtnVYW16LTcQts55LDHRrFcfigQjR9galg89W7hqKzoI8U%2Fe8D9m9Wi36\
  VCBN3%2B9cUQmws8KhDPR15ePCQjYqvbzLacQKwWh0pZ4RgKJpUyu9MbnGAIBzilUedUFAnzSN%2B\
  %2BGZI8u0MvGniB48EMm8WTY8ueR1eycDy0B4nH%2F%2FYx%2B7BHBrqeNarlJg6XezBPj1fMNTgb\
  tCFVHh76CMgMYGD25%2BNknSnu3oluGw1AOGuRtaukdkusM1erQPSmgEXCYoF5eYd6WJxdrpTes6o\
  bob9hxbFvbaYovuy4O4mgspneA85WNkH9MrFo659lwBuEBszv9ts%2BG4PuEidwQNg8dKMl9ZWqEU\
  vx8xpxHjkrPeQsGUc209YLr%2FJW2FWNOn4foFPNBP%2BRS674wPt9ZjEm0x2f0qPMet%2B284pS3\
  RdfWAPth7xvI7OPyFnxbPGIMoYqvll2OsczKJnzEycsbn7EGpXYYB3CwgcAlJMIyt3L0GOqUB2Xe4\
  %2FAHJch4YfTEnlCtbQVOOQ6iIuy2Qxo%2FFyS2HYYaaK2UlEfXZhBTePC8dyE%2Bmz7uzCux%2FS\
  lvhWIFgqAt1nOAiTWWGCrDJnFKIP4Udw0trRuIZKpB7pGQy6NNNjNr9Xuwjj6qEoL4ChKBM3p8C8I\
  f%2BpqH53IZ1vFHmnVtPQfjeoKiuqwr3O1bhVGG5NvKiTVnEZ4HTx6vRcd79GzSTthgC7X%2BA&X-\
  Amz-Signature=580fba4ef9debc748c879c77b77633ac5d91810615c8a2ba47eb911a4c27ec3\
  b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466VB67KAV6%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T124550Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQCvjDzigQQwvLRk8hEnBDKfgvsz9OWVOlNPlMA9lSTb1QIgQsTU5wDlkkEYCMS66iixam\
        hvV%2BNcl1jCA9su2rLOeT4qiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc\
        0MjMxODM4MDUiDJlJVPEqqyYU7Dn92CrcA26I2xRR%2FWBFk0l9VIcdVl59Wf%2FJbexcWU\
        fwjkxYqKlvsmprHuXdz7WvplswIyYsWkzQRVTtOWSdhLaEGcE1d%2Ff8WXoWroflLNXS8wi\
        DSgDBgM5cra85WL8DVGMafOcLsQVjuWgUa1LaS32fQ%2FJlsizf9TcSSlZuJS8n%2BKx9di\
        rpWidHSxzPcdUmHvt0zggww6KCNO3%2BH0G2lu1vzxB%2BitHOOukt1Jk5lwfrKP7EUi9fK\
        fSXXL57sI2Tzhjoc4TbcPgY5beFnJVpntoTzC15QXmn%2BDte4b13nE4UOfnHn9CgyuvayH\
        UtZ%2F486c9JmTptzt896ZTBV9E%2BTcRE1zJocBV1mzwN3fBhos%2BTSF4i9i9CnXXKwjd\
        2KAl5nyBleukZTYi1zwXxmNY%2FfWBWXxtLpViUnbR9uPGyjPmSIJpAMsWJKLuAaSJ%2B2Y\
        ehrv4fV7rYC1TS5KdT2vxvce1GBX6bzoaSZMeV%2Bb04tL3qY2qumLJ8sGx4ufde7mA6ONR\
        HYVfZzNh29vPYcUrVk5eJHOOOLwnHe8QDmd4oJqC2tCkJxn%2BAM2KQjzD7ZfV%2FAGl2NU\
        WYyNgYhAJAOqC4rsfIknOtWXRmCuHntjTGN9VDtCQK0DfxFLGyiLu5bxpFk%2BD1MPmt3L0\
        GOqUBgFWlU6ifqV%2BJqOs%2FpqZAjhJT4tJ8lPq4f4gTH5jCkcnyhCzMPSXlx05pGBok6l\
        ldp00ZAtuwBhVuOF3EFRp31Nqb1N3MQUbxaUXOVAd25n%2B4LXeuI7Hd4%2FbF7RmkYB35g\
        mlzN76DeSMN2LTKBPumc8gRb2kwimoAIsPo%2BaK69njpuN5ZL0ot3wtnfmb40PDO%2FcQ7\
        PecyfVdmMWZUa88P%2BNosKCWI&X-Amz-Signature=46363ec7fdbfd00e306375b3e52f\
        0ba086fd6f3fc07836509a8ca91393af8fa8&X-Amz-SignedHeaders=host&x-id=GetO\
        bject"
      expiry_time: "2025-02-20T13:45:50.700Z"
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
UPDATE_TIME: "2025-02-20T12:47:17.470Z"
EXPIRY_TIME: "2025-02-20T13:47:06.403Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=1e8c5ac504d2d196ada46926d1b8bcf239ad5a5f0e81766426fd7d3f829c37b6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=121761c4327e512a6b618add77345167e84952d1fe22894c94bab149529559f5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=383c19df0aec8e1aabfad57dd94e2d1eccca373c1fa3d6470753980a663b2cb3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=f6f7e03d93cac8810c43048ffe231317759939d94a0de5b1437ad94f19f330b1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=72701f991ca6995500e4ecacc74157c825c568c8f3e6aeeeff2478896ef614a8&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VD622AHH%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124707Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAPzaUNp8xIsNPWQX2AV5sXIY4MTCQfNCHQ3205t6yy8AiEApvc3xVUbN6SlL9P5b%2FX706Mq1D7akwogRkANPV1HiWcqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKZNsvuVSeWPNBVmBSrcA4vcRBN8uwpNawjT3lmSq86sHmzcttrUczzLV4ZIqu64ZrSnGPoyDfRIIi0pR3zpIC0q7H7%2Bxzdf9DOmCVkXnkaxhHuC2dPv7e6dXX324OjTvrXNQ04i4%2BSS%2F2G%2F2TL1LIO1WTMMHNDUIBiaN4fM6UUwOA3y5VrNJspczv27UoOxwROlQ6kRqMQLL8Zu8lOvmvU79qSJOsOm2z1RuI1cys%2B6B6DolNgj9WPdSav6LafmJprzNwuXGKfrE8Yo%2BP8Z%2BmKtYxzHMIGMcevgMBsuZWfk6VB8kwnkmqOs6pIh0in5bfkQqqIiMl62F7gjrS4Gz%2FRhipQemEpjO34o7ZSWFXAckhl7CjmHMOL4pX4%2BABCA8fqMIZgl1epSDyglNNhzW%2FxEkuUp0FN46owsdvFvSOsErP38TwZW39hFyrsNtJrYJ1TZYwF5fk49fHxsbT1Arcx6b%2F11xZVTwb2Q7Eq1OgspFRqmo8pb7S0c62PsWlJDTu5YWY%2FSiMpkHBVV0SFL%2F7HWHReaQvEKbvtXgiL4VFGvr4reDC6vxZVb0iytn8jfM2irO7urOvtqG1mgsAleFeMxz5x5ZlNZzqZqY2IN1vw%2FaJ8tcnLSJMVv1kXqh%2BmncDKKwp11pVpzm5DvMIat3L0GOqUBpQZflpgEDIN3G%2F4jO0%2BWIKvxWnNVYlMghp9w4WShiMeSsG3eQI5XBhLV7ENOEmLiU%2BDR2vsRkT8X5k3w%2FDj4ODKB0TfyU76j9o6xw1G00J8i8SuD8YdCFvC6QDi%2FimDnDJi1wn4ODYI92A2ozvozWgzlBCa8FrVkdc3q%2FHsf2wlIIBP8XAFg6Ym34ivI2uni3Lh9ybboD%2BaIeKfW1O6oFxFxJGrw&X-Amz-Signature=830312e7c9e9bb191e61623146402b59ab8ccf8dae39433784aa703e55138f3f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666RJDC7XL%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124708Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDNwQisQSVveedSZrxmMQjju518KlG6mE4GnRDuS1vmDAiBeBk4KAqljXv0IvgXS1ixsENAG9BvCGHPJzuaquOwX9CqIBAi9%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMNm9lZYeLQ90TKBFXKtwD9Q3UMFQvr3wKQxH8IpxPr1re6JMX32%2BeDK0mv28ka1YnRQbDFcq6zTN49gJqCI61ceF5yjrQeOmvWCNmwU4fiJ6hXfn%2Fc7KX7MQwsIC6izg8vWbsyvTMpcHQ1OzUF9N3nzXdZui5%2BfYyHI%2BjCxF5EijgdDoDOcxErpQJGTHyqqEMsx%2B3J22oooqwcRG7Fv6fh5gzY2G%2FAnajntsiqiIsi1xfeBiuyfawr2UM5NjS1Iu43p0HSWfoxei9Oao84t3%2F242x4ByVRNon7iIt%2BEinhlVhk6etT9o4SQvnDpCTEXi4Gh19QjvqJSUuq2Fb4JGpnUWKPNddDnVf10wgbUh%2FA57fh9Gk5UJuMsp0D5QptGahxOXWcxb1f03qfsTtkKT8EVu1hpQy4zM4k7QST7v7y%2Bf6yg9DaVraTZN5y1iWF22sEVnqFPihE70GOHjpZb1csFoApR%2FWgMXQhbbC5Az3JdToWO%2B1ExSWTtBXZZGoegfQgRey5hbEehWFDohnlkObsE95x9f0kKcM2dlUbozKyXzSn7Sm9en6E8fsUV%2BXQkG6nv0ZDVgspnLq%2FLo1ln%2FIkxjSnD%2BfXGV0f8nULlb%2FN6Mh0dZmRN%2FPbQ%2F2vy6t%2FbDKO0%2ByO3jus5ZvyAswiK3cvQY6pgHywKhIOSllsPLvUG9GuswJwtPMdohJ3hU0pZg%2Bh2dJT4k%2Byum7UdxlKL8MVD6pNNvYHxsnRTBauRSc3T1yB7s7sTIWW%2B4JFuemtsD%2F2pJB%2B6OIez56ilK%2FnRIYPkHcnhpm3fO8EKPmAJCP2qepvoto5XY2nWaZxjZLazhQdzynmuYVGnlGP0KqnXQznXz1OfTB%2FHIOashyVjHLheKd%2FObuYDWhjVNb&X-Amz-Signature=1537179ac71f4e42af2e1b581dbe6f1999987c8163aff113c322743377f2ea4b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=36c497db84bb94a99752f08f5089bf8a50359fac2095ea25b9ff0e4f535ae42a&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=f881018ed8efe13698ea3ec02ed668e5086ee73120a3fa9ba8f23bb430fe02d9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZWKDS47P%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T124706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF%2FUK49Rl8F9u6dnF9tiQ7xAOoudcb%2FdxKpTYs6toQy8AiEA720%2Fuit0TyP6FlvvkA7UJadz1hslxJ4ZTlLmL8qqPqgqiAQIvf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIh06j2gzH1FLyuuryrcAz3rrmCP0FBizTfRaktptz1ueT6bNQ3ZZXre1hFWowuuE88VDe05I9PuJHPyPj4QeBRDf5K3ljEhw6bqHk9yLCkj7brEaYW3EhdWmSswa3EGT7LdafWkALpbqHJlf7rgOLX8CuMX29QDeqhX%2BsgtNg7mV7UdD7w5zt4uto%2FfAjO1vIaG%2Fc9KQO9Sw3YdmTvCivBS1soakoZio0YF7QmG%2BasmY3lwHXfpirua0Pk6Zi3A%2Fusuq6wyquED3JwP4DJw8fs8eklYg0dd7Zijd4cPog7ByPeTjrX8%2FeOKz6Radz%2F01zrSjlrsdjcHDkshBlbGOrC6yPm0Zm5V9vK%2FFruD%2Bgsgfv41T3DHEKV5rCaxDOPHlzGzkyu0gMaUfVJFZaopttPhDeAcvlN8ro%2BSlGuSg2Ga46P%2FM%2FbISGhZXAbL209yFD5GIzgTXdsc6KAGlPLWwxSTgxynt3yYArsTOQZhjnFbM2s9RHkNML1gO0eChP74OBJ4wSNUdVdQN0Y3AY6gPmMJU8MM62KaPGmy3k9mZlumS%2FDYlyZbRjnAJ%2B8Zwtboz3NIYaHYHM%2FKQCp0E%2BnQ7MioSWJDfYBYHG1Gj913PqwTLaZVue7HbCnrL3R29RCeq7rVnsEOj8HHYKmfMICt3L0GOqUBv%2BlB91Y9pMdL3pPcTEEBFlteM8Dzd%2BiYslmQtW%2FBVdpXmF0hzfH6yV7QwdYiY6eGAEacuAfjTdiBkWfKXy1tO11xcCIMyqfWbOSQth8c1%2B4AiQKSIs7PnGOfI66Q%2B%2BX23PJ0K57Z3rALawGGFZKPI8QxItiX62Ck7PPLKDfJeuR%2FcOhTXKGx0Hrn8vx5nOW7f4ROm%2F%2FlE5W0Ead18zgr8vsgows1&X-Amz-Signature=97c56eaaffdada02002cfe51bc1733e021e49a008eb281c4e587605cddb720c8&X-Amz-SignedHeaders=host&x-id=GetObject)


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

