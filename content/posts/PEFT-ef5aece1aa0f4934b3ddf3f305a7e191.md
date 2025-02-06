---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4664N6SPIVX%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T092435Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEEEaCXVzLXdlc3QtMiJGMEQCICsO9Rsega1j8z9hCVArzHgLG79giK8WJVKwNJPxc6OOAiBefgB\
  cQsEGHKqQHCXptVdy7u68ypRv%2BdsQvzYdLjyDvSr%2FAwhaEAAaDDYzNzQyMzE4MzgwNSIMjgQa\
  uIZYVQCMJeElKtwDdCd6VEERpmSW1BQigfUBQW6pJ71kt2tSt6gvSjFPryRMwByVHh%2FaWEtUD%2\
  FTUs0YxPqLuQyL3OlBTiv7iyTC0xlXZf5uY03aQTWaYF0fSzPQMJU9bIoN8UmpUZDItbSs%2BOHcU\
  Jkv5jaxI7Ow5Pl%2FnA8lxSaueL1BElJR%2Fi4G7yLLobra01dpA8Z0EQEIdq4ZW%2BRCHaMAcIFE\
  QBZ%2Bej%2BnpNpUyAtNM4ZOou9T0ojW%2FacnAmZG01Z%2BMOKM5ZMyFLW7vXpcTkr5Ze87Id6yi\
  Lq7nqgj7iyf%2FtgpBU66wmcajfUna9ktvMh%2BJU7LyumEbhNTWeONG%2F3NeKaRt%2Fhaw0r5iC\
  OV%2FhboYOh2f7ksxWsMpKDqvzAzWV6WO36dg%2FIkffRVnC5LoqboNbAaiQ%2B9B6rQvOX6mlG5w\
  gSbukmcg0wXH%2B7GG1u2LlthP%2FQCX%2F2cQGtAFtuSTG2ZD8%2Fv2eQB3siq3uJsm8JE4vvPoG\
  aFr434jub9mGBQIF5x1oaMz9Sl4pOYUVF%2Fz4CH5PcbKDLvDP343PfPGpWDKslfZKsuLV%2Bt1lB\
  FmevNq8ACdwDNA5DPnRGPRCrBjhns5Uw%2B0GroN1gbjSzTvd75Zvtnj4UlLtKK09j4rxt85%2FFZ\
  2dz9Jj2owjO6RvQY6pgESA5EafBql5y5I9wFj7KDejA45a7cpFWau1pIggwfMS5EwxYWIqCbipONh\
  Q28IciNUOkUXU%2BcDUQYS4BWsxeitJrtIBYY3C9QC1lzAm1fXY%2FPUqgAb6GWllPpjKFVX%2F%2\
  FJLnDLSZvz8uDFPiCJmxvlwcjhuTUWC1OOeNBRc7vOVMyj4c3%2FFWJUzHlshQd59GcXAy6PSQz5z\
  ILDg%2FMXXZJTjs6GQPJw%2B&X-Amz-Signature=68a2840148e95b4a863f8da73de7439cad6d\
  a3f476889ab064936a53494d379a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4664HHWOBE2%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T092312Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJGMEQCICxrnOLEdw%2FXZQEdSyoMid1w%2BAH\
        c3%2FfAo7jFg1Ul3fC%2BAiACEJhEJzU3qm34rYtnpGAW09Cm4sbKcPJOtqsBtIuPHSr%2F\
        AwhaEAAaDDYzNzQyMzE4MzgwNSIMk5%2BI4oHnRLytQVJvKtwD2zsjYuq3uuO5cU3gKnZiy\
        YgLpcF9PVM%2BLjyErkhu0vKL7DqlFnkNtKVf%2Fri7JhmWrix%2FlCHBeqrq55msBapzt9\
        qZ2JOxrqm9it6Sn7v9QajQRwWoWq1JD%2BPQcEl4jcU5%2B5yeKk1zpw30Q8SnkLqw3T3NO\
        WEMiGqTySCeqRIfF0X3Sb8yUjIHDoSkO0tc2HiBvl8BfHhOFNio10UlOPEThymNxarkokQA\
        GUyr%2FLWbgrS3DToEthZckHQEZbLetOJhcUVoXi19f%2FWtPlhlbBNyS%2BdrL6QszNo6V\
        k4H9ZRw2N7e%2FB5vxByfvRt4YALRTKCGGsHZ%2BUoekQEJpCil%2Fmh%2F%2Fgrh7bcDnF\
        n%2B5WZvcRFvHDHxhREBIEWeXGadYHcpDa5fMiRqRkYY6Qt4nZERm3WqE91nneHa6yfSI0n\
        NU11E3LCk23lMzDDNeuk9pI1hqZe1zJlLTrC5azdwCvZOIt7qHBEamimgITsVl9nUc2XtJa\
        ix5dY1piOgL6olDfEH8r9VGJZC%2BenIUL0h2izoqTffG%2B7xKhMpxaZSt9WorV2FsavUf\
        kBUHBPM2u4oq%2B0idE6mznC2C9vCCc5S8GYGzOkYwc2OO5QDs1fk1PvbCFvUk6v%2F%2Fo\
        hvsPUZcD3tY%2FUwxu6RvQY6pgE4NmgcNpSuUVUBcj02ci3KrCnS7yGo%2FMc0cjh7yMqCi\
        diamtU2drmGJwaYk5wZMpM2wQ6IfeWVDPhiGgCBXNiy6mnqOZqx1aEv089MYaSa5%2F9vW9\
        RaPkb%2BFhBqrS7EqJHCZ6Oiuu0CutYSGPPj5hVPuxekqZo%2FngqYweaBOTJcCtgVVeHb7\
        rspaUxd9bXylNdKL%2F5xRjtDirWzvPb4OQEAyZQD2ERP&X-Amz-Signature=36ca41b4a\
        09a08650d3c0c1b2d8f5b7f471a94d7376a0152f5d3a6cce3475353&X-Amz-SignedHea\
        ders=host&x-id=GetObject"
      expiry_time: "2025-02-06T10:23:12.610Z"
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
UPDATE_TIME: "2025-02-06T09:24:41.967Z"
EXPIRY_TIME: "2025-02-06T10:24:33.390Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=14b7d8a75289e371d7dc1be3aac757e9dd4afe2dc24b838f506da257682fc736&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=b7632b18c27201d78dc8c5d1cce768d73fdcd8c96ded6945b868f64897c56813&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=329e2c7f7751a2ee2d1e95d30f6574a646cb8250d8c832963cf8817a68694664&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=90ad19c071f0a65ad3ed79acbe30f57f3709470d38fb38cdf67b208863eecaf5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=ccbb8619b2cc94c97da8f27fa87143bd97875b3df6857536f7cea360fd92c822&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WLMLD74N%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092434Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJGMEQCIGb4IYETpg5momCs0oziuw%2FeFLL%2BoGu%2FhI0X9wMKzKimAiBUFpr3xyr79TgpJW5qaMYEQCTJC0qwhpHmrQE9J5z2rir%2FAwhaEAAaDDYzNzQyMzE4MzgwNSIMk96yMnPgrAckw2s7KtwDE6ZTVSHKLEk8%2Bqm8Z%2BH%2FCsvTVBe%2FWvgCN%2FAHFB4pVKX%2BIG7cLVKB%2FiA2G3k%2BtdECH%2F7X0%2BzMCEJnOCUuldHNmblXzd%2BYvkyjzjimrYyF8kWGn0ExxHfHRuTK93qupLENEPtkI359YWKDpGh2UBTi5j1Q95vYQOxVS9O5rO%2BlQgMhdk6fusMzAcph18lsW8om8t3fKVK%2FcM3mBUHnGPLaJ5WrS8TBMXfMPutK6CuEqthQX%2BB%2BiTrWrAU2xD2XlkXwHBxNwRfVljA50uiVxEJuqny43qxl4mddasxk%2FAueWKOO8edAJ75GBCNKaKDUl1B1o9Q7KPxTLvvsCqoD6tREssw2Ox9FMAg93rUkyA5YCRFdacWL5mTLrXPI5iING6fwHRWDyxoVFkZA%2Fn4WrBwEqga7a2QLJEv1EPPrbsndYBM31rqAjJcaZS4UTUxBOp3nXBygvOwZG1cCDyOw0k1jNjGK7V7FustuGW1%2BX9%2BwqOR0m6%2BI%2Btb9TThfIPdm0UW%2B%2FpHCIe6M5PaxIGEcjorbuP6AK5gzQuv9z70Yi4N1Ks5hhM8ZicEgprGpWhvLjzKXo38m8%2Fmj0winWL5wtBpgxupYpSLGM6dyfzN7QhcbS6AuxzRtJh1qOew%2B434w%2BuyRvQY6pgE4LJi%2BHbCQCtva3jqG23%2BRJaCQ7C1wtMSbDtat5%2BvwK2ePXHEDMqblNqsBVe4Svd8ih6N3%2Ffs%2FJc8CyuApsPCszULvwFs8FkyUYsg0s818P9DlrwD99H9DD1uKGGKoPRC%2B%2BSLVwNi8hUCU16fqsUOWQaxuwwWf36Cco2gOtbgCB0KPa5JSg78VFmXtCJPAoFi9yWgKilIjupckXZi5lhwIrZ4%2B2QgQ&X-Amz-Signature=3adbf666606e6afb34dfb95e6153f4a70cc855bf96e2175c11ce755d066081ca&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Y44B2452%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092435Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIDFfwsl55qky220D7DriR0erWpltiG1vIv1texe0t7O7AiEA%2FcNUjPdSaq7N5p2TSs5uivKU%2FOpgKB44%2FuqUTVFC%2BC4q%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDPFMB%2Ba%2BFau7tMrkJyrcA%2B9LXvo1NVkMWe4GV6PgN4coRe5PMAx0TwCLYqicjijsIQrLZ3GE15tJDaPfQOkqFquQS95874OaQ6TgZzyYtlYBZo8BI%2FgLgcIY%2BSrPzQw0iMfpxGb6Q40qdd9tMKBKXAGMH%2FGsU9gGEEMB08pGRGWIbyLX1qkiZqncb%2FcwYRnfiszwMOUfDsljlvDrwHLFqNklsUszWLkeN8x%2F%2FP9FSLpy%2FqIxzGPHQeZA2vX%2FdrpHtN9S2%2BD3UpBIzrrKW2sK11sueb3%2B9q4aS1bQ%2FcL2n7hf2ZWPCLP2rOwAOpXsljvF7I%2B9z%2FK69eQ8RqAU4dXoC1ItGHG3nAf3UsOVdBx18F4qdtOkd4hsOAxGhR4l%2BAOkkxETzM26kblTxmWzlsxyV%2BmNZHCsf6Par56A1oFAA0FbWBu7KavSON4kMU0B%2Bb1VUtARpa%2FOVkyzjekmuzmk%2Blup9bV4lNWe9%2B7oeKUObGT8ukntSwBX%2FpCsLI6FPcDGgPmCjEMHZJuEOHBzIwsf3YJPSyyUsHwcDbGzjyeT83eQOTJEN0OMpLP1RnSLj8B39a5Bl%2B1rf8uoAxuYzVl%2BFzN%2FBu3aXlr2Da3Sz4ves5h464v5nCKsA%2BKwy0KpnaLibZACmmDoFeEehM5pMI%2Ftkb0GOqUBQpJUWAhqm8gRGv9Mg6HWLiKSV5X8nr2sc57oGBxKOp71pflUXy3JPj1eZ%2Fj0NQN8esJsQwZ311T8lCbbZQSAwjAHz9%2B9KSmO52h%2BhO8ZXJUZ1lM5JujBggt0MxaRe23S59k0fcxclZqMtUU3j8jbkhi%2Bvwr8SeofDzWTOgCBSaUvs7%2F9W708iK%2F%2FgNFdwhgoJoqHHkLsBKCCZjLvzvN91IwGxYhz&X-Amz-Signature=c4cdaa0a32ebdb78bfdddba44669869c566eeae87363f9cdc17d974aa648e5dc&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=31b5191ead5cc89c71904d854b89ac94adff9c253ffcc5f76370ad5a4581d953&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=594fa193de90eb777ca75d2e858339f552395e2a4ddaa10fb3c532bd5799b1b4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665AKHKSYC%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T092433Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEEEaCXVzLXdlc3QtMiJHMEUCIQDga%2B1DGZpCXRmKoKObZt9Cvl0Yng436oD3f3HkSD%2F2wQIgPxSIX4hy6lC%2Bs4DZcn2GgVdc7TAsX21Td2PsskcfPlIq%2FwMIWhAAGgw2Mzc0MjMxODM4MDUiDOrkRKotf7z6ulomGyrcA9cXJ1EBOYW%2F26HWV9qlrXCjmeMjqUPCv50ydKLhn%2BkcoyQizpAV8J9v%2FkbK5FPC08i8k051hDr5htJ%2BzUYgVzPDbWLUFaRmj%2F6TrcNEn80sILQRgHDdt%2F99jqkgeeUp1RRL7GDEQwkgoUtXLjXHUtpscrz5%2F5h6aju72hHWymmuM2hYHf0aa%2FDWtqMPEoENtvPzwVw9zoIMxxx4DnPpfwjsTtH1R10tybGt5V1wuXZZuj2V%2FlWKAw%2FeaCExEh5wdRQ8sKktBTiX1ipPhFnNDQfD7YCXQUhe7IiyH9M0hh%2BmnemelzP%2FuueYtTRuBRPQhmoKlUwGPC%2BGJgQZ4%2FNWo6F7Xvsv%2FI8BNAGkgK8L0zo98soNhgnIdRBhwUKLFZ8FqMLxF2jZyECEtsDVpyxxKmeXBnKp8AE6qqBcE2fJIXvwfxpXUlrUoWmliTQKdregA%2FXzLkqzKJbH01pqIylpQzMcFJ%2BugVrGrSuXwUeRMXO1OTrXxse2M22AMa4VQk17lphifHzupchZI%2FkbkYnfuoN%2BJMrNvvexA%2BmuYGIEkOC%2BL2NbRBiNl%2B6pOzugVUTot4O907nu6okQgUkLkpj6aGXKpxiiQ1cBZ%2B05VC%2FtKrXTSwM%2BQ5lwxZ8%2Fq2Z%2FMMTukb0GOqUBhOhYTfTM6C627B2uQYOKPLCazOPUr432foSdaXZatxsPCOENoSJxO%2BrFWJZQAHrmN3dqnMDGemvLshD3ueoh1j56vlceQ1%2Bs1TjyLB2Jw8PeDr6jVnEBPeprMa%2BFp5f3n6Q0IVNP3KNXs%2FJfKzroffAGz%2BXI71PygW%2FTnJ%2Bw%2B1xLcnfHCwVlimcgJF1SLfw%2FK9gATzdOxivLShBCmDcPZXHm0FSY&X-Amz-Signature=b2463406edbc48dd79eb52bd28b8cdcad4ac02339d8d443102f29a2716baaa4a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

