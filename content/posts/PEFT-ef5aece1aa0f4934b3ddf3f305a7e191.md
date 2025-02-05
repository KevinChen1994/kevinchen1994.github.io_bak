---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466T33CMTP6%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250205T232253Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDcaCXVzLXdlc3QtMiJHMEUCIQCHvl5sPeW1ueNXO%2Bk6ixuvFKvMefNs8m%2BjzxzPSk7T1wI\
  gIl9oqD%2BkIW0gT4sWTStmJ3x%2Fg72pA34HXY3Hlk%2F4ra8q%2FwMIUBAAGgw2Mzc0MjMxODM4\
  MDUiDPqGwA05hpRHWQ0ICCrcAzN5ANSs0fjlnDEM%2B5YtNPV5aLrvq%2FcZneZbwGdPu4gk0FPUg\
  AfmRIZXrcvTpQi365winrvmdZhiG8DeYaZ0R0qQZkhMAoZqan90iMa%2B0etUxMOyRspIUpWgwZCP\
  lKmhVRWigt9OhgLytl1V4uSLEnYdNpcGeO4xw6WHMcp%2F6ir3fe%2BHAUjbzGqyFe45pIOjsjZnF\
  YOkQVJYE%2BgUHKmBO4u8TABHhUEooU%2Fhh5cpWYi9io1KprWIlvrBrTtcnGvsA4temBMqPs8W8e\
  8qG%2BzvPpFmimq9AqfRw7y5oqWpkHx%2FZWYNtxDTtgH3LyUMYJgfAN3xdJXzr689gO6%2FB2dwO\
  Sv3RxX8WG%2Fx6qdbXyuzUW6ZFO0U01sZdiYTytb9Q6DGUhH0Y0kvLn2DiiVYD%2FFowjtU3U1436\
  nv3C1sj7GlQBXRqNakConG7N0xrlhrciBHIk6fHcDMZnttToPrBr%2F%2BDjrTgFJyZZIuILAm%2B\
  vUQLOB%2F4uKb6JsL0FyrejacNh28GHjQSjb6pfUkuOS0ZyXAe7dYLdJNfVlkd5BBrHp%2F6lgtB7\
  cccnjyvwkHxOD2MBqYatPZ0mazkk8DW1qm%2B8GjfT6MNaLLpyFFPUEi%2BcqcRGkxrnlZLQfr04%\
  2F73p0jMM3bj70GOqUB81MB6E8Dl1ZALn0vqDKcmPoT2ZWGz54Kr%2BF%2Fu%2FVMmY2JJpHdbdij\
  lykT4L8VxsOLlu0YB9neDpWKRNpZfTa8YFxai9WbrdzA2TeNYrUMT97RxUjiEV8D8wjhPmZEpNvsF\
  L9H12C8qEfUmaW%2Fb7FO5U3AGRLIm1STati4MnzlUcnjQ0SOfYqOeuhuF3cS%2BqS8y6voL9qoft\
  lfhXVLP5QfquTsxHjK&X-Amz-Signature=4d35a8be6b862307bf385a3f8690dd8e574873d806\
  54f3585a9f5a6d0261c6e0&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662KVHOHSF%2F20250205%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250205T232119Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCIEeO0px4XhXfbPNwK3Hf%2FvkQPrP4k\
        aLoq5Nt1yYWg%2BeJAiAkhLn2wco9wLJ3Ahh2VwpkFKmg4rXbZOHPh%2FVd%2FLEPZyr%2F\
        AwhQEAAaDDYzNzQyMzE4MzgwNSIM%2BXOwUxlFngBah9gfKtwDLQt%2ByV15cdrQwOYr%2B\
        yI08vMEC5rb%2Bcpt8elhXFylrPvnxdaon9rvHv9jkoBCSqZhYjMvp1%2BZXHotwWi8EXqQ\
        QppvHeZVqg2BifzWrjLA9aBJ2IqsuWzlqRgoI8PbPMeVPIgRx%2BkZ7GTYkKGywvGZ7ID5y\
        qhSFL554nxEk06vrEREM8WuWjd45SdeasE%2F3AT1O5dY8h%2FzZKw3apzQUC8I9GGBZZV6\
        vNSbLunoN0HQuU6Sg6s0%2BJJfW%2BV8ieZjG%2FsUq4YBr6ajnsuko%2FQPD4pZTlbQScw\
        wtkOfVa4IYDsyBZfoA5BLomseUikSULI%2FHQ6oJEoquHERF7cfLcvRKUj1wC2zJIe5gT9S\
        kPLkGBXb7AfFx81usrAlRO145HYTk4S64XQTL3JUiuXZOgcDVfEZRPm3SNDOOPh1Qu3CSG3\
        N1RV7gNcFOHyIf1ByowS1VN6f1I%2FhQjF9oBOUinAQbLJMab%2B9jQz3dcQG6%2BROlwon\
        agkHk3tB1lgwwoNB8dDn%2BioARv1a1jwm7HG%2FPmDSXYktDTiWldwbaV3dU%2BTc9p7ha\
        wQIpiS%2Bs6Jtu7Rxa9TX6xiT6SuHhbo9EuQkcHlriemI6CH1COq6UtLLg18FaZwjL8abHj\
        QBe26cEu42Jxkwo9qPvQY6pgHDAlV3dR7SHoepIqVl511A58nUvhb1j62Z1cNH0PgpHg%2F\
        54Pb2T%2Fk8w2OKks88Ol1Qv2fWNEpINsWso6MuqQ3J1FHwP59fQChb2Bl4EJbJoYc99qqS\
        9%2BQiMz5wUDyGx2lNj2IKmJM%2BveGqGZHe3hDmHfUebsCX%2FMlsCeg7cDQqUJ3qJWYfq\
        CEkjZQpSM6K3%2B%2FPGV8E7CaHM82i9iw%2BuiTFWUMSg8%2BS&X-Amz-Signature=1d2\
        4289d06e5e3a5406ea903fa15ab8c544f77aa29231b9ff6922ef3250ee69b&X-Amz-Sig\
        nedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-06T00:21:19.685Z"
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
UPDATE_TIME: "2025-02-05T23:22:57.644Z"
EXPIRY_TIME: "2025-02-06T00:22:50.413Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232250Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=9a0737e0fae0f8d8e8fc6560f86b50d6eb25d7e71992674182d844019a95a1c3&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232250Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=04d154560503078d6dc4a428d5704afdfa601ea4aaea9ae323433291e15458b2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=407e8ab2b6fb5fc837ed639da2f1081cfe18daf6ca46a87a5b1ec0774a7557a7&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=8bdccaf868e922f4c68c969121f1d241c127114f538eb7e47d6f44db6535a7f1&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=3378bba12c6c65a8c12f0f25200e48ff34f8f8a66579a7fd9736d8ac4fca0611&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665TQV3TWN%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICJcAE%2FYuJIcEqLbapjPQERomP00Lpcl%2BFSGXSvchEWOAiAH3kf4rS%2F%2Fqz65UQg%2BKjuzFy4K9WtbjMZSqWuV15LViir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMN34PKQWJcqpSjRYRKtwDKg%2BpeF6QHCQjOyeTYCaXkwzVmg9rlJp0p2Q8d0X7kvXcFBNjFhM%2FBlzdWhvSEzqZ4%2B7DS2JQ7EMwBPyk5mzjq4yXVQi1KUNhanbhWbcnN%2Bbep%2Ftg9tyqXgwqj34Q%2FSgkhMt9JGoaKWPT5QEvLVf%2FuIkxNWt7Bkdtw4qR8ly3L6tuRycUp82yDpmaYZukPAq2RkQtmNerUpfiCo2OIzK57WCPzC5MMCq39sj%2Bp11Dkd5bhpMatJ%2BBJj19xFjyrhv31vfaRAkwA0QYt%2FzW6FYQRfVqIuRxHKi0eUBd9QmI5sW3NsDN4zxnLi%2FTNodEgZKRiBNhttYzoshetOGeVwTMhBkd1pkYh058Z3A4UgtWmh%2FvaqALrI0Wka4VYwYUhnPADCvf%2BLzBX%2FYJM9YD0Bjk5hWmTFEJgL8EwjO8AKsqoHhMLG0lOEXvx9K1BPQvNpX7bXOw3UC7gIv%2BIxMIDaq5OqQMNjGsJzWy%2FWEIb%2FMaA5F%2BU5YAbYPhoFRUlHw%2BjIQ2rYc9rCmeC44ZOgEy2cu7IPgnFJ6fZRsz22xq6%2Bm2UCxZ1OSXDBCBR6rGaymlgNFaUqiGzvRpr1g4rsFcYxBDrcVjvdbeWGPs%2BBXJfskoJQVhOshzte6tlglpQ0YwhOGPvQY6pgEKMHEl7m3Nii52cnXTttOhLi9XXPh5HL9p4N1CFJ8Y%2B8G4wDOzBqkiswLyq2tRV98ycknWejv6PW9zbWt5y%2BvalfC%2FLoPeQIXNbDZreMcdv9W9PXCv93VO2SgOIu6MWt8J%2Fv%2BMI%2B8Oo8%2F7aLY3aFdOxbuMnwpoqjkFOnOmWqAO5MTXytBPVT%2FbxgOkFqBnVZHBt%2F6wWj6jQBNNsBHf6%2BhkQX3RHqDz&X-Amz-Signature=b5439e334d0f340f46015b98774268994dbe85739547d5ab9ac3d1db9edbd47c&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466Z7GV2Y2B%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232252Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJHMEUCIQDa2V%2Blw3cHp4cS4R8s%2BdV0qP62EBg%2Fay7C3%2FQbLIu6BQIgaQEBn65DDdPCQ40l1Ux3Y5H38y4b3PQHU4KjzVou7KMq%2FwMIUBAAGgw2Mzc0MjMxODM4MDUiDAHB1aUfbhMF02726CrcA%2FuFL9PRmiR1hof38n0uc5Ps%2BeGG6o0GPzPEmF071BFa8ECniqc2iLT8vEk18D9tQAbScg%2FTs1Uasiljz60HfItUnhRsm94ZTpQuDK%2BjbI4TTEzJLmTwfcy%2BMCTEo3dHLqFJCcooosZhvauZffjGq842E1D%2BKlZzrFks85dNquyRBOI1a0iAEcDwokVVmK95WebG0V3Tut%2BVTAQXraBDRVD%2FKfeTEQKSStEDkD3p0iOe4l3uVzNz6LPbjRf06BmiToDaOqPqGL4OBXtQI3dRYj4lQit%2FDh%2BixGrxQx%2FW4v1haIpOEnrsBhx91jyd8aIhQ6YrmBVzJTfY5euT0r6iqqUACxtHygF%2B%2Bq0Bc9DcEFHjCItx0clONZF9K7ixJwWHHHIFt2blzJZzDoNhFLM8udNIq4MnZdqKmM5wIvL%2FwV7maj56YvjNbN2B0%2Bzp225f6VOVuYA2t7Yw4%2F2kakg8shL3H0zXWg6zQd0vQg4%2BIw0QE6fxTVfVhb6m0NfMAznO0gor5%2ByxD%2F43Nw57%2FFrQ7uyteSXxzGBcyi0xUAwHFrqdqniIUWQ0LRTo8sX%2FFu4CeQzqgOSHIeuBuKTq5HqN%2BfCPnaCNLZI%2Fwzg96HNFask4%2FDm9GwkLVZmN6bayMJrfj70GOqUBTEo8EdONi%2Fuy2QA2dB55OAvmjE9uLAFjRkiU1Bsmzh1hNe5iQxjU4WPZGc4UmC6JhjkTRl6L3aSD3NzSJ5sMVmAL5zNCzxLC%2B2pwzHW1BJ0E0z%2B2KWDd9O6cyibAKUg7uPjtRoOYtB22rqMAy6ZKqCpNdpA%2FoHHGKQ3R5qWmQKJ32t1MtdxD8%2FJakIB2DRPSetAcgvJmrQQXcbMDetZOd44muWqc&X-Amz-Signature=dab5a6059196ff47e53fdfa24a410880c086926b313576e2bb3b8d8195f28309&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=d4e5cc688eee86010caa11236436f9b73ca0fcb877ae5aa3dbc27a0be362316f&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=0568ee35efacb8875c50803d85cb6c1c65a38d8b014aa2d71de74c111c71db00&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46666VED2X5%2F20250205%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250205T232251Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDcaCXVzLXdlc3QtMiJGMEQCICKS0Ot7RQAxfD1dB4FepMtLKaARLrGknN%2BGOaOozP7HAiAoidGpqn8dkqPmEk8vl54Bqlgfn7Fid3IoWhqtdwHz%2Bir%2FAwhQEAAaDDYzNzQyMzE4MzgwNSIMblML1jUTFDe1FZ%2F%2FKtwDp8pgek0IGCMxFMbPCGGthm63BBNVPTwfOLOcUUc9b90wSPJchPCYJ2S2S7vVoX4ZMvfzIh%2FRyh4q4pjFBJYYuuz7%2F3F4euv%2BKZPUloOXGuS5uRg7wQYfAcRw7%2FgcZZB2VypVUsgPEEquCS1zsuVr2qLEcOfxnfDcy46kwb0bJearztSww4M9c4%2BHE0GO4uaPjnT4drBbc3ybGw7XEL84uGLtoyxFsiMKK19NTVUNf64%2Fdm6nojgyYItIqrUNS7ANo4PqfonAki3XOFEBAiYQ4cuxlPSIlEdHAqR0ViXwbXKE7eTepq%2B9kGOwp1aBZbk55Z0QvmOY5CTLoQDWFMYmziFVr8VAXS6Nj%2F8%2FIpmIaQdbo8vgeVOK%2FIEIegms1SBvTEOvdQJ94Oykl3YRCecjbp7F6%2B%2B1Gskn5I95eG7nU5u7hPkBWSJiTRdBMf1aTwa%2BHrupqnTDBjwlU8rVUjk52y5kBcfNDxK0nQTHnQ%2FJ4GmQEjHPqvtctpRCWxK6vHGNvLFCPpYgbL0Vo89EojG3RomT2jVF3UxZR3INZ0nNrdPNN9%2F%2BxYXS1W5eow%2BcgLrRBdzwGOtb3ayT3hECD9638LzGecu%2BPxEm8TQnxFmeRWAbkypN%2FVMGXup%2B4NwwjtiPvQY6pgEC0O7zb6VzjNUhhjzx3jf%2F0ZKN7h61p1ftFttfELYuVM1fMbz1r3bM75085kH%2FGPGBX4xBJfdIoWLX3%2FOfrXFLK3VN6z7J1rOBVIr6FikpiV%2FIenjBkOBc0LwMSta395uTootQR4fjWhABHCCm8piitRlGQ12e%2BDNElPcD%2BW8myEXjKe7u8JfJ8lwCWi3tNAHRgRZj8aMaxtFlHKaIWrVRCI448tTW&X-Amz-Signature=308c159421189a52d36f5ee0bc417a1d03d7b2c1b44608ac85307decef6cc0d1&X-Amz-SignedHeaders=host&x-id=GetObject)


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

