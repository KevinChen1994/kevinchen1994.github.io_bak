---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466XBWUDU7F%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T232147Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEQbUxCE1aDur1dD0%2\
  FvqjZ%2Fik6ROIuv75t38zEvIlHrfAiAnpJ49Gme6k9KB%2FqhqfgVJJTIB6tA%2BIJG4TlofIqGi\
  zyr%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMypvfj6SERO2VVVTxKtwDkhfsxm4q69fyQwrPEFhkcJa\
  kreU7IDpvGsgU0tju2W7hRs2L7UFDvlCKuEEpbZ1EH4NF9YjvFY0kUmbDl1iQJtMuBlWo7lMyCLeB\
  h%2FLuwctwJZd0Xesk%2FkWxx6DzVKBmSgWYN5B65xt%2BOb0xAxouL8akypUDPI0PNEJh5FTqHOz\
  KtJVn61XVRenlgX68aSd2A4wU29816ZARCW3i5wHVVDC5KYdR45yXJxhgJ9UCRgUU%2F7ZnenhyDX\
  kqhg9%2BhjNwFflAQBXPX2OIPTFhP4xLoN3K2krF1OG%2BjbREYC9NYXovggOLYNUZVg36gSeoP4e\
  7kj3%2BmF4Koo%2BTLAjd36he9KnMaZRznvV5yOpG2uSH2TmYGp3nUaXKj4VjQsPyx0wuxpj6Kv1c\
  1GJnrPZQzgGDqbgom%2B8jEoNMe8obar3Ep%2FtULa8yVg3QUFe2sv06FBss2lrOMW1e%2BN8hd%2\
  FZswnW266%2FxhNce07pWN%2F4hDRMTwttt8w47L4WVBrLLz4qNC1o1hHeHyz5aycL1kQ389Zr0k%\
  2BqP4gmGmyXtuM8jFGh%2F32rdbhf65fZ1oD4NlhoDTCHL55PgQLQ7fa6INvdDgiMhtuEzfWVETV7\
  uGr1wNlqhBqlcJ9YvI5o7AzrmI8UwprDuvQY6pgEsIBNHZYvxBJz1cbKi49iVaG2O1ptfYc4A60zC\
  TWF2IFuisGK%2FJySEHDPsNIBCYUqDiiGeQk7l3O3%2BioSIUSSAlrBOQGIYx7WeM3pIHVRMl4rd4\
  e26oWNEmBz21xS9Tm2NLaRs%2BOlCSME1oMjuSr1gtQXENNB7Rjb0DV81RUKSz%2BeuDsdZDkXwFl\
  CI%2BEcw0Kpm9UYEvs0luoTRiEtf8Lh2nCqRmiZc&X-Amz-Signature=7844b00f86f125ce0559\
  279ee18c1384903b860c472ead2cd4237dfb099b2bd8&X-Amz-SignedHeaders=host&x-id=Ge\
  tObject"
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
        redential=ASIAZI2LB466VD4ZI54K%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T232016Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEOL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQCDip9t4YqyfT7deN199g82F6HdIMGi%2FVdsTf6yVSiMTAIhAIkqCi4hpA5T0AQ9skvL\
        fjAbVg2LqGunlt62NhjDkYSKKv8DCBsQABoMNjM3NDIzMTgzODA1IgynhtFGZxcfTjTq7B8\
        q3AMTv9vfTrt73iFOtuz8X9DdavyO2XwhQV8O%2Fx2NilBi7X8EFqlFnZv49YqxVGRtoIVO\
        %2BssSbMf8pom5stPWvsvj1tvZyxafCYxaIUducDBIrC6ZUNt4Hr0%2FxPx4VL8nk6UazVJ\
        HFQufWkoOPXnqI3vAxctnpZPbveLEbHN83XQMju9tZGQ%2FOVJkqPGp%2FP%2Fx9b2dZJTq\
        %2BuXbJMZsK6zS5rERu68y7dqLvmalfIRJ%2FaWQqJeShHSNmRAspbmM07H09HGF3rLWdQO\
        h%2FWOuh3DUvC6i1RV1xfC5HZItsb0f1QBuxZOZEBzkbQtz4zgodjXxNRfnZgvWUR9eazw2\
        %2FIj8UQJ3rqQ%2FIjF5zTG%2FNTjETe1ojjzpfC9SgSfjvYWc%2Fv3LPKaqrAXu7etyJLQ\
        %2FxC85HJ1BRU8fPqlINtwZUamMK9DERHayAlm4yLs6NrY0DycMVCZZ6rbg8ji9Ni5XUsSa\
        %2Bek80ARxB47rwsamEhum8%2BNx6o1LXMH3R2yUitc14nRfO0SM%2FMVV0t9f6xvGQmbwF\
        8zp0G3ehV5l6H6qA%2FhfyJscfVh%2Bm6rV4YEwx%2F4sCdpEZl8w1pccZ5tfFqHDoacVi6\
        5pMSvS6X5qTam%2Fpvm%2Bxi%2BTBZbSukayTpFgT51eKDCLue29BjqkAfQCgC3SzIzvUS1\
        %2BNxeOESJhhKo6A8qMBOYnT4yU6D%2B9dlDjV6f%2FJ4B%2FGeVj4Soe16Ey0%2FqqZHO0\
        F3IR9FFCIUzVxi2uQnBE1ObLUXkEe5VJxQ5jeSVEo2D7F60W6QF763M3ktlhbh3O34mUqyJ\
        DP8aRHtxfv08pRCATvU94XtDo4HUTeg%2F1oHmOMhlCO0OFDf%2F%2FL9sEWxu%2B3Ik%2B\
        a4uf1kbHJV3N&X-Amz-Signature=e85d08f56f2f6d6ca85762508a8c218b523d331634\
        c3151b36d8120af3419427&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-24T00:20:15.893Z"
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
UPDATE_TIME: "2025-02-23T23:21:54.396Z"
EXPIRY_TIME: "2025-02-24T00:21:45.382Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=917412ce37b75d7e6efa32265e2a51314c8a93b297b87b3250da6da0517e27f5&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=4013fce253f0dff8790fb93b73f491a48e3c7cf93f7605a5ed3e38321e375029&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=bdf7e53fa510f138da50d2e308e9e5928d8d5a9bcca6835b3ab8218527cb923f&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=d33c2407683004dce39b533271d761b8f853133a5f8bbe881307f88c4bd2b936&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=9734354d8af91ebd9bfa39eaf15f6916b5ad951e9c3e32ed176d886b9aa6c8be&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666RANF3LV%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232146Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIA4X7mo8cp4i19ce3HXgKD3OxlsfCDAWOpSegV3NTSM7AiEA09QaMaZsRIIvaXybAb6FDH7t%2BnhYV4XFphyzMyyMMzUq%2FwMIHRAAGgw2Mzc0MjMxODM4MDUiDAwk7uDDsa2lhLzxTyrcAwLoOt4dwFHXT2yW%2FXqQBhObf3Eh4vDgBHnudk2nfZXzeuA1Lcbja9EK73nO8dmsnIRr7qprlFbCZzyL7RrJAR8rDg%2BMTm1CCo6Tfl7nDlsFzytWTwvrX6qGyJkSsZmKV2F6K4MuOabnPVzEBEgE6Wj%2FB95kU5YAIWxnAuk3EQMxwjT%2FAJHV8nagyakk4O1zOVyVF967XMVRWR1NTll7MVIg75vEx2fZKb9Zonr9FheuZZEAgxolVdELpUsS8qppnt3V%2B8gc7AP8dJ9NXteaOawGjSei0XjQTyqofLt%2B0E7O2513BAN%2BMuRKTXfDBBaXIEEfY3j2JPhMpU7zup8gHXIRjJtMTP2UqZrbETGFXRS4CiadmkbhtHklSWG4Tj8zOmQnAyZMQ31%2FxDXASp3gRFHPZkv3flGvZBr6q2aZvg0RVWHcU0oxbdUXyMFHv3RcrhlG40t9OyGmhiGA1CCdNRKDIPinQI%2Fbbo8ffEBHpz%2BvkzJHFd7gcTXD6GGA7SWJt3eDp3bzrRTsxOh4ddEPacZ7ynW3bu5H5YqRoAKlFZmi3Q2ToVWmQkFGp6yxZBNUA1j2v1p%2BsD4yPkgH2BZ2FJjDJ0O3sVa5jdp9eImbrHg0Cgey8RIa17PACLGQMJT17b0GOqUBANyPCeqUp1VXiRe4sgzEbGWzQnAwUt6fkWb9BGNX%2BOqYnK8oXjyL%2B9IRdcR0Wl1XYOTcmPGT65h73HMhp1IF%2BtQraMQ0LcFf%2Bm2tG9q6U3u%2FKPB2sNdsa8xYecWHPSGvHp12aLZ%2BKh0gJv1yTwuWkK4robsSZiobBiJ9bmBSf96lrwCLYfAn3m6Ym7L66Tobyzar%2F2Q1XT%2FjlcWdehSDrjBfsdrt&X-Amz-Signature=807e89783d4c724e58452295a47b6ba0cedcdde8e73ce4d914fdae00c72660f2&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664Y2DUPW5%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232146Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDCq%2FUtEPlqL72ZAWW%2BINV2cehODkvQ2Xr%2BjrfWytwc%2BAIgJ2h5asokCYLdwN95YxhhTec7nIdrESWKoz73XZrazxQq%2FwMIHhAAGgw2Mzc0MjMxODM4MDUiDHQcvAhKNi6Lqm3PaCrcA5De%2FMnxJ8CYMUnunYAIt%2BGQwOHCFNs7qfQTSOlqB8vcX62ievtqZzjrpPFb7PwC%2F5GymzVskX%2F4Zbnb6CiAFVcqBQKC59YQuFMl6TQiXpQRlFJOJDxQiWNbs%2FV4GsYuOBHVD1IGg0yBFUSGvSvZxDkzyLH6YcOSnVweoEjsIqVBvfZnQ%2FcbdetZ4tbVklAxygRC5q%2F0BP%2Fw8rttjBvDlVM020DGsK%2FJf%2BwuFzGopH%2Bd1M2xggggMN2%2Fl6%2FevsTfGPxe3PbruulhWKiP%2BHPGCtwnLPu9vcurOB1XcfLKlJiL67v%2FTYb8wbgCRdIL4TLbeSepbBqneX9qkqJv24OLIgvitTwyWmCeIEVyUVCNTk%2B6oG6fv9wPOJTaFa51RbSHhT5iezXif6KHw3aGi2lbz4gtlb7uK3lrANTyhBedaZ5vfeGFSCKM1rboEGRc8lmY9Rdsr88lKmptBPZKdHJ6OeyH1PAEJ2dpbCUUYhuJsf0K8beHG8BOxmyVCRY1Mn7xgc4yGaTdr6uUrvDyR2JYBiqMklPM%2FMZw5JbZ0nBQQlCO51xKp5hu%2FC7UcfUG9xv6EpU7eXemQZigoj4f%2FLlhmFDVKRfXSoqzLob2lak1tJbr81fMq6W5hlwxUiYTMJCg7r0GOqUBksdMZOQ0%2BiBvIC7%2FW7Z40MOnoHjLnmxlqIPyr4o1wIshD3fJcNYh2Szz1hdIF%2BEuOi13NmnZp3%2BqQTE6tB2Aoa1yji4GERoFtHuiRj7RQoVX6CZkMj1q4cg4dptZEX4w6ANkpmqKljwLoj%2F0hwlZiaYyf7B9MDZ8Baf39ryHBA%2BMYbC%2Bo0HILE5tkku%2FN0HdG6AI27A%2F7Y3Ou%2FHBXl%2F3yFugmKWb&X-Amz-Signature=b634b7432bef615dfe77128a7802ab6668ffe8ed1250c45cb001af5ce22a0245&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=655b1fbe4f1c5853180d35fff5883f7edbaaca66bbe06efd0b908c7112521c7f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=5e109abdca9695638a9e578fea4546d2bbcf8dd49ab6681f536362c98efae7f7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466YJWYXX3R%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T232145Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEAT%2By5ABh3l75qMoVhanaMFgpadT5G4AhhINpgrUG%2BeAiADitQvSr8eLboL1ZbEbByG5gvjadluta5FCtBSDNszJir%2FAwgfEAAaDDYzNzQyMzE4MzgwNSIMmUBB29SYFVSs0pdWKtwDMtBbVpfdGyD2Uh0kpoycsownLxD0FBNhZp2FdDZkBJp85JrDEuEzy2tVt%2BnVu4Zlymd%2Fav69dDP6b7nwIlaP0XzjcbR6A5%2BxP8Wh4OqPHNt5x8RFCH3ByS7AewLye4hVB0tqJkRdScEfsnI2exLtxqm2hE%2BQoEalo2Uk1xTmCogWa6Rr1RbYkgmjQmtiXbHoUdgaY2p12%2BBtu2mJyiAJnEEo6bJ05vaLeq1kYSBbqQikSOQChEnSxvlOHQVL9hxf9mGNk5WvRla6fKLihMh35XrIeCUwtZfHlNLOXAxtNUYl0gf4KSHg6vFm58onAfCG%2FATXNScaEOQTpcpeWCsAhnOI5sbmietUAmETkMnVQupjH%2BxAWOmmEN0U4g5aVpPeA%2Bb07nYz%2BkZwd1G59lss7UCS0Axxq5FH3fXYoUriLbV7%2FVR8yXoUYa4JEPgCqFzJVrb%2BMaEsfYrFrMUQUqpRz61nT6D2NYNSYk34IPlMetf%2Bx1OmuztFKuT1rrXVcjTEGw3OxmFHvFybVITerDOfzBHiMxJVUMgsSroQUOAQtmHLH5fXfy4BbcPgTDRANk98DJM0uNaYNN86Kxij%2FxpsZ1RI%2BUJn8EjxupVRCZE4sMWHt89w6JzsqeaYF4Ywi67uvQY6pgFxFWph0Wa6v8znSYtrrh4gJLjbVvJar1TA4I%2BKSunUQG%2BPydEodAYFF5D3WKzZziGx%2FsNe1xibbQAnwqzuvKxI%2B4AdQDIiGaqdaP0oiDyNh4rAxjZILmCeI1M4MHoCJDFUGjWsb31NKNMijQgwf82DgjIPY4KslHnQXlmwyJYiD1z6u7VFM%2BQfTuK30lbunjU861UDGUwhqcYEXrs%2FzpUAlYIemVmM&X-Amz-Signature=a97d37730c3749d36cb9257963b57bd503e94bb4bc55d1244e32c1b5f08e2b83&X-Amz-SignedHeaders=host&x-id=GetObject)


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

