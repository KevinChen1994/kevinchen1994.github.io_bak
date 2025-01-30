---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666ZTLUO3J%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T063130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDhbbgv4osVCK3LTSW\
  Dt994UI5wCPUee8JUqlpqKB9d3QIhANGxF2UgPgi35hycNvsvgSpljWhQjX3WDOET%2BYUgkKB4Ko\
  gECJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwSg6c9UBIDUFdZv\
  g8q3AN5RID7ERLdi5dOMaFV0dfMWjBisYgjxvrT2jnoQtKcIlY9IXR%2F6j4QziUjkrkaaikvXqZm\
  1SLYvlqwAC0sysedwDpBCwdkWFKA%2BdxKgDxPk%2FIkkG%2FR3ZskUz3M0b5ybS0E0tEOyTOK%2B\
  psophxUg8MHDUJUXTdo9yCyo9OBR5oPU9UgrTKYBN4yokDIR52nx052rD8ThUggxQ92PyY3tM%2FH\
  70TLkkdIIJfvzc1gZEa2Hzhu%2BMoAkChF5A%2BRR8ySQYU733%2BLySObNnXxg8PsEEhIMa3oOry\
  XL0cycfhOAQLtwsgsESnOHAPKgs4GlxIxgCKDjwbyrhSbA%2B6nriz4p0MTPg%2BCQZis4UfmJVBy\
  MnPEXiCoqkXqo%2FOlbQ9muGwf42Ay23gmVMlwNeryonmGBv2uMO%2BODZXaidaH%2FcDMyrkDxhL\
  Qfar2pJjuzQyBYugWLHWfIcwYC5AznwdZeIUMNXGsKoZwvjJyGmQkkvs1P%2BAIrj9rMouW46gNUi\
  DgvZGL7uX3oooB8i6DrRIlyNbPIhFfvA6upogbmTOoRlAH%2BBpMdOHk%2FfE2eC0w%2F9WXP0bzS\
  sKt2zh7bfdZCgs85jFXVR9TZkVzryzK9CP68vkxz5Fn%2FnyfSU2INtKbtWfPYzC4pOy8BjqkAT4v\
  fYZpvHSNkyXfn4Zw1I1YOG57k1UmE%2FPD4xlyoIc42%2BjjWFpSUJ7VX0IB6cBjHIvlNDlMFeRkg\
  hmBzaCFVoft7oLiAqydCNIUDKo3xLatsTTeixR%2BPmuYTrYPeK26YzSd9R0AFVc1Vu0AwLFywOig\
  xB7dlwibbMpOHDHcMSU6qK9XyftCHFYvehfscct9Yw%2FntBv1NZ7kA7E%2BYq2jnPzyzrdq&X-Am\
  z-Signature=488b9a670e676cb48849d35379358777fe715d3f49a592763d94901ec37a6900&\
  X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466WQZSDQZY%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T063015Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIBDSzsECSGspLQ7PF9BuIEmU83PG19ZlMrP6h4kR%2Bhs3AiEA%2BpPDilCRu6INIpxJ1k\
        Dcn%2B4g%2FFePX3dCfDaP820bIfgqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARA\
        AGgw2Mzc0MjMxODM4MDUiDL8icUWyfVC2xoYGyCrcA%2B2T3nMdfUHH1MMDyKr0LUTj4ecO\
        6u8PQWjC1%2BCMNwp7H77rNSStN5xL%2FZAkKdA2kJZrNUUVZm%2BUp2UA8PYz6EU57X8jH\
        9R%2FtxMa6yqwnoUOFc7SgvDWa1eS3WE7Qp449E2y%2BPDapeHSE6KwehdnRUwdl%2FgMan\
        DmNWiyCE2og8UYXM%2FcrG0%2BFLfwrfaH7EQJqLQALcqPAX7JWvC0yLkcyJxajF8N93LeM\
        qGA3tanRruyqnra49dVCjlSj%2BWWSX5os43tEaM%2BUx8oszLhSIrDz7eyeSR1Nr74RBEZ\
        73i084RJA4iHH6CQd7y%2Bqig14aAN52kgeeesiJJbUXjPVZQELW6O2Ovu1ZoGV6eejhn6K\
        pDyaBkO85nvE0uYiPhLTQIXIwmcPlsKrppo3Ldqzmt1hmcqfu1YS0oZ6FmvsdqMfkIZknYg\
        ENtxd2x%2FGgY9HYo71RcNndpJXjBmPxo8fFzsdNuVYtm6RChNKIjlCuKUfWjXJ3iqE44d1\
        sIsO8dude8I9BPYNe8zteC6DB%2BirZxdRdyhFPutQw6AkJGj4mBZzNfFSF2KccbXJpmLUv\
        rGxHf2RihXfJv7rZeMMso4WwgXSJOiAf%2FZJR%2BZ5AeysEzA5sjEJnExJDdrs%2BIcQJ6\
        IMM2j7LwGOqUB7ub8iSOcMZSp3VU6UEL1ma%2Bu95A%2FiWhrlcBDLk1JHQG%2BOlfS0RIz\
        eanYXEqODCnZLFk5Y0iE3uaPx6DaBPeJnOzQYodwaafBoBTtHwy7szU%2FH9E%2FWrjO6i8\
        ImHMPG131uZvWYiGsPHOYHVq%2BseCiXpN9td1P0vAQkzhTtdT4VqXLEhT6ldD3xw4YJDHV\
        %2FYdBVGwvQd6P7sz6d20DjswT5iVrp%2FKF&X-Amz-Signature=1c232d2fdc25b74815\
        cab260bb25c7a7397c0beb22a2c669b4db0e932a96eeab&X-Amz-SignedHeaders=host\
        &x-id=GetObject"
      expiry_time: "2025-01-30T07:30:14.964Z"
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
UPDATE_TIME: "2025-01-30T06:31:35.484Z"
EXPIRY_TIME: "2025-01-30T07:31:28.405Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=5ee435c3655bc8c19db908afde2fe734feb1e498fa30a7f9eaf53e7c2a6450ec&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=24200e85f9c444163741790a14654c0d4d315efd126a22fcac9b99413a79e55b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=ea5e9cc33863874ea5f843f339a3b2ec0f7b28beabd54cb9c7579f20fd6f166a&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=f786f11a2989c423910d6289532be32e2869526e2b5f0b6758558f338888d349&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=6447107a4d0bf3a28e648c387c22dd0d3e6ee5536056e8953101e525c1e99837&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665VFHLQYY%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063129Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQC52L0A8EtHmUvMOjer8BMkYqdjU3DIg8hzDv1j9JBkvgIgdC7JIHhPOa84tkF3qIV0h2%2FDoJ9OwZ502tlM1fV0EhMqiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDBginO0vVT3sQyyp%2FCrcA4jyEW8rlcwwPuOZzNwg%2Fc6fkCryE%2BGHfYzWftIu7b2JE0XbO5IvMQaRQ%2BTdcbggabxV06ykeixSUnj1Pq7jscZU3zOmhdckzu9bFBSmnbOFHzSRyAyuELV%2F0oSPG%2FyaNlqYlM1IVcBy6O%2FEhaqUKfyzaQBc2R4YA%2B58qLeisjBYVcQK2m8SyUXNqFSN%2BMDg0PNVanOEWhWycNrv2sOwkJHpKVJWrXhlGIOIg7Gu9DyBNUBumL14rnpgjH71muDe%2Bcr366Ehs8nYIzKqUEZyIwbXRk6O63Yd7wJjNk8cdJLUqkXFiJ9h58L42sz73PaFApCkdyd%2FYJcqiR656UT%2Fud5SWjKrl%2B1nZn2PHpfegsAI1bICBmtGiJYGKr%2FGQm5cXWIxapA5aiZaQRAbT7in%2F149O%2FG2wH3YtyfrZoFQEIXfTZuMGeBxub4DeWbHh46xhKY77ByzcYdGOqrjkzDyeewLHqPrUlwVvonhuFCdC04yV34zcHk61DSDyI%2FZ%2BmMZ5n9oHoFYpvkm4uMODIgIuBflo6Y8be4LP5MCwDK33Wz03KisulfRK5CNplqKVg0oQ07bBGr%2F7kopX6bl80ibejzcVGr1SZcTK6Z3EWjSniyQj3%2BNTJlSVj%2BJ3GFXMNmk7LwGOqUBoWiTKLjnln%2FeKQXKfuGA3J6UCeOrkZyAj9X9voDkUKYjon58CQAlL%2F9Lj21a2P3YDwC5s%2FJaoI2lWbPL7n7IBvjcIvNQfWolGVsihjGvs41U%2BzsVjO8Gate6NC2SvPW4P74trS1iQaWiAYe2%2FIgtVAlya66lF5T0463GUvupyERUzoyETXuCM%2BHG0x8flB712FMr04JnniqYDbRTHo2WV4Zlekeg&X-Amz-Signature=ce226b26190c6b738537dcb6e68a79f483732b8b56cd89c164704d2d4b497b5e&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664SKZULRK%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063130Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCKsnjFy0Yqpn96FM7gKnsiHVEt3qWyat4rkzEvT%2FVMRAIhAOHWrKv1YwngE03lHUce5es0ut03Vvtl09LxF0O4f9uUKogECJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igyudme2S1DW%2FV5xoZIq3AMJVupiszdjZlDk5z31Y5UCD%2FQZ5NEAp5u8nvThzPiS%2FAjYsaQvf130jYd1yO8tUZwj8lftyN%2FO4F%2B34WSduAlhz4F8x0hCpcTQAeY8%2F39VyhEcNMq4kK%2B4tOegt50QKsNjstEKrsyevOVTTZOM1CJPsGEBto3RjvjArIqFoK7HnmK4ghDfePwd4Q0Gxn7iqscffRxT0%2FWC7k%2BjABbXwRYiA%2BI8BHk0QJSHgRoOFMSv5Ukvsj8b5OSf1hPyUgpAVZ%2FOHpEtlAlcc2A242TPqE%2FzqqoK1QfQo1fG4kdpQjUEBmE6X1Uz4%2BTMP6RSAj4xmxUEhqYUGDxXiyfp32qgWfWYLsoFtz5v8HHnwPwWCVGDr6hE0pShFlWtdGzLppEeubcD5kO%2BVxF%2BCim%2BnZyGovzsnMgSoP5DUrzpoOO2%2FcJAUpvjMBNDN1ws%2B8egRdaQBDlq%2F1PjHdxgViqrZaQKDObVPbUI3e6TrPZbEIUJH2R0fdQM5LLv9XYVrrQ94hHh6AQ0fO%2FgSyxstCxdToaR7pfBwwemjoE3n8nW39fu1ERwwbCX06SEnxAJ2pW517E9YtXeA1cCfuIubvkRBi4p6L2OrUPdNVKh%2B%2B4KHglZLO4LQTKSxuUjOZOZSifFSjDWo%2By8BjqkAZeSpP69mdhq7zf9Z9tJGLrErSZ4eSvy0XPfWCyLI267PWg54FK%2Bs9I09nVmu8PYmeVt2v7Neoj2D5oVdVRryyOaGl%2B4xj7hiqnES9dn%2BLveeA9UA%2BQeXtZDYHnlzcxok8xswg5oc4GBKWTjQ257yqw6%2BxMVbsf%2Fw2iWG3GFAFShTg%2Bl4T22fcpxD5KARgBOjr4w1ED8BY38h25s3wTLraSZtC0K&X-Amz-Signature=b83002b623bf3aabacaab5b1bc7de4783a86c7f14df27da8a5958395fff4b99e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=2a885836ae0f20cf6acce8b1cd11a1209028205cb8a3f0a5e46cc532e5559480&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=3b40ac6b44b46761af1f6b70b4c1f95edc7aad55546339ceef0ab25fc7061fc0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663CJI7CKF%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T063128Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDKpPf%2B8FduY7CSkgUTOAYUlvIvsIjq5mRnfxqZ3KFuQAiEApLsXp3ua%2FmG%2FZsSIz1%2FeAHurMxuJU%2BcmIVdmewRkbP0qiAQIn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFB8OZkSJWS8ukGc4yrcAx1JyDp9p5bFcpC5smMbADm3qUkOQ%2F4kD5DgsQEVZEar8OSyznlVwrT1dQE6WpIIqnY1GSKl2VESTGCMIizd4z3G4w0J%2BE5X6z2WOCcu9n7oGYGvnxoCOn4dAgs4zXVh6%2Fz34SCk7wA0itjzir0%2BolMkxmfJii6PaJgprAoZ1diuffCAmSztjX5tDvXIssYy6dWvpKhfSoOxbyK%2BxiC0nzB3JLxU6%2Fe%2BYZRYqgjJPD%2BTpDIhBrPqFXYxLeeUhJxtWKWx1uVcmB%2FUOWwnUFUfoO5i9GD%2BUHOi64mIUwbKh7kYxgRBe1iJqXu7rGkRTg69RLikJUZC2XhnRFS%2Bs0WVEWUVzRSAUfR0fTdWG40rnhOT8pMkKYs7XxMvQVBl%2BOUw0asqWPwSdCSNY7ZMdcJ3gg1lLbIWdSkbfm6La1VcL13IYyzY8Q%2FM45FxpQGXp6Zgn7QfO70DKlfJxq2pxR3qjnUZpK1eRrikFu9sR%2FA1cjWgM1b4oi6ZRgvOpf995Bjg9ZE%2FNsn0nXFedLQ1PSYQlGPkEfL%2F6%2BTcMJN6Te1W2G6D1Q7gvHeTrDVlXPKJT8u9n1xrs8snDTCWI5w%2Fw2yb1I8SI9wyk4HPhptPqscn2s7ssPbE7mLhBaqtzmzaMNej7LwGOqUBf1E7mpj5daO1VgMvvFrDdW8KeHgjDwuYcCmDxWwAq%2BezaaNzF909rPcWb0eQlMOcnKzaPPBaWQB%2FAHROybDLP5xYOnnQISU%2FJMSbNPsOX%2BOkDJmNJQv7OF0rD97jkmouiEN9iLZA6oH1j%2FMlkBJv8BB8Tedpb1briLpgTutofQvZ0J57i9bnAWCGas%2B0pOtMmv5IEmfwIUGlALJwm1rr8jodp7r3&X-Amz-Signature=79bba153411ebaeaf7de7587fbcde1b7686d6e8af726a98edd28d11b62b4447b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

