---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XCAROLOU%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250208T102303Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHAaCXVzLXdlc3QtMiJGMEQCICM3sVFkPvQF7fxiU4dS07hS7Bmdqvrf9f60bnD0x9NyAiAPY9s\
  %2B6YeG4ThlriePmNGPce%2BB56mUzByyCpoT734BKSqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%\
  2F8BEAAaDDYzNzQyMzE4MzgwNSIMfnwqYu2L7%2BTrEPjyKtwDssIHoFSOqrayqOQT69dNK36dkvu\
  3jtIT%2BJznF%2F5%2B7l%2F8nL5XDSHXui9iuKyLEZD04Kvda9O%2FltSOBTUu6YTdpHRNehEAY5\
  oNkls8exiWLzZcMRjWZCUJwnzUz136XCM%2B%2BHxwK4rmQO8%2Ft4jakr%2FGqkba0hLDcfui57d\
  0eDEjYNq57EG6e01jj4tqgOqUbVX1B%2F9Yqx5rwUFdpb%2F6brvOh8vNMO995UdliDWJ1WzUIaNv\
  Z6kAzigxjH2kRMX1sFRCHATyVm5C%2B8rnPHKIRWPsAfMD2IZRI8RG%2FmAYHN3uBdfuMl71P9vn9\
  JPwkVzR7Ggt5cvkhlUPsaKrboZ0zCFzSkvVcE8OOOWfXqA%2BxeDfc5nuBr5bQVRHWMQehE1UMc5e\
  XnqP9zUUkXypFI3YYKInQsYjbUGxFqZFM4vGLTZ2O9l%2Fhtx1J%2BNo1fJcFkg%2F6zKjZYl2H06\
  gIxnpf09HFPT5FEgvp6dcaSQFzDSqTpOGY6NroRCbhWZ%2FzhKff4syrSHJ3Nd1jAOjLjtA5pQmVW\
  6pPyrDfngWthrgqUCtVsTIMfMsBRPsS2g2TG6Vamcu2BBEnzlyAlx3yflJ13oL%2BIJO6K%2FrJku\
  Q95NqoBdgNDz2mGxoQnAPc%2FGQwAiUASYw3o%2BcvQY6pgHBXKb%2FH1IAdjyk4oevqUZZLbtIv6\
  BtLO1wr%2BKYSevP3twUQgPokVVmpyuPbLOCivWwmNuCFD58t1Q7lrt6vGLveYX%2BJ%2BF34em6X\
  dylhLRIhvl97ILgZa%2BhR5YwqrwZchs8Z82zKnGhqE73BJVkN2zJ014Gti69hfjuyntj8%2Fg4KY\
  7RoBeLlHeRpKWzf9WDb9saS60Q16Z74IEGaDVbSOfSbFws%2BNES&X-Amz-Signature=280c73b8\
  8ceec0907d859e43a3c79ffe8272d06521d7e04f14220a17d763be1e&X-Amz-SignedHeaders=\
  host&x-id=GetObject"
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
        redential=ASIAZI2LB466WQMFK27N%2F20250208%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250208T102203Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIG5ELCjUCsEwwfxlZnb28YbRr9pP6cp\
        EzwhCdAPH72BQAiAr4Ls8UVN19Pn%2FO0BO9Lb5u8CffRdQHENOWf4tm3ypByqIBAiJ%2F%\
        2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMhh3BLYLU2XSDSdGdKtw\
        Dovpu4rxi9fo44n2tp4%2B7OIBBbfYIvbTA%2BcEebycPEimUMbOvKTIMxEL%2Bvp46GQnU\
        hwbtjH60sP4D6KkU5IeRo8zjTC%2FRlfwMwMjSldJN0x%2FI44tQcysjmgmO72WibpxCqrE\
        QwKTbCaAVQ2oED%2BzKtLhe6eMUeYvSjAw9tYHaxP5fToUx4f7ME6HxqJUUthvdyU4hZ5MA\
        2n%2Ft5jwbByvjnuQQJ3mg63zmRCZ7uDXMefCWQITBY%2FUi7pSh8Q%2Ba4Cmw4rRCOXtPI\
        lZqDj5ArVsN91CN8urPyEibbW%2FZP4M%2BZEiK9jYdQj2QYObrv1HHOCzz%2FM8Y0xAhuf\
        jSbrVclmuzhqDkUUNUNLc5YZzkxEqaWqZZJvwmRvyGJbmtKzCPQkqI49P5sxoHL1VLtG9Ve\
        ukGO0FEpz5X0bHPivcIXTnBrumSiNEZJ9kchwIvBx8V7SWEBlwCvt%2F6niVGnlVRi0YMKR\
        y3d%2FixQ%2B0y6MZ9lkpAta3ylwOePn2nxs%2BIbi%2BY1b9xGYqDc30pWAjecPWHhQoqW\
        mmsV0J7obtjBxy1U4E4am5d9AJ3x0qQetf%2F8z%2BQ9dqKeo2OeDV3k0oFXHfo69vdKKvg\
        oRyA%2FTmvGgYnJ%2FQmhVwF9KkhLB62A%2FUytmMw54%2BcvQY6pgGIfSaHinpnYvAyvQi\
        35GF2EAfyglxd2DbIHZJ%2B%2BSa5xVWfoq1kzT6U7oNbySvIQkYsiWg7zbtcTUG9ZDhTHT\
        2X4jON3GBogN%2FGXvWMngqWoW9mZJEXUrdz2OWwTVLi5ptKSEVFif4yB8eTQ%2FpZOhXoS\
        zcT58UVUV9pqD01xDmPdjQLG74ih9V3yZUdwnezpjALiWbOgWFw5YlVgzjIsk7hrv6XX5sp\
        &X-Amz-Signature=cbc31873f8974b0112be2181aa1465208540962b7b683515538380\
        b90bd598df&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-08T11:22:03.500Z"
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
UPDATE_TIME: "2025-02-08T10:23:08.934Z"
EXPIRY_TIME: "2025-02-08T11:23:01.219Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=92c92ea19bbaf2da0230ce22c1728e2b06ee8896aaeffd8ccb94d0c396955571&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=ecd1076b6f3d2fb9ec188ccf3280ece9c15edf8ae100c4ae53147777a1f2d1c7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=230ccb087aecff6635fbc78322a497064139fc4c62069590bf8ef0a9529e1df3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=60092a257cf4e19496492d0003fab53b4613eea930f9aaafce99f507ec2c472c&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=8701c3bf6271dcc782972acceb5c5458966923b3db4fcbf22d126f444db562c3&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YQMMNBH2%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJHMEUCIDMgs%2BOwmGlWrVGvsheR9yjjeUOzqyhnTS2kSI3dxvksAiEA6qAJZfLo4rGPlg8fgUSfn5IJAPGBVEdYdZSRF3x%2B6rAqiAQIif%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKiDRR9KklKR5eKL8ircAwll5y2BraS%2BwlibAWegOv8RYB%2FVZbfbP7BstuJpDuxTmXpyaSgj7kFSPS7ahmmCvP1R7rH2J21TUl6SpxbDF8gL0xRCdCrWbDVntWhpV6VNOavBJP3WP4iwf5wCl24axOQ6qQVS8S6QKHkX05dMIXEt%2FgxR4yrcj0fu0fW%2FzORmCbCrxZ8AECqZTPMY9GwyZBwuSEUoGYhNqBUsFHqvVVUEWKet3vNgHcrrOI7wKty9l7p6U%2BO6aPP2IA8WFG5zslKabSCPomZ6ukxIGIoc97xX4UDe4DjFpGEs0uHExZgk0mzAG4QTdQhoSVcpkB%2FwjJCrNZSdJQ3MQqa3rHmgAv42M5lzjodiwPQGf8wSyrAU66426hhDUDpiQeJHzi4lPvo2vPK3B4O6Etjh%2BOYcVsUWcI6nORL00FVDabV3G13L2oEvw8PDveWQiDQnH6Y5bm1jBjJkPL%2Bid3P0kCkOdFyUKzDuxSFl2TXBwknPl0K6qA%2FXe8ru3na5NseGZx1HoAZS6WI7yuBsG%2F7NJktvtXXCMkxGHxykrzsbXPcrqtlzwqx6DuMRdHTKL2IR%2F6iyXcGjUIrP%2BAvwjmbt5uEhM8OeU%2BBBH1a0oA0t59ZNVk%2FvcD8Iubju8dKBbmORMLWQnL0GOqUBcQ9Vx412iIPYXx1fE%2BtEK2MN19xnIqjrgDksB8UbtOEfnp4R9ZyyMXBro4RWooM74eBXW6hPWslOUaWtTRiVuLxEfHp3IwF80iS%2Baz%2FVrUcVR4kh61jyaUV5UFtRk3ofjg2dDqnSA9EB%2Bs4ivvFtRel46ZvGysy70AoY23eAgJQ%2FFcBWFVikvUyjZlBPW3kU93MB7S10YOYWWgpOV2P3dE215C1n&X-Amz-Signature=9d3fc720c2aaf97b5cead417fbf7c1f45dff1c028faa06a8683bbe3bed03d19a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663ZKXH33Z%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102302Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIHpwaUYZEO0HRGco6bp5G7rBr8a1O105PpMyaPFu2UlZAiAm84VvY3h421Sx7vcJHsUDq9SdIBdA754WGI9gY1j28iqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMrLRphuoHXKtKH2vUKtwDwQAjtezb5nYHde4Vq9K2DzymRhEP%2FWNy1VwV4lj7WAQ8Ovz9%2Bc5lbFO%2But9nvv3EbaDDQIWH8HMd7tKiHuI4yBlRZRU70F1R72Yy2XfTsqIBkf9Ln33HOuwCTUWjnmTZgxANntHaF9C8v1%2FNX03SiFV5xIdpq8ewowW5GChYoWeHmptqYQXefxB%2BLLmyyXqV6iYXJN9q9nEzpBO%2BIN8hTnxpSo6AIkz4jooarVoxLrMECSF22De%2F5%2FzHq96mScKr4XvCB%2Bpu7ns2YBsSTNccGiyTt0t%2B%2Fxo0StNE0yeaLV%2FioQ3t%2FqRFFmjwgJsYh%2BhNtq8AJPpsiRQf7qaxvvQv4VzLwyzlWUOfmlkR%2FR74R6%2F3i%2Foz9LZmOeDpBsiq6yXCtsyP0b0oldPQT74Iz6GeokhN9mShb5t80zq5eix2t1ANct72lQbfkr1pSH5Jh1JPBZC6g0plSvamMfNb3WLd5z9G34Kr7FYvQZ5gob7agZIm%2Fo0PScR38oEa4QJynWhaTOu%2B1ZjAjMUYzSGo8Rcy0BD0jb8G649F1%2Bz88yMopq4dKUDeVxatlAEhIZ3vPw793R0M9J45%2BOpaQn0RaPLwax3qVlrxTQ0H80kNvrSXIU80DY5XWzCcgSTh03kwqZCcvQY6pgGcmO4c165%2F%2BDIrFnU7JiVJWXMIbRmJ8DY4k%2B7O5No41Fc7Su%2F1wvJcwTVIGu3phqM2rVDIwAJq9ohiGLf9%2B%2FOPMdcIo7kwjyrRojsnodtGTTQ66TA1YGb3%2BG7ceLCTOj4QlpBrtxsnrpmNyYyr%2Bdq06b0YE%2Fr4v666mIhZrDaPDaLEpfsJlxTmtFrv9Iy1tR%2BZFSZzlN6kVWDLvV4U7fHGXsRBd66l&X-Amz-Signature=5b0b32c992e3883a34de12048519144c73cc9acd6a1b445134ebc060e09850f5&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=f1106f54559974a5d157fb90e6697d7b4a89fa91acaa4158785b1e0befdd1cd9&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=4b36b7249f72c295efab613c24ed6941e6dcfb0384f506d50b9fd862b8594ad7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46656TTPTNF%2F20250208%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250208T102301Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHAaCXVzLXdlc3QtMiJGMEQCIDYLDS9kJbCJDdxYIG8gbB5QCKl6a29HJtTxT4gAbyFWAiB8Tas4cUkB7jLvqGvbnUlHB7w6J7%2BGkl9QwZrO6fkelyqIBAiJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMUEU9vMETZ76ZIWDaKtwD%2B174F%2F4nhU%2F7c2iOpbXhahs7UQKXWREO4bRBaHHgbtn16ogIAD1%2Bp12XIKA%2BrCdRNnJHECSjhO56gELgCj41uZ6B%2BndD30zuraqvKCWlOEKw0uvnCOBSHNHUIoYvRdYVTKKqL%2B8S57CPLZALeJ5yr%2B4YZCUaB6DSrA0vNMXhNx1Mobi9JytYN3GLGCjAyHUxlmsoBZUCsFbVWwvX1SUdR7L5hUEiaMBz5nsoKH2iN2BGIWEVJF1B17Fv9KPZqRrJXTRlLLAVu62am9hcjsaL5zthspBOox9B0Ur6ylIgYsiWLFuB13s%2BnQmyxb4BabFQ%2BOXmag7BZXe8b3g5taZUmhnNgsD4OyIN46Qa%2Bx7aE%2FoiicsrRqgFnFkBbxeUIuNg5F6voSdGl4B5GmooCDBndq916Jo9jzTB75Tg8fevTjExIVxLGjBHjiBRVjtICPgRYiB%2FyKU6rMQUeMscngAiFwq4K8F5Q4Azd5esg0bVC1DOJnKvnEHloMVTJiEwr%2B2o%2FeetcfdfJh0TEhWQHvU%2FzOHLEXgFHfypnDFp2c%2FrSx6ahaL3KIxK1eqGkAc9qrCEQfB9KjS3L8L4MDDf72MUpGX5aojQq9119Sny5NHIWqkwykehvt55uHO5Cy4wp5CcvQY6pgHQI2r%2FIR1rRc3h3WJKOzxRhIbf%2FguOifNpMPKeKTWzN4Mcj6F0fvogooiFwIT3QF28zLkdC1%2Ft3HGTJrNl5d4xwOtFUIa%2FlHejBPbPYJg9bc4JHaNw%2BbJ0XCUD6eMYRTMzFLQXFQmsEGYMi1JqwvFAN5c2zuPaehek7I0jRe5RPx7Zq%2FuhslUHpyxKaFPsPHrMasGUcTlRRPI26tGQPOMqj%2FZfbBHI&X-Amz-Signature=30731cf55d0425c1d61910c693aa54e889763082e376a34e26f2e12831e6a0d7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

