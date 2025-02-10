---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662AYYSB2S%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250210T092627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDXeiqDyT7V3l6q4u9\
  AHN0AJ2otK2jxNqD4FOCASeNvsAIgOZSnHzx3FuMM7I%2Fgz6auTJ1Ld3fbQ2KHHbRVb49QjY8qiA\
  QIuf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDEKdzkiVfe3CgjVRyyr\
  cA3QuwretSKv6XPZZwO3q4xHgBzWlbaZ5fh%2Fg6CXdZ3VojwwWAwvoqA89Sd7rlHdFwOuxzjHUuX\
  sFyytfnkFSMurh9c95lsFLWShNTX8BaAXs1nBQSr2IvrdEBpeAj1VdNPr8eneFEgczlcweBWa4aDf\
  IwcvQ5wxueRuGmOTMpdBOdLHMiV0NPhd%2FQqCOH%2Bp5CJpr9MeXmlp6sixl63LkeFAV1Y6FwgJN\
  rLCz%2FzMjuKK852gdswOP0xpQ4sN%2BLweqljq6ijrhAoGEBKZISnRROgif1c4V29aD%2BYp%2B2\
  RTpociXgys9YArb6luvuaDeGAqOrA0UJHkhpDkDlJKqye1%2BP3hP9HDLEns78jy880N2U6J409m7\
  3OS8yVNcLw50sXoiAi4qWzIrekD20YLF7XNMzZ6BmcABMai5o1CcebkZ0ScZTZt5WjM8qdQ1akAWj\
  Bu4T8oueaHmNhT5CtD7pzoiTTObRfsZPWKK8ypThHd%2Fnfza8Bbx%2FfiwONDT0VJKqLiTWhJeut\
  5shGN%2F%2FuEF4PS%2Br8bPRUSKay6%2FGtVG3uVz%2Bdi0hnf0Hx9bjQno%2FvUVeuTti%2FYxG\
  tlwN%2BXVw3dIXH%2BsCLS2mgvQCmoUG35zkmXk3WiGUw0vfKBNM1QUA6nsMPfYpr0GOqUBMaV6%2\
  BK5ohb8YKtReVJHcoelb6C0gm227VEC79%2B4oL0orfTCu7PO9uRy9VupI%2FdgFmoUhbfsidJNV%\
  2F1%2B%2F453UPxmy4k6vK8xElnEQACm6zbM5tkTbOlKks12Cb7xqA80MRUZBCrPskdVWVU93q8fn\
  RAN0ZBixdSQVq%2BheHHO2%2BZBn7gCDSqRHzKsL0qNRYcZ5vMXs858wRC%2BWtXlAwqjYsaxohCf\
  K&X-Amz-Signature=26551a8a062fc1c7e55ad5b15edaec3da1372cfa6b529269378656a076c\
  2150b&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667PBD5XDA%2F20250210%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250210T092440Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIA6L3ta5543aJdY6NFJNDzh4lBTcD3y1NtelcTKDXICSAiBIqv%2BfGcvWgthEi%2Flu6Y\
        l7YUMfwgk94%2FilE73S3Rd7JiqIBAi5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDY\
        zNzQyMzE4MzgwNSIMZR%2F6DyYhZ4ojJKakKtwDyHTuTyyM65VEyMspF1gZ5GbLM6HGN7zS\
        WmDoPUC5Op2dWG13BjJ6RCyBKdwWfVTdwsy41tVRYKNhlBEJpYtaeulcLBeAWOIWWEPm9I%\
        2BsfqzCCiOpqOSwENaMd9o%2FyR8n8Bdjfh%2Bnzt0fJteQnwyE9ww3sDQGPx0bCzh29I%2\
        F4i8HSAQ7TrIkiOdQBRdEN%2F4nMoJNZ%2Bite0tw%2Fc7dTA1thy1l068SZ6htj40H4fBE\
        AVrzLR7PGRLigfexVeQ8nQbrba%2BOoCVqw4SeLG4GtXDaymvK01oQQV0JaQriXJwl81BfE\
        YhmpZbjUOjj60ep%2FysYTzc2Twyvz1BbOeep7zDotU%2FLo1lZ5mDeruBN%2B6aX49JZOb\
        %2B6lSavOWuU5x7%2FfZS8pddTqGHmYau1S9RIqT%2BIMPm4MJI191qEgnb43%2Bu%2F8aQ\
        gHdaJistvG3GH59MZB2ivljLhnouX%2BUSFGTn%2F6DmEVNSbu9EKlOT2QRB2z12vtC43qX\
        o6sO1u7DrTZKXtfqaoNWGar7INtgDB90t5M4es3qDuLO7q98QhTJpMjrdpfNKhdSzz6MpsP\
        SMkoI0CgmgAns8wer2D5KYVglu0JKTfda0IeFzXbdg7NbEmkNrmXA1Cph%2F9DmSikfSfTS\
        OUw3dmmvQY6pgGEipsJqcXoTQdy7vWBloAKyKRc%2F6jHTaLJmUs1ojvZTmSj7y5rH80nhN\
        n7HhWJWcX7Ju2F9HYAqaCwa%2BpLzNk8aXIrygU2k09Wo3AC045QAv0Exg3xZ%2FSB4%2BM\
        XEkio%2Fe7w%2FkGcOn%2B%2BaaTVOgO0f4vA1D6nUdYYuxM4f6NfDndceHpkpVCAewtAC%\
        2B6u1TodQ1LoE45B4J51jvQsmpfe%2BdEIq4gBeilb&X-Amz-Signature=28e0b67c83ee\
        d8760d6aad83b9ef76bf301220db113a508cef3fbe7d979268d5&X-Amz-SignedHeader\
        s=host&x-id=GetObject"
      expiry_time: "2025-02-10T10:24:40.852Z"
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
UPDATE_TIME: "2025-02-10T09:26:35.643Z"
EXPIRY_TIME: "2025-02-10T10:26:25.432Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=622979b4aa7f3471cb886ebdfe3f052f6e8b3a2e2770e2a1d125baa302adecb2&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=564e219fd66d8b59a4367493d8f8763f7004ee2398eddb41c43e1040c9ffd5a6&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=1a9dbba33de5762e8a3d1404fbc62b2deb3f282e24e71c2b5acd5c9e370ae065&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=ebe32047f7650e074b2bed796fb5fd4626b37df8d61e596e09ddc8a1673d54fb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=4d34b3f22433c1fafee736170e6479dbfa642b508273dfab92b4784f0ab72975&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667ZZYAC42%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092626Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDNHZoWQlpMRKQ4GZQjWn%2B6kzQ7WWJ46XH1SVi7T34llwIhAMQDKojPkGZ%2FSBjjY3%2B01n7j7dBGKPPQ2MuwlC9bEIowKogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igxc1DbkCCMJLOaz2pUq3ANAHviu%2BgKdmF1MySt4v7Qu3TZWVy%2FvtcouHmUmVrKajts30NE0pOKFqM1RtNRC59yoWChQjVSO7dRQM1iZp3rnCWM0lGBisYjv23xli4V3jlGndKKliSTW3ElVkZqCiZAt6BzxXSnFYJqJ9GW0hMbF2T%2B3RBqONQmosM9iYCVepl7gVGhpZqvGSKgn9xbC%2BcOhGVJ4aay7uCkFFGbrSaaxejv3OXfaxqbpHljlAuC8QqgLr3vVwj1AXp48LPqvMTjhVAjJkISMIe5Fdf%2FiTgcmVIMoNzK%2FW43EZK4mnUIMGUvdj9rzhtNQzeLgSL%2FVH8UyQCP1G%2FyelQgT6iV0yAFNTmd5mR7Hq%2Bn4GTlr5FOxp6NvU1kJva1BcjbniBrCTPD8ekbXCjBZ7yn6dfYG9SgmkI9bXFaM8kWA%2FbgwHtg2z53rlqetN%2BUbbEEbkDqVPCjzGHpj%2Bpm3v6RErQGcJy6AvgrEJ2R36yX0Bb4HSM5XQ5AhzIEbevzu2H1GSrHtfRS98rfZojFceApbbmPkFpcu35WaY4tPZvSIJpg9UzXiM2WDHX7jssAO6JlclZd1qjDoB7Dt32Ws4r27gZL6GsU%2BKa5QwvhIW7SVZVx4mo6X1BiYlILOLQg0VAcgcjCX2aa9BjqkAQSEcEuUaaXIn7hP3ndHDJoR0hl7g8924fXsYfPLQ9uydXtmdNHjXf4mEmE13x%2BgrwCo0LqAfzj8UK2Ov3yOU%2FtbkPIVaCY9t%2FcZdyAZ4iU1IxGR0hisPYmrx7lVc7g%2FvpHWvkgFXXSQUqo0nziykj18etQGLOJa5i6e%2BWrC018PVrAAuTEAMLLRwGj8mgFaKJL%2Fy0lQk1tuKpYrKdu3MS3bSRMN&X-Amz-Signature=2ef95137c452fc692fc195323352b6aa8e4d97dd2c5758f0c623a4f4b1652265&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666A7M4RJG%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092627Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCn8ySogEGaVZxJoFZ8neh6Q54Sn1bonP12wD6Iz32t4QIhALddfhIMH2Y5K3VuRSakWcUioG4yuNKlq9B%2FGgDtO201KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igy7aqGRNdPvT7GjOOoq3ANwtbcN9jUQ3P0FMucUpoirhIkF3ssFN4T%2BBR0yqeyXq%2FgmxH3DcDImoEIifPd%2Bzl0QwhqTPZWm3ch6Vy%2B%2BWANvot1u7YnUMWyE%2F1L6dyWZ6hCz5Mkkr2JMvdwoAIvSSLt8NGgeXSHevoGiLl15LEEMlx%2Bb1gPd93cgogMr4gg7UzuYGDuGs6t5wPgflKFUVCcuTshyQtMsui%2Fm06KFsRMzwDRUb%2BuhQ7JT4%2BFub1RPIvK3u%2BpP%2B2VuF8%2Bt1xtdhXb73i10qojLq0cxTI8xI7DLjOgRBFPqxhCxOmGnFcz1k0iRgZEpbSr3gS%2BSk2pSKRbLSGgFyltnIilxiYCphN5w8ntG3ADchAvNiJGeUhKj3WryL%2Fm4LkioCrIGPfdApEiFMWh8F9OZwdz2HF9V%2FBHkwsimmgYLQ9Q3KV2ARLre8qXVDbeuc1g1KYI25ILY3CGkPL5S1dmIBp1waF6S2MCBx2BQMsjur9CnpXERlkP74vWI6JxDxg2CofHlrrd9ANRswdbsOxUpAOPQulnwA5s0Z5GQoWkPp4AUqYJhysG313WxuEFV3A24eJ5eiDlxL6qt6ZN58CVvxZmETQMOhhC85F4IFcDEG7%2BlYw1zJGrO1wSwbFVxVuqgdvsDTzCN2aa9BjqkAVy%2BLIwFSfLkC%2BNFCn1MGhSB%2FkmZQVjBF%2BFo5UwJAK5eQNnujqaZiPfyzG8l%2Bweu9NIKjcD6KLfRLy1nKSxuO9Md4iIpFVtHbeHwSLqPTCqv3ePZ1FeVpa2eXgwktA6Bixu6M8UY1LXlzGq2kHBLuIuPbbR6s3nC2PzS7aHFpQvK0fvDWX7ECPB%2FhAydH2ERc41yqX0WxrFusS8jzkwFRaoaJVev&X-Amz-Signature=274f70cc7437a35fb9f1efa084ee3504798b0df72d5a9133835232f14a226c1d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=67c8f5892c8acb6f52f23c8953bf006ddfe801d525626a002b1a4a37ade7443b&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092625Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=67c2f6a54e6501bc027aac059127322393ae6fb883795a562bebefca8fc69ba6&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466ZADTRJZV%2F20250210%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250210T092626Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEKD%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC4oqqxEh%2BQZDOEa900BTfWwlZihZgit0wa%2BV3Nsz9j6wIhAKfMvCgHTj719UK1mi3KkUGxMWrCsy3gnIU6M%2BCixNC0KogECLn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwWdY4mNQX%2BWVLx%2FbEq3AM4OdL2eDDDct7e0UPVfpgv%2FBhWyLw5fBdbwQL4vSeXoUFECYylR9hsJuPFVklSJS55pPCotLGWhBk%2FsvPty1d%2B4DFCGbnnolUiC2Lp7eJvoNMrbX9JlL%2Fwsbm4AEn%2FbtEokk%2FFdwh0II%2BH2Yf27ZNRsEBosu4G70C%2Fl4WGdIhLifRdgQa6VVQ2D43wNj0oP%2FODP31T4AklrE2wPyDXtCgzl3FU6%2BghGwAJjZOcInypTwP5mIqr9F7pQx41ieKsU2egDf8BcjvZ6Aba6GoxYsr3h9lf63zLnhCPfEnI3b2PIO5R%2BrJqBtpF%2Bp1OEObsWvvMpHaoA%2BzE9UXwer4%2Fzp215cUN6Glm70Co3fot1jDQd1BswYzIAhwYx%2BXe%2B8i0fUiZ3Py03Ct4bxN%2FtpPGGpPpPUKTir10QBUCXGRZyuSfwV9yJQs3ACThyifYHu6j8ZVSguLXVdqjI7JGN%2FRXTKHo9R03GJ6zLkarblRSe7ZXI0jCSdnGpc4SxeXDmU6O8JXmMTCnaPpc%2Fl%2Bu8hsepLX2mfTggAWE%2BtIYzd3lonleebrRYrEcUB6iNwAQ%2BxSgD0cCUx6Sy6dTGmbpzSIc6mJ0L2ald0ueGXWDRdlX4jCNfyLIRowOEKm4EhSWzzC52aa9BjqkAU0%2BUsfdmiJCYEh7n%2FPMlnlv7O2HZC9FEe4Yw%2BfAketMLt069jCu5bNmL8%2BRwusbBXu8J7RHh9CMloKS%2Bur84%2BhU6yTJCqHKgtjGiV%2FnlWziOcY0IJKbKZGbnQ6sqxLuhllTJDlg%2BjJcolrsmhGhSg0ZbpmTLJv13onP7IbhM%2FDnsH9bXrYrHSiBwahh2wAXqVt2M47k0vK5C8s7HzSrIWRaJ9Zq&X-Amz-Signature=6101aed47e80329f8c371862de796aea90cc6d982a475a1bbe517669a8588b4c&X-Amz-SignedHeaders=host&x-id=GetObject)


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

