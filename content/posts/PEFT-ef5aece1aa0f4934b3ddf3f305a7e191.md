---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466V6QG7YY5%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250216T142017Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDQaCXVzLXdlc3QtMiJGMEQCIEJlpz8dZfNSdU7%2Fmjiqh2THLUVeXnacEeTkTgnls5L0AiBDX\
  Mb3VguBMRsBk0n2cDPE8dIexJftygHexkEv6L%2Fymir%2FAwhdEAAaDDYzNzQyMzE4MzgwNSIMgG\
  YLwxSYr2HqQ96oKtwD2kCWbWs6vKaGNxE3Ge55UZdRqpYhU%2BAgNM%2BqSjwAXV5w6%2BYzVjDF2\
  iYaVk44EdMtfW%2B52m5yc406bEjYT4BVYNdUDTF2hoQanUTdWD2JVYemNWmfENMOknM2S3ZchM8X\
  1wIa4k3b942u1%2Bg4jb7irjbLYIr6B%2FTVUSQxaRSKpP3%2BuiGySVXqBDp%2FI40N8JOO8EY9O\
  QAL9c4VE9NRLMVhFJAFOoFUZOXgCDX1gPK1ng5GH%2FfEav9PEHwseNLmUP%2B8NvWnwUW9U4dLwt\
  UgGafHHxaCQe%2FcpGRoBrEiBSaQYq7Chvbr4p%2Fb%2FdCnjF%2FWuiCW5ylVp%2FDJAkq9dFMen\
  6kq8J7odnl917HXpefKAmIWotBCthDSZIHO0guAI9z3Dkp2SHZlPfY7SwWZ5mfHu1VMHFuLIVhOeY\
  W0hHvzLYxKUd%2BfW6oNTTnGtS10wOCkRJ1x1gxLn89bTYjX5VcS1fDjtfN06M3VpgB3CSBWi69yX\
  Qp7Lg6RNLlXjTb9P4bIuENuMRTBBecGo6WL0z4bTxhGbXCJkBrPciQWYrAK%2F9hwGpINRXQ940Qz\
  ZV5aB%2BHTm9vbpqRapr2%2Fkxuhugk8B6H0WJOLfeOCaUnTGS8cyYo%2B6gEZAKY%2FALm3cQGE9\
  OkwvqPHvQY6pgGb7nJ5Gk9OrvvVIbN9xV1aw1cQxAn1PWBLYyAJNLM5G2NJWKp9wsUOn6o1yhoBnF\
  QmfwIbmNRqY0991QCW%2Bk429JwP8mb2vFK85cLDFwkPoiIgW8uy6BRMVqtmOXsYSenfSkTE9KfBC\
  wwOYXyopS46Q9nokVQ4EOQQ6V39gjyvkSQf8iYaVNl3oAaiLwtF%2FRTsiiHts9fVhZmVQcIJMLYd\
  Myeu9gQf&X-Amz-Signature=f7da826010a0fe71c2b4e011d3f7f337330cd02e91cfa447a473\
  b67222910ab0&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665DTIHLG7%2F20250216%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250216T141855Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQDUPXXEh9EPelGCEDoGIUGZsgo34fu\
        CkMYdPp8PzWnczQIhAOQkK88x6x7ZrrfJDNjXujndM1a2LxwJrt9h42iN4QGOKv8DCF0QAB\
        oMNjM3NDIzMTgzODA1Igz8YcojN6V%2FNm8kV%2Bwq3AM2hC7bEHClUEHc%2B0HE74SzXKr\
        Nzz%2FF4pc2HgLvhBmBleTSj982jLkaDWte2EufNUJabklEjc0aszSGS8TL1kgygGbZxVra\
        dd7OjJntmKCRJwwVe9zHC7rSHyxq4PwI7Mw%2FcF0Ffq2ZvRoeP9zM%2FReNX%2BsN0Yroe\
        atm9VaU8AIp8uS%2BO34oo7xewwc6JRmwYnTXEBKa1Fsi8GIBg9s1uOXRzizRg90JetO0Ee\
        fX%2BPCCTy%2BDMcBqCovtGIRF7lE8mPJoFBPHVrplu80qTaK%2BMO9kJ78u8OsECnuWLdw\
        l2ydFS8ng3Xz9s9%2BYSyCKvn%2B583jpAJSAegCMArO5sZc5etUHP5ubsZ5%2BfQCWFHMd\
        bIupi8ZePV5XbGrX6z0y6jQCHCYuXfOtbmhDiP9qL4u%2BGm0LZ3ENFl8%2FFOpIQ6jQMRF\
        VwmCLeeZRDeJWprqWJPJgl8KSZRdDeWMTC0XphqqqPShX5hUzKL7GrEbm5RdvR%2B2vmaUQ\
        Lbtl7gCICx4o3N3lhAVzAi1AMaOXHqgK5SvJSO%2BaWmT1h6CMUJoaXvi%2BvDOjDmph3rm\
        25zTwwLGjdQ%2BdEVIOCaoP77nEi0po2il29fWIaZg0kkqEl65omq4xBLv%2FUd75v4w8Qf\
        fSAoHAETCcose9BjqkAXRDnHCbp2jr1zf27%2FKT4pRTzHpxBnrvPMEoW0tcqvAsVeG8Khq\
        W8tIBRC81NU3qf8rcE8NVY3%2F9eIYVieHM7hFimW1Cx%2BYWZWORmYay4dpva%2F0GlJI6\
        2R9uBGmKQZzftvd0tkgX0KTPqD5ZgY0zyXwLsf050Meii9s9g9qrbnYltMd9J82mzEnQ7I3\
        %2FvFtBDfZ8iroZTGbGwTP4Hnyu8oo8bdOR&X-Amz-Signature=137000b30d07e1426dd\
        733922b46949141c13a5375660c0ce25e687e7fd73241&X-Amz-SignedHeaders=host&\
        x-id=GetObject"
      expiry_time: "2025-02-16T15:18:54.947Z"
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
UPDATE_TIME: "2025-02-16T14:20:26.625Z"
EXPIRY_TIME: "2025-02-16T15:20:14.704Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=474c7794c4ddac1490dbca3c98bfcd292e57698d9ac58e1ea7820344a825b4eb&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=40b7568e3bbea4a02cbc55a8cc5d3d7439901ba0d61a9d64459636504661c1da&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=f2e2f384387a38fbf2bedc554a29bfffafea675f2939a7b7a9cb186f6102977a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=26f78a8a8a74ef01e12992422ed1ad0ba7afbb93ddf17215fc55b1dbaab612e0&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=c4da9fcea6210235c622c69631465e93d335d54fa026141a9dc3c2f7174ae884&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466UJTEVO62%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142016Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIAqhGtfOzJFm%2Fxem5O6quWiv%2B2T6I36iPFhuo6x9LaePAiEA01GHF6zW%2FncD8BdeGBNQT3GhR36NGh%2BPWUM7D8DWJSAq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDDznFb8KFxvB2nzG1ircA96WqJs0Cd7R%2B2ZVBYLq%2F9a%2Fl2LaN3PiEiHuNEAaTaRpbLFthZSk%2BWX7yc0xCVd2iQH1tNRnWtK5poPuHUpon%2FMV3Qnkc5IhdCfhX4urOavS41EeFWrVPqDRpD8bB233LhFrxxM0pSk9g6rLR63JF88dEVud%2Fq2XzqepdfDn7G3NNQTzUxsHthMLJxSjosE8Rlrskklk3Xx6NlhibROlEmCyMclTC%2FGQFWf6O%2BZN%2FMTsU%2FtMgq2W86nNGbwKDx%2BDGrogncGgx7mdkyB0gxiy8Vr7InGZeLPlHewTbxpUL3%2FSl8h68iWtlum6ITfLyaYBQGr%2BLtOUHlvpufsaDCbdo2FBk%2Be5ycoG6Oj8TBHMQkz4xEBGimSXjXU81WoN3MJVGp%2BUwmY6e8lMaFjMbmv%2FGPTZugm3%2B41uXx4bQ51TleIqBAxuge%2BnLpmPM3gS%2B7MArxltig7AV5yae7CXnQLbJhQLbdTav0q1ucyHrdy6qdBG38k4bgGUz0PYKCdFhdX%2BIR7dgrU8ICzf7qLAZuwv8xgLNUyxLSJahfIuja9bTQwmBilFOSb%2Frx1WRJCwrcqVHZKeCNqMJCReAX2QKPdzYujJp2oYQ29zscyajHj8gIFoi3K7MWm4rmPpRalDMJeix70GOqUBftnj1tX1ySZqd84Mtnzm7Vy%2BsbimImMd1gqnvy16HeteF4ORNADmkHyTU2WHYe69qEqtkxw4PntyM47aIXk%2FvzTq6Vp8bH4Ox268H%2B9YOnO0WQk4kuu0d3Ld5jkbaSegpekYsPHDl1930WAym7YMl7aoUz%2FWU1u96sHvP13kvYn5yMSKBq4YJzheEeEhkphLYZE0ItFWCiCsKx2RK1SjQT4etkoV&X-Amz-Signature=0e82540007fbab6ca112ca0e8cc2c13e53bd41d2e54ed531a15d37a5da2028f7&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664NNJJ356%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142016Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJIMEYCIQCfS%2BBTVcXYvZDgQrTZH3uQgX3xHN6l0qA4SYqzUv7Z2AIhANdDihUEMLArmwBHIBRrQ1SQt8Wqt3pb0bc6bHVlwhiiKv8DCF0QABoMNjM3NDIzMTgzODA1IgzJY%2BfLSejls2vf7Swq3AP5lEvMf1Vrffhx2jQNNJ3RmGTXsJvuxrHzB0YZVfDo67z0kEjlt6w9CBUDjlVGw8lLoxl4G0MNTEbaY5DlvfH4JwQy0BGyxN14mPZFD47TSSgufFtrJ0vNcEKsOLkYJVi6phgA0qDOhJn%2F%2BhUT8ibqRbnjHOFDRp9FdoNkkBFFYLdT4Q6oLo8Bv36Y%2BD1HOS8EY6aCcX7VMmP74ZiJoHq9%2B1kCX2VEg2xLMFoVOYbSs7i%2FGv7386prvjGiWgC8WDzUoyVWZIIS2QS5jpJ6KznRczXXTWoG8mFBSTkZ3y9mWXnTzAcwof2cc4MrqWNANSh0YKV96x9o8bb0nGRGtdEJcwJRbBLgWfni0IK2idNlQrlK1u2HAO4Adb9YRlX%2BMUYx1OqnhS2MDZcC%2B%2F1eJQfj9GHQZQS0pPyyZiH7ZaDAL%2Bur1Dn15LjCzwEpod9PGQCR7%2Fp5ZMHKLXfSscM1Cu8orY1IzmLge%2BlFSjNzlJVkMIPxITIQqYF0cTzyAfuCfOAwEcGoAyn0gx8f%2Bwk4H6adrC3J2t%2Fx%2BCi62vVNs1aUTX0kHXm0UyM%2BPHeTsN1%2BaTYPpziCi50kYeZh7WU8TmCE8xLCjfbaRTyI%2FySrUVAjVefz%2BmwS6D3nMQFVLTDonce9BjqkAcv%2FJU%2FNhsLF0S5nq1ObnJ3td4jioQqedsqkifYacG7pwo9Deak8i7BhApM2MiqboKfbqrsak187M77Nn7%2Bl4fQwwuvoItpBICR0s8GoEZtDJbgJYHA%2Bn5OOg6uvHyJOeCpGqwWrBFIkicPxn15hqORdEU1XynpWtIswgoyHF41f%2Fi5l46VsFGV6dcTBvbs4UCpj7V%2BXKRntbI3oGlydMKOcYkQt&X-Amz-Signature=a60cc3eccf48834a9f7c974c12e4f7009f19d4ef59780eeb37d98a1431dca63d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=1e69a0912609cbe7724e0d5f07881194b59e24e23203fb28c6b90a8dc26678f0&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=44621c96d1836374540e5412fd8b39a71c9c08408e5f2b9c7fafef5ad95d8dff&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QTMWH777%2F20250216%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250216T142015Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDQaCXVzLXdlc3QtMiJHMEUCIEnnRKXvzxeCWzk1gXCwmXNIoF7QQ5g9iRoz5JTVjMT2AiEA8HVk2VHKqK1YQGrYoIeKXZimOf%2FLGd1xu56d4Mlqmysq%2FwMIXRAAGgw2Mzc0MjMxODM4MDUiDIX4v071YFCojJkpQircAz9vbceI11CC5Hq42TRPshXNolkl%2BTnUsiASaSghzhbZ0HvT%2F4qZ%2BBzk%2BgVw%2FHl%2BRY9eQHeAKqrbPDiiu1sagXgJei%2F16KFmkI4DuGrAmX5I76racLnTb7unGd6JIL48pCRMx%2FGyoGP9nyDODXOdYM5lW4gmIpxM9pwBs%2Fs0MFSYzmwvXHmtoQ%2B1w1mlt6FdI%2FLtkpZKav9dVlhAXLXN3oNPZjfFb1xrFE7AgvWv4rXj5w297hEhgTE1wwlzw%2BiZ2ZlViY40mkFjpynZI5rRgT0zQ7ZZdQb9OmOvw88C0vmehIuopHsEM9%2BmfMzr8hL%2BHVo78%2BJHsBWvr3lNdGHamwX2j4bfdSAFRXakQDEK1u057AfU5aigSAaVTm653uQR29oytUFXreuXrqb7lbYvivN1dgW0%2F9E0SBwo8%2FiH38iNjUFv%2FHVBvo7JqBE6W7V1WwVPP9I5YE3QVbaH5StOn1dt%2F3YO3GC7%2BL6GEmp8TBiRn4jVAs7fwnqnsc0cgGw3UErn073EoC9U9wNKeitG1Qh%2F%2FMPwCmO2HOi9gtW59wE%2B%2BAKakhsKFO7YhlKCSikwSotMzuwbtcMI%2Fgq1heiZJqkJr%2FHsJRCT5OlgF7Xb3PXjoy93IivTsEckp1YWMPWYx70GOqUB%2FggU1bkCq2WHg9FawwdBvxXUAjdKe9HB2%2BSKKVrNq1WJkKcqoqyw%2BPVfIBcamiyxZGXcUsDmFGFNGLaPLHu%2B9S%2FqSJBUi8Q6AiuDtU2oZ32HBvCE%2Fnu3DbLKKWN9ovLs7DGa7njgCyOZCGpKZpRkJPCycDKPRqFuUAt%2B0cFpV8pn9lw23MDK24XCfQ8WkGouj8h5Nz9v0LFGm5oFtS7B9JNrdVGp&X-Amz-Signature=e986329eaf55101e078c23530709fea9f45b32e5745a70d4a52be01f744556d7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

