---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466STXZY3KI%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250211T152732Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIHesTkq33vPhybTon\
  KEGPGAQ9fAEF3Q9Z8x%2BQjgWGbk6AiAo85iUupBM06ijqNJQA27vvPpQ3XoCI168YlU6ac1EwiqI\
  BAjY%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMxsVUe6vWyXgF6mI0K\
  twDovvk%2FWamNI28Wdg3%2Bc6%2BaMPfXstA0BbIZ3lcWt4bX6WGjBqvXqbbDARTohh%2B%2BncJ\
  qbiAXck2M2PMfkhYgvS%2FaDbgkzTaPnZiRjYEbD%2B93GkJT9W0VnNI4YH8K4yx47c56EblaI3%2\
  B%2FTA2CnFrWkI4ZvpgCX4bq5PYS0UEhp%2FOyk0NG4qpmf1dkclLV4WbkfIeyKYmnpWVPh1voyBt\
  8s0OOnXgyMS%2Fwl1MkTz0g4SryVS%2FyVv1KXNu%2B8jvAvpAtbB1tH1pDiG7FDJNbu9M1wXEds7\
  81eu6Wyv449IG1Y0JphnpsJCbR4JWtcn6TZ4XWI5a0wh43wjIxLP%2FEUt2A%2BhkgVijl%2Ff2R7\
  Wnlg0KaZAaTnYO9vOudIppORs5fjITdEIESdl%2BKQEgu7Q6r1xDyfFlG0HoktytHvHXTa2yd4aXD\
  1IN1u3GUg%2FzrH4MPMv9Ui%2Bx2p4aR0JA9rRLxTR8IEbVMbnN%2FMSnNqwpU7curBMLhvd%2FCp\
  omG%2F%2BngWWNEUM0ohiAdm%2Behk1qmoUWXQh0bBBFvLtsTSDgvVfHPzVDvgBFRPmHt4u5oedUy\
  wLTGTObWGNHceQ0723YkKrtzbCKiPrqa9Fa9RMyYYxTBH62EHxDUewP491PQCFkxvdy0qAwksGtvQ\
  Y6pgFQY8nsLlmNdZbdJlcyqgTOa1hnf7QOXffgKIeU6xi3cyVwe4ZmQZFcIt4Wlv0J4ZXoRTAQK2y\
  IrUT1nP70ibPml8dFv%2F7k8%2BRaA5mbUIVwQOctkeUwGc4t53pAXFGmoQZlcCAS%2FaD1A7hCQe\
  h7FzN%2B2kvkIMOMDLfk2TdN62atBINxfjilZ5YUaO35d5Q86nXd%2FlMWMxeLv5UBZqBOLw5WaUm\
  %2FTFB0&X-Amz-Signature=1495f1b541022164e31b44b5855fa23c74675ea4bd5278bdb9611\
  99b27196dfc&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466ZCBCIMRS%2F20250211%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250211T152544Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIM\
        EYCIQClFK4VQeIdOFQB8w3nKAwlRzhkiEJeKtV4q4jLt1DgpQIhALjXE5EFaEVtciKU70IM\
        ukfLmDwPcrTVcFN3kTuJYaNVKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM\
        3NDIzMTgzODA1IgwLavhKxrhoJFLR%2F2Uq3AO3Q8OMmsgR4WCPmHLDZCzZmH4uAWOTH47S\
        eTzgSDwdi0tkf6uoNxmoZzRsZfKlsQkJUToVSNFSPiUV2YG9wvzmvYDRdw5UhUveWnl8J75\
        iaEUdPWkrEJZYfWqsK%2BzfsCdWf0UN8yPZhNuR9inI2nm1QIYEnfi%2FcLOWAH7d%2BnI6\
        dXORONlM1G32GsGUk11rJsm0UhM5SBFmchpfmBwDri7GLTJTcyzAMSGEUKmvPxSr0iOv9T%\
        2FJUtTgxxR0CV4Z9unU4SCjv2arXcZAg6BzapsJg5Cy3WumvvrMkXtjatBIO50JIZcGItLv\
        HZwOW7icopAZq%2BwF7TJpq2Kab2t5TQKygLtqdo5lRiKQlu1arLW6pbHlSMjR7v%2BrFfI\
        ryRzcTqR8jD5yGBoCLfJn0iUR3feYICgHXcQFpEg7q9zWrbhrzP9XmXthFslXusR1hc5s68\
        EdIFu%2FtAwiSTEugxN0fvO%2B6K6rnjTxbCa5GvfylrS3zeZFuP9im%2FJcE1H81SHSYES\
        u9nOukcM825LA0UaU8vM%2BZSA2U8preVQe88Ky6d%2BNRiw%2B7ozKn4uScUOMLFBXde3o\
        cdSoGMTmWGtqQWfokv4rAccF9CMOegyVtUe%2BKTt1PEf5GshOWNz8lIyWvzDkwa29BjqkA\
        VJVoOROMcYQOSIxTKzjSPYxfeqJOCc1Q6EymoFtMydViTBiFg2IjqyrEtGRLuVUSVR4A1jD\
        Ch56yMA4u3Gr%2B6KB1cJUXbgv3zOluD%2Bbp3d8R%2Fa%2BgYe76xOXDrLhz6mv3N3cD57\
        S5Gar%2BAelfO3jd5rVaixz0jUE9AWfuZAeJpbSKa%2BXOeyS0MlTd%2Fz0uabmWNeLQVuJ\
        MoYwf0mw6C1Ze99gpoQD&X-Amz-Signature=080d71a2ae0b09df2bdbf08ef31333ef0e\
        52b3651d95e6ee75973aa862a0e32a&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-11T16:25:44.476Z"
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
UPDATE_TIME: "2025-02-11T15:27:39.651Z"
EXPIRY_TIME: "2025-02-11T16:27:27.775Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=1ea79be80337e8c58b31bf072c41716bec828a989ca68e514e918ffc6e331362&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=ca2dea075cb5b2c85a308db65941dbe0e99cfa1c394fa2ca5bca95261eacfc69&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=2b834ee652dcaa5b7783bafa44de0ff502afb82760d82cfcb74b44aac046b4ab&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=408404ca618a490a95b83002abd87f9a61cf23e44a826fee15fcbe6c340d3b75&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=52ec45b8b6899d0448856650e1a68c493c32fce02550da2212e1b6f820dccdff&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QN7CBKK5%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDF6igJdWlp21gTF%2FvDop9WuR80MbxpU4IoeQTQdZHDZgIgKK62dukkii3d821AIp%2BHhtD2j8H7n3Ea%2Bd5bkCW1BCsqiAQI2P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKOZAnCmiTLDDeTojyrcA7b%2Ba%2BWImipiF%2FYthiE1Q16j%2FQtKFvtImo%2FJKO%2Fqq1u%2BismUHXzgfjitz3qD5MuE%2BGxitec9wZKQdMe47WCLcGFV5DgQCqU2NfO0T%2FmMcmOnZKfhC0V8qMUXbL7E06yvawTaypw5VD1YPuMYkm%2BH4UZPdK1tXrTo%2B5SF7GgBjb2O85DMLUoswr8EOeSrIBYehxySMvVlMT5O2uuvIIMNoI4kBc%2BABOYIcsWATmnMTEUIS6G0%2F4NzruYzoa2rbV%2BvIG2sHbi%2Bn%2FjFMy4v0NvhF%2FzdBSmFSDj9alarnORfuXoDgdU2qgQs%2BhgUVT%2B2VuIiTeQf5EIT%2FyphMeS%2BgYxdnoaGXIHExHyYi%2FQc2rgb9EMmvPc%2FYm%2BV8iWh4cJZ6xhZz9sitk%2F56P1yPmwNJTNrNB%2FeZiNwGfYxuVFRkQZKzI8Jree7tbNkfiV3qd9uaNCj9%2F1cJl3cIwN03Fwul59sT5PyNEtki6911wo34KRCJA37r7cvw5fySJKK9q8arNRqLUcFH%2BwYTOQNYdOjk1OpNMud6Zvc7xBv%2BjOQdkZKzdKgVcXtsV3VAS0oGAHpocTBq4YpzbgVQHA7JWj%2B9RClNuI57342yBOQrqE98adzqejTI8aCFGZO5yC0xlTfMMDCrb0GOqUBKQab7UMplwLmfXxCJsbHTARJcRJwm9hf6CCd9Ov6Ryq0wOo3RduJU7yQqPg5HXObQZB%2Bg%2F%2FZp9QHEtHf7yKQpgvOPe99s8QzErOMOw9ofAkdM89TOEAmZG%2FV7TdQTJV8%2BoTJta24W1%2FHw1N07VXVRyZC%2B4WwXKvvE79WB7LL%2FUausSxqNivldZZwVlusKFXCVn%2FN4s0jondkI48WLiSjEZbOVy5n&X-Amz-Signature=c0aa5092904f5325bf92a08d8d2b59503f76e09d5dddb063dac48b6c75ce0952&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466VT6DFSEW%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152730Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIC35jnZE5ETQFi4uBElDY8QIhJ%2Fzcefu0zXHKal%2BtmuIAiBbG4gfh7W5UMJAnHzgERG0fpChLE9ZPzpNbc0gNmLJ0SqIBAjY%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMHPM5Wp6Tp5eyRH4nKtwDxMNY2GGJmJ56w2wLuVAR98xzZ6GBuzQZTVPgvMhf8fBbejkcVawPohvEMqEGkTgcjyz%2Fw5b0f%2BBhmjSPTsYsI1uEJzOGOb4Gi7DiI8qgIH9VsVGog7vwXGPVD%2BI%2B7bQ1jSAqK1h5xs4znDsmALDZc4Vm9XoLcVaSs6cMLlhkV5R76Ry%2BPHBrJOz5Rmo6Mt%2FhJHXcitC%2BbmnoYtdjmdst1jMzdQNv9slNrksqK7mR%2F%2FB57PICtRu9fG80lCfvRSoD8GpM8zJpY2Qq7xV5ztT8ypH%2B1wuISzcJcdjgpZz9H%2FsPCqt%2BAlIK7gclpFTO0P2j12EPT%2Bbp%2B9oW1BmUgAqxvyCcjHy4iKNFX%2BlVFjbNj9aZgVISYK1lCWlaz9mN8eysN5%2B1uY%2BEF5lKZy8rGQcpyd%2BzKNi1w%2BfyMvKIuf7X9EU%2BDhhOEqITUv4AuuHYSKWRfrPUMBVxuzm4icUVon1Cnqlpk4PEglvklsPDLiR4%2Fsvcp6%2BfIdGeH6h0X3f51Y4%2F60DByvfuPmV5t0HV38zNV7gS6YXG0kQkktKHvAVVKaPMLfWf7s32r47WUabuVhw4iCkoDCD7Is8ZreiBrIYkJuuj%2FdLlsXiTHA3FwGNchJ%2F3UG148fa%2FN941QiIwjsKtvQY6pgGV2JeDNvX5fC35r50LcqmhD5655Ja%2BJfP51UHyAXV6E%2BFA9dSWSQ6TOdKbMrh1vtRlbD16x8dQ7Ti63j51245shEXBGHMmboWXokU%2Fr9RGbSCznUWmkjwCLlfKOmnkLmaRkgZA2wIa5V5Nm1NuqQM3XPZdw%2F%2Fe4iLXXuBa3Df8vwmS58XOa9fZVXkhPeVayWvDrf8dXlOJ77WbblCo7mPt0nA%2BUr4B&X-Amz-Signature=da396a087965cd24d2d1a46e0c50a391e88c9b987bf9ed677de7d0404be19ef4&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=f1e7c68e9ddf395fe73caaab1112df31ffcdca4fb6993dbd9b959ac0de52b5ff&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=a91a7c7e087f0ff2762093341f76b819ef04cc16d2f3315bbe9e604289a71dd3&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YYMEN3SS%2F20250211%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250211T152728Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCLWj3aM04c7usqa1FHHFWIIDJbrtbnhNC%2FQVHhfC5BpQIhAMsXn2uY96A%2Bfrt2lX6bPtFk8MFGfpAtSLHSFa6bugGDKogECNj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxYhdK7oqg355Sew9oq3AM0Ks9cJBS61GIRbFEqtd0oTefGujkMArnwva0nK4oz6R6rnvKt7ECSgKJcs2x%2B7K0CCmkDSDqyJxE6PEw1AaEQktvThYGpuIky2zOBql3hPvsycyS8oE%2FZ0NBnepCJzVRMvwCEdxic7IHfrXBs%2FMf5lAjLDJjW7Gjld6STNgl%2FPQ9PfspD64UqQrkaRzn2uS7ul1QPi99diYaH37hJqNztC6JWdlP54NIRh3OPaHG7pm3yNerbX4o8jf9X8oGRS5oscoCbLIdBN5R%2BD1yc2St5XEj%2BPpfVfyF8HXE7EMHxFtQtSrKMjFP07vfE%2BRa%2BELAXu1cPlae3YI864K2euWLynBAFWv5u4VoJSvhla6T78S8HJfLc2gwwiv1v2gj2qNhad%2FYHyf0kfFeriSyNcR3%2FrxzZ%2BwC6pdnoZo026DbSMNa0ZgLYGdXdFrfbOypJ3zgHYAp904snT0WaZs87zLKTu3jVUlYdnkoKCY7RP5%2B2OoLLNNHJcYlUTxmq3b2ma3Q0GtRI%2BUXhP%2FIH0Y2h2bJaqaddFBW2ELHGfVQH10vVOnSbdPBcNjShefdpTHt7Oa60i6CCuGMMFHQfeSRhh9%2FF%2FHGbEJCBgzl6x9AOg%2BV3hbn9GHQTCCG%2BC17fbTCTwa29BjqkAWn71eK1hZghGAMPu%2BUjTpK2y80TSNiZwWrin54b4RLfAU73tRTZBoFx2gCmQ4jteL86mVmfBmwV%2B5lX26tDi2DQD1LSP5l6SIFSHhQnH2eddjR6%2BgaSMuBPxSePUI4HoQAm5IYrZIv%2F43Px16%2Be1DNxyryoKBSsvALHhRWqPUqTjKCKtBQb2QspbsqV%2B3K02MLrM%2FwaXOrDuW7I6lPNMKkQIcZS&X-Amz-Signature=9dea84b155b981290bc818de8fab988b135ed69682d573d75e34b885969ffad0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

