---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466UIUFYS57%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T212154Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIHOCwGxqHene1tL588k\
  Fz593y2SibVgY%2Beam%2FNnptCXqAiEA%2BkPwE5E1ZGcjzpeDN3WwV%2BwKwh9NHUoH731RTkQO\
  H7sq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDMA0Jce1mps20fZjgCrcA1IT2yVeJY2pWChPLflp8xp\
  %2FObdK7%2BvbtThooo3Ll92iJ6R%2BD0di3NY%2FZkN3JZhGMEkN3hH0Rt3ttTXUhi3kRw7T5Sd%\
  2FpKNulkk7A6nrvgpfBMTTkgh5MsFb5aXzzYUWzJLI0bBucBlqttR%2F60ueecZVquScnLfytqDNr\
  XAnlea%2B65FN7tt3t1NX6CGOydT3F0q9o0sK0JlPfWSSoVxVUBgCBHwsEOiesKAPxPDvgl8sRXhH\
  H6X%2F3Fn7MbS48Rjo%2Fy509tUgVRBbRMZdvBjcDf%2BitAb31zwlxrAPP14N5a5d89y4NYbu9Op\
  jkiq6XB86NtYcKzI02cRalCCmz66JLj4h8GaSQooe%2F31i3V7QgUcWBSsXZX4NuEsh0Wqmoa%2Be\
  pX7ix96vjOR1ET1hQh33hN3hcU4Ztd1yNpQ2F4zPpHp9Ofd3xlAhNW4a%2BQU1BpjIDJYRoXc5xLo\
  2qTjI%2F1b9Q%2F2IxdweL6LClHD5C53exuVHkyD0EflPlcri3qxThFgqIDiCE%2F0Uc5AesGFBOb\
  %2FEAnrExJHjDHdb1QV2iW2mP4bNmEX9h6M%2Br9gJ5Ia%2F5bVMLyjxJGBk2LVA4iWV1A0%2BCec\
  %2FoSsj0w6wOl02IqUBac1YppwMnTPXSaA%2FSID9MMiX7b0GOqUBWQmkxgdYXc2ZK1ayVVQvSU1J\
  c2%2FwLETIaPxsXgk0RbJxgkVyapIRm6yzLucjwVoq8cQJw0GJje5yuzdCxG272vM%2BH9A%2BKEF\
  SLTezM6ZqqIUWhtmQIzVneObJIzk2Do%2FM9Zv%2FWqlH6zQuhVVk3KMzOeNVkql1ztGQLUfPnMY%\
  2FV%2F0amgO%2BW5PyXFK8AZj6wsw8RfeJvJEcu8kxb1xq8Fvg7950LYW6&X-Amz-Signature=bc\
  62516e41e88a976fe059ca145357fde57ad8b6663f4b06dee3666258cb1093&X-Amz-SignedHe\
  aders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466XWREIU3L%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T212011Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIDuzJCfViJ7vN5OnB0hkZyR5jHxd%2FVmfYQM8u07%2BLPyDAiAtgf9nFVq4dollHoNel3\
        tdGRSqOloMV8IWenXh64KIrSr%2FAwgaEAAaDDYzNzQyMzE4MzgwNSIMA5CyFP%2F%2BHVI\
        B9Xh0KtwDQvTXhIGSdUHOGuG5gU%2FvcisMIi9Yr4j57%2FdCSCg%2BE1WwrHe1WRRtSkD6\
        %2F5pKrhmbKk%2FySqdFEKFEJhZudnEToWyL0b8RuoCS%2BgZju%2FmOInRsS1YF%2BRIdA\
        XX7HbvrKy0ANBPcICBOGc6xFzJzPcYAl8vD2fFVIjukTYkh5ptZ2wJrs2B6VDkNx0zhk7dj\
        VY51E8ASii7yKwRCx4qjernM7iM0ryDS%2Bb2Gi2QDy2K55SMFH%2Bx2j%2FRJcfD%2FChr\
        unvnDLlWK4X%2FmM3xMaT4uD3A0%2Bv%2BqWmmtG%2FkmDq4PWxxjjWeRNpcyU3vEuOnOp9\
        cjBXEHxZcY5fJrpCrY10yyTe%2FAdoga3KO1bkFoyoFguBT6AaTYaWZ1WscVJKgff%2FaJQ\
        vQ4RapD6HoPjibZ8YSv6KsFd8qyv8%2BVL%2BbhFADfnzQeSa0wbyYBvtMgdbXcTwdSS2Bb\
        hxaZF8RTyLBI21UTv5Kj%2Fp%2BBwFww2ShnxT0YLtm2N2dagbXLsgbrgh%2FkWwkoxReiF\
        NHq0Ak3O0wQrWlU%2FewgBfcp89%2F809%2BBz0MKaugD7DP%2FEIGITGuUVEWhraJg8iIg\
        U9cikFTfpcwefGT37vN30%2FNzI8iV3Eq%2F3MCcGjGYbkuZ9rsN0LUz99Nnf4Iw2KHtvQY\
        6pgG8Cqsx6cbhasHd135Cc%2BhF%2BMR3CjS4LfzcfoQDMAxL8v%2Bz6xPmGRNpEJIFxFJF\
        %2Bn315u8ZXymb7tPSwWtldJOAXds5AhsRrP6%2B3ZB2ysc8Mw9gF4Hu2LCzuQgAvzd3jRY\
        1CGhyJRIGNXqxNsjeDbP%2BCWm5%2BamrthaK3x64XkO3xriX2DptvqqgOsb6GGvUPYsGa%\
        2BKGFHBetiRZZsz98sUQG1kJDYxp&X-Amz-Signature=f8ea6fc64142bc7432344cda42\
        47404b8e53490512ebb2f79d4058ea87c2a366&X-Amz-SignedHeaders=host&x-id=Ge\
        tObject"
      expiry_time: "2025-02-23T22:20:11.521Z"
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
UPDATE_TIME: "2025-02-23T21:22:07.043Z"
EXPIRY_TIME: "2025-02-23T22:21:44.444Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=aa8e191c204a60581ca39680e428da869e07a283e72b52d1c87772fbe2f17b14&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=5076d863cdfd35072e265345b53e8db47e21ffcfca62a10871f7776e89654558&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=f968c7734b1c3d1cdf6016024a310ed366c8f8f1c6a571ed6ae876a36754f3e5&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=c8be8ebb696a270223476bfcdebb491a605e42b97e08c72af40ed9ef7d42517d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=db0245cdfb74a35b8257441d84a80a6be1dab8d0dadf3b14e9dac280505d4772&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46626MD3QQ2%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212152Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQCF%2BbF25vBsTOmcdRoiPOENpf4IqCSB%2F%2FaQcOc0BI1aNQIgG44scE9LQbXsJL6Q2aIveCMVn%2FiCdQs8uQniXivvwB0q%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDLxjvnOCvkMIh8ekiircAzzLuP9tKvoFP%2FeRJ0kR9XZ79FqiSwfr4Kry%2FmMioh8Ts8rvE23BzTofRq4LQt8VY%2F7MgPx0BWV5H%2B21zUA21%2BlWiie1DQq5HExZuxPfeDf3PfjZkkubCmCX1hRM9GypkipOKICI2WP7KJzH8KjAbmkneulP%2FKe%2FRkbp%2F8HgAmpghs4PL7yQGAG5VZN6KrrAvsT9f3Emt0z%2FnJudi7zV7tMTAcpivK3iR%2FZGK5E42oFcYQLxTo77JjPKrz72T2iHDjHzwE0nVS6u3rfQUZ5AIngPzkG63fXaddz8NxaHLixwBl5uKhXZ727QPxGm7eysMaxO4E2AX%2FVa7LBVO893p0tRjjw%2BqX4uwxOJykwzqkH0l8cORzAssS1BMBKQT80cCoEDvD1hM%2FRgNtt5FdWpIxnA7%2Fg0UHIi77pe46tPzkDVrePVFGYYL4r9ZbA5%2FIW5B8vF%2F3cWF1zOW8N3y%2F7H9qmL5Im0NMkWnxsqMSNRZgj%2Fjv2JushNh%2Fzu8fOn1DOyAd5EW0f77FyrDwPsqN0p990NLtsCmuDPgkkwSX1j%2BR9VvShgPq6N6BZhhv8BKIPrsFzIwXrTh8jHGfFF2qF1sUNfTnG5zQie0Mjk%2B%2BfVbJ%2F%2Boug4G9nR16k6LlkrMJiL7b0GOqUBnV5NDc4l7cBTUea1IWbOoktn91MjZX%2F97RrKCNCHBOeptWvf%2Fc%2BlFLsQbw%2BcA7U6o%2FmZsSDuZ4yJejUpRCD0wTo93AkDtLCz9qf%2FCIUOW4v8B4rm2PoD%2BsbLkYTJkcDnP6aa%2BCNbO8AqMwVhVrHDoWBAl69X7a9yqB%2FgNKAgCCvG7Cv4jkyxNrhNFHcqMSpr%2BW3v9FoypaZhcvfGPGCRLjYPo%2FDu&X-Amz-Signature=522986ede4475af2df0fbeae55b8e320b1768443c2055204162711667d6ef9e0&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZVEGUHL3%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212154Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDEe93pNUnrZz3BF%2F2QF2Lacb6tevznoCXiGRNOlBeVcQIgZ9g6M066oQhRUKdxtURCCHeL54aPyn11h3netxjfubkq%2FwMIHBAAGgw2Mzc0MjMxODM4MDUiDNh8HKgPCo2IbL9BLyrcAwypG9wnX8BBDbHF9Mfsj%2F1lYAWQYIuU02rHeIDkAjhVUPXghMv8WEQtAhy%2BXNTeY6BHjOa98SJ0kE2JWDcDNAbnJQ1wewkYPhjhOGCuNy9rHMfCFxdA979zg3J0dyXCgIO3yqwJp%2Fh%2B1lrB4il8yI6qbuv1imLpukCbJSRrdI7XA7lmfj3yD9KvvaOmH3cbROxHsxU1%2Fehfcb3pvJOWv7RxXMEgCeBw8LIf5RW1bsNoR0zDyisAWNqzRS2FwfK4D8tmd39mlR1SRVquZXuNfrmc61veoVdeyCJijHTGaahW7doK6xZ4TM8u1rS146l4kUZRbWsMuAPiZbKw2xWIeN3sxlOpOyMI4ZTFXG7lO02lizut3B24hRoUp%2BRIUTWvrBudIh3VzoFGkOr5W8gycmDcnrIHvkFHhFhvpdnKI23aA2oM3an%2B5xdOp5QfhtnCQiX8Eeh7%2BojnrQn81bNadXSGFXgbWwkntOu8VDPsu%2Bcnph73rtL3iN18nzfyKA%2FipDrmG3y%2FnxQYM1ZJ74maZhu%2FXfap4TTcw9EQ30UPJAlRk2f4DqzLy6zqXZgKbHkHTwo%2F4zt%2Bb%2BQwmMZgqnOnFNYa%2FG3D6Gr6RBEapQfLtjVeh98iZeQCTWxc2dH4MNLn7b0GOqUBSnUjFuIvq7suMyZLPXifHNp77542r%2FsRgN7wQa9Y%2BrSMFJCUC8Ztvryo7wpxYkI8Aib6X8k%2F6dyMxw0qzX5jvI7zMOwuw5Dif8BzFi0kxKbaIvv2MsHwZfcJ2NRTNiQK7RXdLriyPZjrxaHmv40Vy4buGehYLB9ME61Idt0w3uR%2BTVhGVwZc%2B63cKxZoqtVZG9VXDkdrnhyV9Z%2B4j38qhHhiH5HP&X-Amz-Signature=b91db086cb31f1146102f4b744df8e80552ee351ed0dbe1b4390696c88996644&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=d8400e06469b312dd2fe598358ed32d5e547024549fba1ab774cfd9e5a9a12e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=cabbd643f7eb3583d4ea842dec45bcbb52215619227613e83f16707ea4ae1a35&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466T7NY27FJ%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T212151Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIGxq55GFh%2FhZJe%2F8mS1xpYoXDFOUp5lhcJIh0xi99qpZAiEAgGwHuSBpU0yNAG4nKkld%2FplvZeAg%2BmGKKnKouB2Vu%2BMq%2FwMIGRAAGgw2Mzc0MjMxODM4MDUiDGBos6Zk8E1TwnPwuircA3HoDyL4XZzTxCWMtypSTI2fYd413S510Kf3u4s4NTiCAU8ixPLLsSgU4Wdkf%2BACa%2BbNkHsYCM6tv6XxS8jyLkgJKv7TqoClpa6Pp%2FY%2F5fxn29R4l9cflHWDUuhhKxowV%2FVYPZzJShDDxiOu7cuI8xWvsvllxxwz3hVUaWGR9SV5c1VARe1f6DZtDm5%2BhkCSrfwnBjBRIn8Uxf%2B%2BA1vRYM4iA66Wp9Hdq0M31bphMwYgtb59%2FG66H440a1vjayfvtWgfjtuqsEeGKCPLCH1rA8PLv5bzlegM0D8gGT%2Fxco2%2BueObosEyG5J6AQiuiywO1ou5UmDFwB2ipv7akNSTiHDDe3NpPi%2Fvwj1xm2UZeOZIg79CsQvg4N83sgrrYlXG0ZDCRZMjIAyMRqW1A%2Fy%2F7aKkLXaY6ysgy5mlEPi9nElUzDSbXu4ccuVlrACuCV4WwZvlLnL7SRw%2ByKL2%2B5iZcp%2BCNzeUL16kt9wHqrXukI34GB1q4Angc2F1alKL%2Baic8M9U9Ckj%2F9RLvo9pARxAdRGolgV3Dr5BQx9WIA5sA05huwTQjTqf9myYhkIAfpGqUZjFKn32LR3Kcf14zqm9OQPuJXsiRi3CBXH1Dppnb4aP%2FvuUKuUtRUOjk6xjMPeV7b0GOqUB%2FpYm7mbP8HQauYY2OuhXgxQ04f7duIj%2BdqsoZ8o6pwWl38gU9f0BzB9mVtHy13swvoS4FccMH3nKcwckYbazyfzKyrWhEVctfd1f7XTK7SsrFPwIFkXhk7CDRUtN%2BkRGymuXPNs0Zpt%2FPz95Hi9eN9cNIcsZyWuQ0ty0UxAFWQb9fQBd12RZBxf7qox0OhC5Dm%2Fyk0YZ5o5gVRfWNxuFYEjxxw2a&X-Amz-Signature=603291eb853288937db8df00765d6b364dd0c9c855e2b411d20c29e0d1cc1ebb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

