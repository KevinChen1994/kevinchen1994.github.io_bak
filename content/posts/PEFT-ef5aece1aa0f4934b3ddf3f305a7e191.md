---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YDQUITFT%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250220T132947Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDppBUOAa4ahcVHB431\
  kUkj%2FG4TUMOmRH%2FCk65SY4uGJAiBz8%2FE3jgNRz76e0uMiGJ4CgOBX6s2rs%2BpyE5ezeJq2\
  5yqIBAi%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMHo1nW0c8I5m\
  60fW5KtwDjLnhjymxTp1aew%2BEwi8RZTi4IJfz3TWTjQWLAkEnAlsIf%2BoJBm72vranrvILkGeV\
  WMIOcUWRzWW2WwPz1JBeYvsHavbToS6rpRksOVEZgtVwWQ8hqGlz335Y%2BDMw9H3Sv2es5OfxFRU\
  %2FfzIS7QXZemH%2FBp5QkrLd6fmdL1ZIZFTbjwiP8MJ6jDeRVooCRNbR4Tmas34USvvmRpkTMe2q\
  BggkU5gsLJVPJsq2jvalaphNCeJrXPJ3lDxzM8uBvF6GNXEaDhEk4CrtX%2FdcbsLw%2BIU0UyP2g\
  ZRJ%2Fe1%2BH%2BMcKipwx6%2FEsrmzexEBkPhA6WeTMNiWHfUCX8D9%2B17QrpQT7gyMTPtXcA1I\
  aN%2FvGedZxhbwg8gQYvnH3MvE%2BzGV1QU9I7%2B%2FGUvXv00OKXv08pVWDR7DVcx1n321ppJPE\
  ysquOaizo%2BeRw%2B8xeyKQDlpGPcOryejvf4K7YEKfFi4Wiot1pOG8ABSICkjGYu0CdGV%2BSv2\
  %2F%2BVu8ug1BPY4%2BPGHyWbEGlWLly1LOLPX1lCB2WmLn%2Brk4vnzSCMNH2La7C%2BtHI6xNUf\
  yEBHwyVZRRfhC3hpfvLFxfXzjlviIj%2FXijKpMOuLAXG%2BrbqWVqk7NvmRZ8YmP83l0q6hVaSrY\
  kacwtsvcvQY6pgHTTTWTcnY%2B2HRWFzfB81nlaOolipHKoKzUkSxHSUflh0gNVj9dhsrlyL2iKay\
  mIC8yMLtjfZ5OxtXS7fmleK%2FWPunYf0F1ZcxdJLxy9xNmc5Y%2Fy0MmDR%2FXzq%2FgVUr4IjI1\
  o0tPW3EgyEb6SpT8Ig8cRhAWNWQS5efSNJUjrM5gl0W%2BP5z3AnRWAOWfQglRhpRQO%2FZyNTG65\
  5VoKQXqXGQtgaORwVWz&X-Amz-Signature=093c6dd3fe50a17445d280c6a2ada0dddc9a3eb04\
  6b3d6fbaf6028e79b8b62bb&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB46672TXANMP%2F20250220%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250220T132826Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIDH4ya5%2BpPeQUfwh%2BNoHqgs8XC9CndQbI7ZztVgm6IHKAiAbXxVPF%2BhEK8grMpbH\
        i8ZykN%2FnY0wcwUZGF8P0KS9pTiqIBAi%2B%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAA\
        aDDYzNzQyMzE4MzgwNSIMY7Z1HXqzRkHQCDSrKtwD1Xrg%2BevsNYTS8WHFzi3B4F3hJ%2B\
        z6r8rygyZxIwSJy6Y1cg4Jcknh8h2lXrsHGUFkJSZrd5pVinRM8PKy82BFE%2BNPOdLTb%2\
        Fzmi8h7ix62KuWkHDwZLXzJhshxRM1R%2Fb5GtVLgo%2BSzp%2BATdq9QArr%2FOH%2BZho\
        %2F4Bid2udaw2Z3aT0aIUigcHrUacP7RgT%2B6j654tavidAxROC0DWC6BNVUllr2tfvWmW\
        pGBAX%2BkMYRDgSu%2FfBA8DDUZlhYv05bPLiTru2O18Bk%2Fuip2IFa30wyhNGzU9wRgiv\
        Rh77V3CRnah%2F23gWWbWy3gKTpcje%2BciPSGt40vAQUnMFjH4Dt50HqaPncsJaScpjoe4\
        3RgDW86mayAK5sYV8oUIzWHfCLpUMQsSAXYwe%2FmLf%2FtqWzoiRvOzfA9Cc9fjP9Rt%2F\
        A4BQKFxG18HWsxsXYHTjEXuKaBOb3c49zxczm1i%2BuymjZJ33569K1PIvdy6xJse%2F2C0\
        A0U0WeFop2X6%2FcuRi6NcM5dn%2Bh2VDt85Bjj40ogOiBMJYIM%2F9Kx7ucU9bPMHwoiz%\
        2FFwNPRnG1qfkGBWRtRIOETjkgZsgrysqm07YhZ8VcClVb6%2BuT6ES0k5h7opl5Au%2FQu\
        9cIyqa9ZXOdjId0DbSYwwtMrcvQY6pgGwYLcE6A77c2I8daR8GD6siMff4FI%2BsD%2Fv29\
        JNVDUFp7NAs%2F%2FLIxiIWIncZkieQqT6Src4%2B5wXXzG39Q%2FX4TJkj02j2RGpse2pO\
        kKicjGQMtGEiFRf%2BkrxK2ztlSHsYpJKbz9b1TO7Wt2fsGlLRL0EprbiC5AHd2W6JGGtEL\
        dOgT6%2BjnmewRn%2Fdppn9iO5bCiFlpBxYuPU%2B92%2B7snC10PQoq9wic%2Bp&X-Amz-\
        Signature=f9d14e487b23e2e8f735b051a2d64bff1b57b44290be1449b1994e760396b\
        ecd&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-20T14:28:26.308Z"
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
UPDATE_TIME: "2025-02-20T13:29:51.204Z"
EXPIRY_TIME: "2025-02-20T14:29:42.135Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=c004ab06ad92a8f539453095dc3278706028884df08ab348b49acce62abc027f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=d057fe99d6217ebe194038a5dbf1cbec76f71ec99f87cea1b68f4068aa1efad7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=efc0a9fa7ac26e93651cb55d5bbba30d3336c430208eccba2eb720222c768fbd&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=57e4cab6759c89486afbd43e187e67edd880936387213d66ae884e075f8e92ef&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=1416fb9f4bc4f3b2e42e736ea71deb5c651bbc2767b3263268c0dfc27db45834&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667OA4BSBF%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132946Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCxyTbuP1OO10i7VUjxLQG2XVdZ40YQ0g4VxHoPyWCGnwIhAJEJLSfFZi%2Bjf9Y1XERULmDQ7MOWwSKbTHzgtfYR5EDFKogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxMZK5tpLmOjcufECcq3AMl14F19dAvfLrumPZ5ITVT76b%2FjX1uElXHZQB1TPGYBulVW79zXf7N8213azWjXH6Q9agw2Abu9GLUohCsmH9xxWJERyw2JIwenDZ4lQ7F9XxIPpBpcL7CNf0gY8ecXnahuAgLiWO8gGi16F5ynzvjiMHb4lc1T8%2F4PpEj%2FKgwc%2FvN6sYkXW10thyEnN4re5Db5wCe%2F2UJRvP9RltN85J%2FS495361oLgb8tV1L33LEike1iDPZ07tqoCrL4lgyVJDRVqOj52N4cFmsbVJR2wwWMqSvxC4IcDIfqrY1xhb%2FRxUYX4qPbQwX2ufst5EdcUy2GF94TB7pBJ3wtq3nrb2cqgjiZ5TZU%2Fn%2F3fMZg50EGb26%2BGs8io8BVc2oZVMcyVbqCDl%2FsbeK0laopFF5x8RxdziemKCpO6v7pBGTbS4YAb2kAKr8XCcLbodpekhKIzKRQbgcOkwKs0MTyfja49K4eywkYDQYF2bL1fda3xZ6jrukFSmImT6ToYUBnsCTN5kjeHcL0itHD5agMKt%2BEfddm4zRwbGZCXPmJb9fKVwCxIOCXhBekOPxUsvFvfZT5a3qMRFlDwZMiLmfWcTvf1PQTWUoItN6GnT0xM6KrhLHM1Sd7r3gn05NmjcCvDD7yty9BjqkAer0eG4g%2FvOwT7PWQtm8ahk%2F%2FOVhr%2FrxIbAb6624ciHdjGwo9V2Ckz2JeanokY%2BhMk6j%2FHaBcZaYwBEAwAmqOqWAcsMDo9Zfky7IfYBO0ieMH9XLSUB2AXeNMHBCGclBV0M8d7pYg%2FgnhM5nUWq8Yz1xXZs22zL8IQiboAGAUNbwpLuK0CaDnfw%2FPfp728M24No39RC5wNeCstIGRb1fqu%2BZ%2F8Qd&X-Amz-Signature=3087a45eab64967a109489e6fd17f24a18002637c5a51e76e825d758e43af32d&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665SDAR7PQ%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132946Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDO7X5xKKtLqAcrViDG1451Pj2YNJ2RsTeFV5p9%2FyiWNQIhAOphJzjNvO7StGBIr9VAjoLD4SxXQqMQ12T3XZ%2BVtufnKogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igx07vOv3nQfENOljs4q3AOYjHfqp2Ew%2FdeLNTBxuMiV6nDi41rLC846XzQnbSRSJLMOMESKpYzlcS0Y2c7T0MzQOAki7fdXJFcqDORGdxCNwD%2BuhAalfKBrTaGdqY0dJeWTYShwXc9SgiIGMJwbr7riExCyI%2F7TlbuL3GWnWeSdm81HdG%2B%2FOBrTAIvxaT2wzQEXdpddcL7U5MMUmvVWAKSgZR9EcMwpsAGUkRLIzOGHB4HBKw6%2FsxrtVXqOPss0dr7Jv8NZieTQeO8McJHrzzy2HUy6mH3dFePcGwZea0CyW1QW%2FmsLEARSjsgsbhecGvMDhFN%2FpQ6T7wDhXv8biHyW%2BX9yQENXYdgHrFwRhl9KGt7VSnZRr0XNTXC6BHuHVO9mTXVID5tjbgZHDK2VVBv95rn3ekTIRPycSQvs%2Fd68Aa4A%2FLVUS3wc9rucWlaFxyYCc2cFcUQKYWrcWHIk9PJfWoIy98hxQg7wxQeDv%2BTUmQj8zTSJFVgy4P7MaLjtZhTvWPj%2BQ2iGvq%2B9nb1sX8Ee%2Fc55gdHZkM5DfIn%2BH83F75FCsdx4edmI4AYjOvNwa1q2J9kwllA%2BYNrBhku0o%2FZzEB89QNq5X8yQIBvqeEy%2Bs%2FaB7unMmMk27I9O4FTvGIOkjQZntFUJfz87TzC9yty9BjqkAcSm1H0%2Bk4qTYIatieJXZupvW11RGR8Ohy8noEH5A5KcJomqIEu6Bsv0Jeu7gSvSLwidbcBIeQUYJXwntRj7QfIOPTiITEwgeVuJ5Q70fT2UDOXC7hGjKl4%2Bj%2BZCceFJUbGR85nw%2BPht87lC506X2hcTVrfXEyDw1m3p%2Bo8sT7jIbZgLQoOnVBYca1HWksxNQHBlzfUGt9Wgwm9%2FbeELDXPFUlWj&X-Amz-Signature=871b443036b75fa053d4a4b1add7d400022e534203bd4e7b4b53791658ad177f&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=ecdf439dedf782fd9b677a9a217afa29b69c3944a29644f9f2c187b3e2584eca&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=1d69e814f54b8a4cbf4d0b29dc7d91e8ac431931e30d04092fdbc2624c032b08&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663UDEM7FA%2F20250220%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250220T132945Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCu1yqkAoPsQtE8sxB1siTAV0c5vpyF65kj%2F0xKgPwu2gIhAJR4ZpGxYELVoLh%2B9kHncoFTkN0h6sPfKmDxBJIHWU35KogECL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzFZhkSG0r5dd4Ga1Aq3AO5SVc%2Bab%2Fnmsi6iZ8p7P5j2GjnYQ0QuyqUev5%2FOxnN2ceY1%2B5zWizkJP1f1ex1NM9gTyINRz3EJTEh48uBhW%2BbTOpfh9DbQozxD83Zdgrmq8z2qvWj9l5voTlhYdrLE6yFmDBeiQd9%2B8L3xzXGmlu%2Bec9z4x25t3hqQmgrdjTcCdFfz3SRkvNPerxFcIthZ2%2FUN8tFj6z7KPl%2BTu1E71xPlCnyLf6dXlCGPyBAMfotg03Tk4WY6WVf74m8DIkf3QNSSpPStOpwiJliW9tUyyQbBZGjnLpuvgY095te4nCKYC%2Bao281%2Bk1qiSBnyNMR9HMdPOY8RAgS%2FE9pnNu4ZpUweCI%2FYI0Qr%2BH%2F19xaTyXvDZNwmtFOUKNflpc4oydUYZbGAN8yWD%2FKc6K0T96cu%2BFWhda2RwHjNXuxnYt0mjpZ8Jx91dJ0jclc8YQfJIDtjfK0mscJSYRJnrMe59b%2B%2BV0bZT6pxZfTbieZhyKXU%2FS%2B11aJgY0%2FOKOBy9Migul57ph%2BmTvmIk%2BM5oQnLYdLR8mrmF7Ulhh9B9xULpTAppsMJV7jbBuw2Ip0Ik03700C%2BQWmDKNE1TzeKv88A6mtnZxs1VoJfG2Hxc4AsxsAIrFGrVMU3Miu2ybNnd%2FllTDzyty9BjqkAR%2FNle0orL6OCZgMCJFiEN6FVzqRLGT%2Bzsk27mg77areh90W2xtopmxyNqgSPsTsEKQDLEIHGtWCLwI0sQsqpZQQPMlU6Kh6LfNQLDvfbRmUj7%2BbmZEN1JuEr9C7zRuC6fdZJrVXNNNuiSqqzBhrAz4OJ%2FGA3VP4FrhcmyShiYZG1KdNMqbxB4aOZ1Hv1EjkNwHFosNg01P9xHOIizllsnf1v1U3&X-Amz-Signature=b9c8fdc0e076f3295b80afc9489707da951c34e305ea67501f4779691086d2cb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

