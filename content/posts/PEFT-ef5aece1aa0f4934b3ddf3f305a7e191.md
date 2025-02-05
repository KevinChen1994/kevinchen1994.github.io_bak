---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466RI45SRHZ%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T025154Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjECAaCXVzLXdlc3QtMiJHMEUCIB2pPXR7V6ilMWsiCLOxUoJdT51QlPxlnZDrnCTXnWucAiEAmlV\
  TMq5hIqbJC8pZvunvuQWSFwi06tA1O665gUQR4Isq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDEz7my\
  t%2B2P%2Fxc0VCdircA%2FQNRixktpcMWw5CjDZwCv1MtwS7RIy5i6vLDsBKVvSGqzTaAqRPL4XM3\
  5sbolRjqmRQKiOcPe%2FnRcJaFEP7VIveA%2BC58EH4fyHRL5vmR%2BSw%2FMAqqHvnlzAlN3mI%2\
  BDYbEyTEACN0d2hUoRTazoxWzBYeFoIUotA3iGvFPwxb1vkFwBI%2FwVawDAlHBVuT2rMqcGVsRwl\
  BIP%2BgrQlRFhet0vz3tzUeDhQLYbxDL2GoFtG4vnuCfnaBt3a5dYZ2Zqhw5k0MBH%2FKuuwgfFLK\
  NZ3AlztdYvbEXbzVzrxTRNyN%2Fm0B1wMNlb7oIcc%2FGGlJfp5pVGR%2FqFt58kNrvycqmcVz9wI\
  M%2B%2FMn00xpsqkBkZwWGAbLHnTgoOuQbvH3VkUMuhycf4A6FxJEb79tGxLyIIJ3DuDNtQXSxpDc\
  jTEVfs%2F7tO9AnlA2XcFsuGDcztmLmUTAfnJv9R91sBNL9Ngl0vyXl5152whSlnLAPjZJhFT9CZ1\
  %2FW9n717hN%2BAuCFVOsNUrjYJ6aZH3MHUduEvARULDUQ4AjJJd0PL9Nm90gjsnavM1K7CO2ukyv\
  VBhMe7phTfl6ke%2BiejZ78WKY6hliN8vEzyyfCwb2rp7pVADpIBl%2Fji%2BVA2AqY7Z%2BRyXZC\
  JtsMJnPir0GOqUBf7hPGZjlVBfED7xw6U%2BqyO%2BGH69cGu%2Bd8wMeWLn%2FQJT4qU4tvUKfgK\
  bVOjcCjSMH8ux3%2FnUuZAY2buBAsjp1j4EQ3V2OnrraIR1oeiAg%2FERMC8hV%2FeSUIB1VXZQtA\
  mam4E%2B%2Bik2kRIj8gssywrtMSVVteALsMbqmJnrYgnpb3RhvFGIg76bHO9nZEs2xJftRxvUF08\
  l0oRn6EqZGwtLxp%2B3l74Ma&X-Amz-Signature=7cfbb572d323dc76a17f9fe6b99daee9eefd\
  5112df9614fe58879bd83a77aac6&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XWJXCPVF%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T025050Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJGMEQCIFMJgke8C3Ou0uHlKiTF%2BJmsrq7O9\
        mPKvQKW3nyEoZ%2FvAiA5LKbd5jqtR%2FdPJdMGN6D4Md%2BQ6H7aytpG%2BOFaqcqx5yr%\
        2FAwg5EAAaDDYzNzQyMzE4MzgwNSIMIYmBIVNjOyQV8xuQKtwDnw9mOLZ3U7KZlFHv9dV4B\
        NmxinE2OTTRla3sD%2Bd3xGP4fcK8VdKlx5xTBipvLPQ9XcYEvmzkXLUIApwk11%2B5NVmK\
        cI00PALgASbTvi7QMq8ZDDkvW8Cv1X4jPalmWJJ8cXTlGgrcyoLtxIuWADv%2BLbm87rspr\
        mfUc%2FJFIKZEF9vovF49kNgQkJoNU9VC5WWzD%2FM2DwMsBctxAANIru8KtHpRjkMny0vW\
        LBo1KcEMhg3DI2EPRKfJX8bOKuOdOouLGUKGbgYnw5Cq1uWm4guPKRkncUr%2B8UnM0wZvU\
        nx%2F9VcJvHyEg6YVzhjoOfRM1gkUzu4jLLwDha%2BTfmQvCIn84XyZRCx4fEAKnlqO8Dz6\
        1mU83vb3Wf2W4SRrNL7ayd388FuRdt2i7m7SpKgDnffz3KcqjX64%2FqCQShlvpFOLWDz8g\
        hmuJwmD8YTwPtIf3s5QesIolr6YZQs%2FF%2BTxfMQMYbxQIu0Pp%2B1DybXHj4MVQf%2FB\
        gWgTLkenDtELIYtjn0i3aodslq9USnm%2FHqZC70fyPIdGtutSOZLud8dpwMPJUpRPRn%2F\
        X69idLpCqgxWS8m7ghQbL5ChDRuqMVw7%2FjBp3MYPDZV125NqI1w2IfKG1g%2FoZcg90QK\
        ghvo1GdX0w08%2BKvQY6pgE3NNvQSowA4c%2BEch5x6Pi6LeKL7fvoySa%2FFX42tuyZdyw\
        pVVGBj8a7FE3B0NtpsUSNjCRlDbaYD4hv5Px2SsDgUztixZ74AQyU21%2F0HAEYLefuK3uq\
        j1nQvOTnllKJmlLodywzka5PejJQFAz1OqyLl114tddMCeXhVegrfhs%2BW5bWYdp%2BP%2\
        FbHnBNxmmIUuEg0XaoKNvv4TfH9AQQBNRyQwmv3p0%2Fg&X-Amz-Signature=6907ae7e4\
        8fff9a8690dcdd0da6bfcf5327b14752718f561b9df4ef4be4f8d7c&X-Amz-SignedHea\
        ders=host&x-id=GetObject"
      expiry_time: "2025-02-05T03:50:50.480Z"
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
UPDATE_TIME: "2025-02-05T02:52:01.221Z"
EXPIRY_TIME: "2025-02-05T03:51:51.940Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=378e74f2aa95f402a3f0bf97d4792ea55a621da8df0243fa7742b3e928085731&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=04c500d26a6b93a855825c4b9a55a779bd5bc64acb48fb06daf3faacbb2d0a34&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=c5dffa8de37f7f001896e725ee38b22c6c93cd91e98045582a9358dfe3149cb1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=be976a16459402594bb853dbc8cf10a7fe076a92c4b7556c7288738df3086e54&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=3e70b4be77e95cded3bb88c1e09155d41289ba735adde43d1a936428e938c0d5&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QQ67EXMA%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025153Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDOlY4gvDGW36yN9V%2BtJpw16j7M5bq7VnXZBqGpL%2BhPlQIgNRw%2BlCoNAbF3iRxMW58qddgmutvF5TajU2Hur9LZ5pwq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDIWMWzAoVW2iBAu3BCrcAxUENHPzFMW25foKEN%2FzLzcMeXBHqRyWF4abYLmTXDU%2FGtCYmY43%2BhCzs0lhaWtmkDXfMluM14By8PmO6SR4mTW0AO1HpTJ9p%2FCGsyHkCwmj0BKRNHQamJqkltt4FVA6DBBGL%2FItW6ehNA2PnegLVhEKYByxgimDhWL34qS8%2B4eznsDX1rZt9iTAiirIkKDUHlxL3q%2BSLTsDk4dIhbVMG4nyR7DQAhsnCAFHDjT7RoDRX9vEpUofdkty%2BupoZa8OAxBwTj62jdiO4zjAq3gSlPyZft%2F63WJduObhuCiUmRqykH5rd0HOQ%2FJFXn%2Fmxots74yX5dQr8kl6syox3FUla3ZEnKhdJRStdfQRxfwv3rqlptF17saARSeOLpU3KMUdkzZfAwZIGtbqS1N1B6%2Fdg%2B5dDe4YiPzCjxmymkxLInkg1JuDEo7hRrwvQLy01jIYZQJynZ%2Fm3vF4Ntto%2Bjys9IKUhII1i96Im7zXcGR7T%2B9N%2B0i14j7HE68zuD7YkOrEEuGkzdClD9iK6M8C%2Fjc81Op5%2BMEcn5eQCub%2F5LB91NaUuO7n%2FIjpIlQXZtO5%2BDfUvke5IL6TmJ5Cw88aCO2blmP%2FO5bo7U5MHh9DtwwDmlPfSW7NoNJzQ4mnJVpCMNHPir0GOqUBLSCKXusQh3NSzpzXG87DsvsSMx7fK6XwMnl4mXHYBl2Al4X3%2F94QzboS9ASOiCiQrG5t73VSzN%2BC%2FyUrROAA9roOhzNodLo%2BxJewwGOCI3WOTRTZ3SZUSRCWy483rbCFKIHKV0ve5oF9dffaQeuuFNgq8tCjj7mn8Lt4CWcJ4hShR0NxLCNr7LmnjEbR4Y6MySlq4oJsBgV%2BGFyBMM%2BMgjEhXJiY&X-Amz-Signature=f8936cdf92839bae76d76621cef7a5afa587b40372f29e8e6720bd8b78aa8e79&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RL6TVPAB%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025153Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIBNIqmSUBsm2euMztWTyhiqqesyg5g3ircXmp%2BBWhqyZAiEAs%2BfQ561IdV2uLXgaHcVD0lFpNw3nxEzGsZC4xMXYaNsq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDPNzKh%2FGFfNPRr37dircA%2FyDGNyIu1qJkW1PHMOIC0LDnlLxtl1DNJKbF186LEeXLAmxFCgBV7q2%2BdWi7TyxrzXy2h%2BaG8bp2C8oBSWUom2OUza8RAvzktcR%2B1NOcZj9lzLaKxyVLmXkgWg1BCReUv2Pm8m1w9nmcNwTf9hf70BLYET8zXedwF6Hsr0Uzf7TLtJiwJ1y13QmMb1kSds%2BqsNFS2TCsReYFEflRw1R8cb1ZEgFmIKaokOdFyXAbAVj4r1HzbQlxTOZEE07ljWFwPRo4rTeT1eH%2F7IUDr7qwG3dZOxjVIYNWgtUyd78hn5%2BDeT6g%2BB4BlMxseD8FleB8hMNNCRbYs%2FpCFrKmS0uaw3UL5t%2BR0MZvIdfBGi5FJDBdQL%2B8%2FqEwyXTfVz1kVV%2BJv6DsT1vR2a9bSokNxNMOW7C7gYGu9uknyWq1XofWPGeeHOnKOJIgPMeOspwr6p0VticBawNqCx%2BYSskr0ZgUTtmVI03kEAK8LAzmogPvOeuObdUDzz3sBfottOg6%2BiXEzLRiMfULq2v7TeO71UcbrPI8t3aGjIVeD23sq1svvNnTz3aypw%2Bxgo0FzNaSqhf4BYxNuaX7sbkEnkiLVoNbk%2B1Bi8h3zHMXYtJtKzUIv6Jhkw3%2F8UXYEQjo4xeMNbPir0GOqUBshwquxjOP%2Bzta3O4k8c%2F8%2Bh5JAH2Ru0cDCoWoRfIbSwEju6ZKhpXdHXK%2BrBtWDezVEqCaNTkfaDO%2FiRngpVzA%2FOjWEPkvJpBjbQTIlntyLIPEk%2FhRnXXDxOpL0IgsHberB5WjGi3bjk1CTYb1OsUmHswyzli77cn%2FtjVrjCGyP%2F6sNygNRnnWlDDOHiM7gfZPQHzgYzupsHM%2FunusZfoKCol21Pn&X-Amz-Signature=b57ae86d52576b21df74c6d145cc5cc222c7b9cf4958f67d80269479ede982aa&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=10bad45a9d286d46bb30d9d0dd6567afa740cc3b0ad0523057abea025725bdd5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=ce003b6d5bb88c6be7e536bf8e67b688e2cb23237ca83c107d80bd2a8c1b8e63&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZIAXRAQU%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T025152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjECAaCXVzLXdlc3QtMiJHMEUCIQDR3wy4qPYgkGNLK%2F6D0ddEzkeLQiGOQogcpxZOR%2BRElQIgCt8uu%2BYPNn3kwRgA5GIyFP%2FC9gEyOxpy%2BeXrraR9WcUq%2FwMIORAAGgw2Mzc0MjMxODM4MDUiDM7QgQUTak8vnn%2BeqircAxUq19bheW1QwmEQtSss9jZX%2Bdo4fWxT3C1DYKfa6kQSH8sN%2BBo9bH3ytHP%2F42E7xSQmE%2BHIbW8zG6iTL1bLiNska7KDmq0MK8DwBIcY9dvvgP3eCwssC0m3hxQ5EkrO9yf4NxTteQns4WJ3GZIcfkjtXoSpZ8o0DHzEqYqig1UNtXX5YvMEiW68%2Fw8UhfD2uxnVOmgWu4PFi8SXGoIUGwb5upVtX0Gg4JAPFhHInRy1GPu5zblG8yRmtqtK2A4Tg%2FlPP4sBXKy9tEXusBIb%2FIwgUhgPAn2Olr%2FfOH%2FMMeFX63FrOD0nXO4kYcb6NnpzC23ZfoHNnpCtR1%2FU2S1DWqcpoTVIQeJGM9dZyix7RTiqOxfPczSl%2FXsIbzf7WYqBwsdRZX7we0TkhG7%2FYGg4tXymbpAhwqjxaEUQVygQYymNR3TCc5xMJgzZeGGFQJgCUYEcfb4KSEfwlv8rMIKV6DNUKGDiQ5Wu0gulcyeiuE06RqzhTYgj0KU9EnOfGFKF6zG5S1SlgBtdVcKVu3avOKapbS0SR%2Bup2h9Xym%2FKE4%2BrFtsEqDmwoL7qR9cEHlh11DG0gxhyPQHYT21Jjwd3OmXOUhXZr34Xk30ObGKSa3H3o6rWmsd6LCGG3kVLMKvPir0GOqUB7PBGmHVtnqW%2Ff59MNsXEDbPEYzV5ss56UuV2kKgQv8%2F4gm7ZPX3L7brFFVkX%2FXz7zf%2B6gO96xVLVpCUFR9HB9gUt1r7hH2dDMmXxBlmA1BxiT0HIQGJeJ7BESQJ89bvo656OHwW2BZz1befZ0zvo2tCW1ZSjDM218zFltBHKuL%2BQvrIDXEBp5wasUSWdV0iqiaiYLoUv8U8dpUMkZSvF5JKfgG55&X-Amz-Signature=2a067e796e7d8480f02ce04d1f71127d1ae0186437eed7d109dbafa239a144c9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

