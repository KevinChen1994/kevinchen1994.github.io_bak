---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4665TMUTXYK%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T191955Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDIaCXVzLXdlc3QtMiJHMEUCIAud4Z0XEUTWkNJS6t9ZIEoFTzoxQ9t8xC1NngKvCufPAiEAsPG\
  Z22YJtSksw5ybF%2BkCRCp3Z4CsTMyWuaojpqARvrcq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDEL9\
  demf4a%2B3bMYU2yrcA2A%2Fx7gAGkPBjLbrT3rz4KC6QzORW16UF9Gv4T08hOQN4bcX%2BTfW%2B\
  uEMC2oKi6HWfMlF9jUiePTv%2BAuRkNNeeuoWuuz0hNoRsn0IVWxx%2FVLSAFP1ei4JdXngD8DCKJ\
  9RROb79hZOmHVR%2BSuUN1mHv7CS4R2bt9KaLIzmtyxDOMd3d2a0AYskRHyyO3hPrMRUQ2Djl15pv\
  aFLVPN6HFMFWQcylXIC1Ka3uMikhwEV8WkMAUk6C4NTJCkTPFA44vV5dP5rYlqkztJmxGk6fj7SHe\
  bvxAZAAQhv1n4sm1QPDIcB76XpToHGl4luuWHPcL49dnZsg4%2FGvZO2toBCQAhoH5ZkJAyJ3l4cH\
  CxN3ByvDDLban%2B5EbQatrl45ttk%2FH3iaZJEI7y%2B3%2FBI5INxvp%2BSMCEbP6g%2BHV3RaC\
  lUEMi32J0wco1g8kbojzKO7FrqYEycpkuucRkCeSn5%2F9M4QwvfPUltORl9xL6fDE%2BExhiUzQE\
  oRsFwriQTjosASOHqOm8gkV%2BC3I65goV7x7Jxuc2Qwbt93LmYGUup1qmFxjrQKeqgPF2wMr1PIk\
  t7VOrL3v5kt1B6JmdH8eMw6pGmUNBlOU%2BY6YywKeqUbAIc2FBZZ9g6fGuWfEC623XHJVbjMO27j\
  r0GOqUB1DuTuMmW%2BoxU04LbpCaLKByNWdK%2BfPWRZDRfw%2FEStsLlIytMugJJeoHMkqfoqadt\
  rkHwH197wfCobJBGRZwqkKQO6Mx41kAKH1N9AerRGpYctDxzKTfnkkqzayz3VYlk6Z6Bxl7KXL908\
  jPw9LfLCxPgwRZUVwA77hCDPfaRAkabUC7ztqnXiU8%2FA%2Fvpl2jOzTNIpxmN%2FSGesztM1lBk\
  wKapdZqi&X-Amz-Signature=e7d1375f6845894e8026bd36df0a851bea97f7b930e9c81d60ea\
  df67c2b4a477&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466YFCPTDQQ%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T191832Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIH3xm3xEyT1%2F4iKEcoEr8d%2FDdCZ\
        0LCoA3g7n9U4q0pupAiEAsHlmsqrjEUk5y7%2BW%2BrN%2BmBeLoFgqrMyVtSNqXGpTy4gq\
        %2FwMIShAAGgw2Mzc0MjMxODM4MDUiDGDHCCl8niyRZj%2BpbyrcA2IYI7AeMB0yygPZayh\
        %2FIPUQC3afz8hDuzbw4hh1J%2BeC0L57xJaNxdqrYTzpvjYbFDysMuFRlhGUKXDs2EBipQ\
        VV4bRRz4xH19MuErJu46bp5RSS%2FstBaiwI7532fx%2BCVDNW9og8SMlnqlt1KPUrS8z%2\
        FYkFhrmse3r2aTGwLZc7ZHvVkV3mKvj7fN%2FrCidLRhDQiDSb24hobeOea9YZFu%2Bd6I8\
        w07JIA7Dq28Oh4TdlC4lRFYr5mZ5HAhcQVUXuxwLE9gR52C9uCkE%2FSEV2qBLTnA4rlIkM\
        %2Fd%2F9dMprjPhdbiYRKioJgAps1hgbtc8iA9xs1uADNQ%2BC26VWrwzOmC5Vgj8ePVwln\
        u%2B4cFWUflywTy1kLF6%2F7vH5LUpFdlNOW9KD1BPdPPGWig1zP8i8rUaG5II00xuWB%2F\
        ZhNJMEMe1d0no5mltvPVxxxjv60BWrqyTOoe%2FuV%2FuB9svMTYTtG%2BaCU2P8zQrytD7\
        QJcxJcfWpm7nRGgOGtHx4xns2R3QeI3%2BTI5Q4IUFf9fN0BXyCcKipXzbIYDnW2oHn%2BU\
        DuELl90249fbXhztLXYR8KwdswQjGim3%2FqLYFcMiJOkfrARF2uK3dWGAGqMQe0c4r6JIJ\
        ibpqX%2BNQlvstPm%2F%2FghMJK8jr0GOqUBmK9qBFOtOqpOy3acFUDOWRaqk9gAYlzd43U\
        1ctrgV4Sb%2F6%2BK2jNWhyySJiRGr%2By1EFRpwrTxjPjdX3iU%2BqAzf4Jhl2BP9jFHsj\
        NhXB5gGlxBs%2FIDMFlQquLk6rmnVMQifR9DDcCcO%2BI%2F6T4gL%2BjqlgEqqQCnw86HO\
        g4e%2FPowLRVMrnTitB0ZRz5nKuNGycQzeDGTIKNWJxPp4QGZ5Cq23OJsI9pI&X-Amz-Sig\
        nature=ba6ae5f89511f43ba10246ca998eb3ad52d41fea3d9e2f7f37aad66fc014fa56\
        &X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-05T20:18:31.982Z"
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
UPDATE_TIME: "2025-02-05T19:19:59.373Z"
EXPIRY_TIME: "2025-02-05T20:19:52.927Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=28ba12a2d6b4c209b4c2c85ecb9e0707e1815d3dcdd0d6eec7f5ff8fa57f3575&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=3cc81565dc0fd46679e323656cff40320a1d5c94a323f649719fbfbd392af980&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=8abcf2680e6308b162f0e7d6140e5df5e5297eb00323f80942b42371aacb2a97&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=aa9fdf1ee7ed77c13c55943c342485781b18087da7c5877d9f9f5ed6492a2c2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=8fc4f12a2b9843f9e820800410c6e3a918ba4b511d4689d8ffd85e14e8c48886&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QO72ILRE%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJGMEQCIDaEcfichpyxPoh%2FB3O6bAwZ%2Fl5nipo4B7GAq8RKVw24AiAPS6iCdgx86rq3SF0aRA4l0JhjJS7g0L9VjWvWHDsThSr%2FAwhKEAAaDDYzNzQyMzE4MzgwNSIM4wwsoaelmt6WxvidKtwD533bKKddu8lsty0kdf9cFg4KTIabtJOsUnuMq6%2FQPQOrue5%2B%2BDJzOmx47wtJYBUsLWBLoCAaJf0RpWy%2Bcq7m9cspe8T04i9J8boKeU2e8PSGCUv5m4cddLBmQ2uqHF15wl8khf3VAHONJ%2FqCh9mWjYgR7bQoQhktipqFVPV2jnR7ambR2aw91sa6iM13v%2F57gD4dO8mTBVazxnFzwa3G7XzZAklmXEEbqHyiu9tVunTT3meEGCkDcAjwuVFz36wIKLCjZjTSIjb9TSLK006zeO1ASxFq5%2FU7cKbhGthbPxSW0Yte%2BxDA7IJ4YGFzAQSy2gL6DSv5UFFkrliEHKMpwAW5oioeMtf49%2FGKWik0gQOY1eDqxDvmr6zioKmuTwjOPnnySqZO7g%2Fckfu4neJ04gyXszT6NqX%2BxnaPHari091n3fTNW0W35AyrW6qnSC8AHLBZxjPpxtb6dCfkRqY%2FvMk8KlqjeQOSyw5YX4u%2FCM%2FrbxpD7XkKRUxuWJlG3Bos1SLgSpX%2FaNAraZES78hB2VedVfSfTvjvLMgFXXvEb5PNkocuzu9hByvY49GPI2PeRxQWV7iip5u0iHOvs99SUFl5QkgrJL4ks9cqHYGlKYE5wJ23z4CudiSqqaow17uOvQY6pgExVLCvkpk3HGUQJDdCqbzwQslj6xX5JKgtkZ3NZ1PAXA6ULBhczRyt3ON1npKRH84k6av8buI%2FhB5F0WyGVUbInY0CegP0pZVmsKww5nDszPdmQRNEFt44K1EL4byVR5X1xHt%2BuvzJJxYEMVpx%2BjvhewJ9Nw1GdSGUoQ5C5TrEefr0cgON5xjb1qGGMTs4q4Z9lxXMV1jSWIdptNtBGN41H1CY3bak&X-Amz-Signature=9c7dcf12a99c85c3c955784f6e940b2c025bacd77cfe65dfbca4033983103f9a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RA3N6OEP%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191954Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJIMEYCIQC2ZQgZJw6JQABwZ4a2XyLY7AWCrzlWbGwj1onaY1ebjQIhANMNfuq1BwKVVkGW6VmQF6WgoN%2FDTOK0p7AXBOMFMy6%2FKv8DCEoQABoMNjM3NDIzMTgzODA1IgwN%2BkMF12dx7YNb7Mwq3AP8LhuFbuU03X8WvyJAhUWkTw4c8lnM0umwMUuChaEO60IsW7V%2FsGbCUgag170gFMY%2F87zXohjn75p9GVefT2bAl07nhqtS6JfiemeHf%2FIimUyQl6v21YwOyPA450qE3yqjIjFBRxRw5Uq2Mkfi64f8N0fviQq8RSEoAx7PfSTqFTlgFKx0lhpTOU7cmqiufb1N%2FiRYWYtYoxHkIYgx2xmwdNnd6WYUyQCgPpjAIMGITTzrss7Zn%2FLkNFDTLnZas%2FydiFMN4nS7FGsGDYcOjjv8SOg6tQFmoCK%2FkNu3XIoZyLjn7N5R9ZqLfTv%2FjQjhOMlDGHf4Gs17oymwJrIwgVkTQH%2B%2BcQfhQJGgCA60dEWvbmzKHJ3NIsSloaZIBoLvGPZAk4w7K48Z9aZhWT4Jn0mMox9vIwHvTlgkcSH6vYTnFOK05i0aSRcYzBDkCnM1%2BTYfofzQYpOWSRBLTf%2Fy2OyHMYi94Zz9MwcORHM6vpHbZbc7RHn1gmQpDasYixbvDR%2BNMlfdgE%2B4Cpl%2FWYsEc2n0VSZ9TDf%2FkU%2BEuvZMP3QYX43szev4G5Fz2oJWC69p6N7%2FAioToiHOXERYkNAs7gko3LoRMuFCgWTxEwWWtH12LavhM7U9Fqku3y6Y6zCCvI69BjqkAaIIVXXy9LuIwJzqI1MdAnitxNq71BsgCdPEBNSrDWUybH7b%2BXPTad%2BO8hmcpFJN19r%2FIYBk%2BachvFmJo2U43UKjxpU4xv3JzZU8RNPeJkvj%2BIcsxYMIhgjHEVf%2BgLzIWtXfcrZA4XZuxKnvymbZzc371slDRQ%2Fs566yzrUIKHqKwnoZvTBJaHCEwTNRVSE%2BUYoPILujw3J8yuAy%2FGpi8Gg3GDjW&X-Amz-Signature=d73030f90ee6d9e57368d8275a06d1adef135d904f28f5b14fd8c880b28476e6&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=112a1c32ae3f7e986450b77195100480ab81f27ecc7be7dafe0b305b96633145&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=b6f054acb4d78016fffcd8e48e14d0d9e8b8bd52f7e7c2426e3995011add07fb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QK76S6BO%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T191953Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDIaCXVzLXdlc3QtMiJHMEUCIQC%2B%2FDu548F%2FBDhSZMrZPWudh%2BXyVbnNdZKeIuqoDPl9YQIgCF979HpYP%2BUbuUyRaSJt7xxIupkz35C2BN%2FumXxHLFgq%2FwMIShAAGgw2Mzc0MjMxODM4MDUiDB9k3KeAXLXivC7kSCrcAzDxREdnFJOoqR6exabMFlsdMbwqpahzZE7sdR3gMYBj5grMR3NuX39Wn4SgwH8ZpYYX2h1cPtv5sAYN5bwwY6f7S2%2BEfCqr2pLQQV0Zbd3o%2FlusDDfHY3cjJHVQRefgDW4gGa3kiUpeu0OJ%2FWOWQbZOrB%2Bh8qFwKS%2FLQfSWgOyL%2B8DXyYzAvt9OSTG0i%2BWBV7Fw7URIE2Akkane%2FyafwzYUWy4HMDfpL1uAc%2BV%2BX3vyG%2F7XAiqRKLx4WgRDhzk5xHqpyEsGRBrQtjRE6Xto3RtPJr0hLLVEhJnGkkauFlToIOUY31wYc%2BDUanIFnrjyFJUhH8wR7c0325uiDtQ3lZX6%2FCIEVA6KbWPS0t%2BOqKAfM7IsoHGTk0nC%2BW5YRRgpT%2F2qo4ARms1EKdSsOKNiX9Bym40xa62BJWZCspyPL%2BUrz9VkYopUnLqLfKW3k5MYUNYLGczro%2BTAuarmbCn10PGkqZuaGFhKJfGlJ3p8NTSXkZXyKzJnGaY%2F%2FcWfEjpjMwXdPm9Lkq5xliJTO6dYbnbhBYi%2Bmd%2BV%2Bgph80Q7geyucakAJS9axnOflPJYEbjKng2x6Ao6uULUQ5uQZMsnDxTYcQRTzd6w4BKGJLDM6%2FmxvjrvfwJTUgGv7Q%2FqMPW7jr0GOqUBajOykKzRFgx9%2FPig%2Bj3rdBoDCaKsUEYNTbzPnZS0ShjqDZDvgiHOB%2FqIkDgE6JSenNXSyRnA3Mfe9vNsSQgFxfSTfYtwcSnD1dpfcQ6r0OCpbXNQkZNXZbL1falO7TXXv4w1WPmaF2s0JipgHlguoc8szWFOj01VCOlCPEy%2B1siJdfmPlOPd5ZT8HrqFf2OSSirx19Qnh8WQLVcu9%2BThD8zbtmVV&X-Amz-Signature=ee74d208e5ea0a8515b6609c8d86c4fa78449b0a05757eea8a67f787100ec235&X-Amz-SignedHeaders=host&x-id=GetObject)


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

