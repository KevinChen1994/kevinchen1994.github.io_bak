---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB46637N3ZU4F%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250223T172032Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEN3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIEeTAlmIOJUNnwO5oqu\
  pY%2FkrYcv8kXo8QTvQLlibGq2XAiBg7hd169cotjnqHSF%2FJ0jfNxOC5C3preVCQCpodrDtNir%\
  2FAwgWEAAaDDYzNzQyMzE4MzgwNSIMowiEiHti75qkbi94KtwDs37PXUJDbrlZznzwmwtGciKYNcd\
  dhbDE4GTuWQ60D8FTpxEJ1lNWpb2e4zsc5EgJFRchBv9v%2BovJ3CMZUBsm5n2run4XuLlVSsGw0g\
  wr5hMHbsdL4hdUZRniofsnwq8cSpUMjH%2F5aArRwR739TGMs5AiaJPGY%2FVbUv%2F%2FYOLZA87\
  %2B3z8lfoAdm6A2Mn9UwfzjQ34JcYyfnmlYvyyqos6qR8JmKTPgrk2Ksp9sCEtKxd6EMX7S1MFTZZ\
  cjDUMhkvJOXLertBSwTrmDVctTLYpw1xCGhIgaYIhL9UF%2BQCG%2BpfPy%2BjKldkaEIrjeAVq8z\
  ouQWLZ4JT8HzKymuVbUcR9J818vx0Q7gyIeyldQN9LRr1JAgVoAId9Yob9nR%2FfvnkN0R2NHChPB\
  qtorKAB0WBvAxasil6cYDOFHKwRKhx%2BoElQU6srYPj95lUBB47u3T4dFQ5WI492ZA%2F2uh28OU\
  4AT7ISix5VN2QTOyuXem%2BC3%2F9Ij9k%2Fd63xbIcrThfy1r7PvkywF%2BRARsppMkFiOoBOhOl\
  EVIClhzZ93lvYgUHBj2JwIw4wuDzqSrZrynoCNbkgYsmD%2FR%2BMghOntmfbUuta%2BR9N4bUOed\
  %2FU%2BPy7AHA%2F%2Br1tlqjlGpotirgWFujgwzKvsvQY6pgG5sZeiKgoaXoMJiHGvetNKmnrZbj\
  v047YKsMRESTiAeWdnyrAB66LsvHzhFlJau%2F2dHxCSa3Z7vGa3w%2Brh%2BcHIor2%2FBjObFbG\
  sewfHxAh5sHVXKLzv6c9tbyys3ueUaCS00nGt6%2FHyWRJFRVcuIbqg9Hfdasd89PA9reTGrk6pXQ\
  4CSNjYWjIvMqNCtuKmfzc8VbvwGVyTb%2F%2F3O%2FuPBrkiXgsQzi05&X-Amz-Signature=1415\
  ea4c3739da3716b9d791ef71a95dcf5b904d2ab1e88e6f75a9567b65117f&X-Amz-SignedHead\
  ers=host&x-id=GetObject"
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
        redential=ASIAZI2LB4665RDX3DOY%2F20250223%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250223T171851Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQ\
        CIBJFMAC%2FY%2BxSgkZ%2FsRsgBTejR2VPKbROlmSD%2FeCNrnRjAiAZJ3RdNnelKt3a1n\
        2Hq06XSzhchDEX02IWr7c%2BHZqV4Sr%2FAwgVEAAaDDYzNzQyMzE4MzgwNSIMy4vwZCt9u\
        5GSTWm7KtwDKEKJTJsUnLn%2BXcgu%2FOonwr1h5GLUgwHqpFopApIiNxTwo19D5hw3ss9e\
        VhPmE900I1%2FGKu5roP%2BLwlslcJgsDmK6QvesLTwTqJ%2FDo%2BLgkm%2Fx54UNwszZg\
        juoPTBR%2Bi6e7U5bj82j6PK91uPwTHojR20gNUkH%2FwshZoFwaM%2BFg77O451nCjCMAV\
        Bq9WpZ%2B0ZQcF5%2FWYVBaA9mQqd1%2FAyMYaFy9s9KpXeFSO7S4lly8f7NgC1WjG7xfmd\
        EGjrnMn5ZGry7FX7HK%2BPcbKFu69G23%2BHcqYsci5nZzKZmw5LJbIyGr0zBHWQQNZTty2\
        DTfcyx09p3Zbtk4ypxEizp2oq6UUyQrC5J1R18p1ZrpRbR5VAIC%2F5XSEmAmOU8t4USPM9\
        AMJYzjNRazGZmaBa4ScuJkvygxNmnTET7mo83cQlqX6%2FlZn5rh2AKd3z9yQZMDiYu2mzQ\
        A4AnCRdoTR676hruox78hf3Br1%2FLU9rjt1VgKWuUeIFXUaEWau5TEmdkq3IbHAzmcdTsx\
        cHaFe76jKpKs5IsENDZoQhh069Hvsmbknmwex5EPaBgxoJuw0xhlfen8dkklxHKdRI5P9jp\
        dpI8zTX2RfNj09A4IQUo4UK%2FNJh%2BnpOD%2FJSPBefUSLQw95bsvQY6pgFVLkgT0ILGH\
        j4LPdvB9Nr8oVddv1wqLuyuDvfFV70TjbNLYh%2FM0TzjkrNs0IR1YRXFTikEX2p8ZTzi%2\
        FTM7iPUyeg2Ir9YsGUGr2JfBsSIPR0GCOKWyfkxOWuYqxOmOqV0Dj6yyZf78902JxKVe2oc\
        H%2FoHJnDdw2jU7eKvALH%2BA2J0W%2F8CKD80WtHLQVs4Z8bMihHRbeoW2A5H7QcAZn%2B\
        %2BlpaZZDZwD&X-Amz-Signature=be684caf4ef885f9f5e9d0e242f34f028054d4fa2c\
        02da5e0eeb0c4148d369d7&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-23T18:18:50.974Z"
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
UPDATE_TIME: "2025-02-23T17:20:38.119Z"
EXPIRY_TIME: "2025-02-23T18:20:30.335Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=67c765bce2216cc775f024ace5cf924346946feb2775495d8f8f7dfe7122d975&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=212bd1f7cc1f36bfe869942edc380c80619bdddc684df213c873bb131794c297&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=6d7343e8b5c8029249411b9c0fd37d63313e1f2b0d2cf3c702f77075cf6864ef&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=07bc0ed5bfdf440ffe92cd074d4ed9ed072c55af3172d8aacd8f82755be94541&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=bf97abd87265e2b68ca0852cc38779bc5aea6b30b8769655da825fbc54fd19cb&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466RAFOFNCP%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172031Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQD66mN%2FD%2FGka5IPlyiUJdCLuFV6T%2FWzjBBQg1YoaC0gKgIgQJBmkbvyQZWpL9%2FqaQw%2BZUU2rHE26sfmPgJHWvreEyoq%2FwMIGhAAGgw2Mzc0MjMxODM4MDUiDHEEiewryV32%2FuupGSrcAw2JT6fNcwK%2BQDJzbkLP4ilib5OX1LqHUOD5NuZ4sQowqHDTlyG%2FxfR2P5wR%2BV127%2BIz9zwT0iSXdIJh6cdQhHfvfQZdAkBMosWctSWKsgYjQSwPi6CO%2FzQCudIOtMrJzNBOH%2FImd9mU2zKW1KLJ7livqUm4FjwD0rfmnJ%2FWk2oQqnyWOiOVmmJXXXBK%2BZ%2BOHPcoASKnCj6qRT2HvPdFRxgo89GbtEXsgFWKKI7G0xq%2FJLTUG2RHVWxXsJjwpOoDFYnOkZKpuEvppr75BRk%2FlKeSvTYhj2qDTC8kJzEHLShbiWBqPYZLUogpG5lYfTXOHtf6X6p2P%2BmMYZnqFToPMy5kbKMbQNWTK7v0ITSDlY%2B7JX1jQt2oBthaiEMLRMXkDZkkiXZahEL4iYJMz6VL9XAD1ELTzTh8K%2FVuLkA6Tam3ZyRsy43ePLUAW%2FCIQQpl8wXOJLrJUouUUE%2B2iDDY3ers2N37JK6XZjoVLB9YJ55IAETAcV62w6sx40EpNXFbFMnuU%2F71XeGCYkvvui7CQTBsPCYWk0YbjUfYA1EBdVcu9J0q4zEgL2i7HjChpzaZ%2FbpRrDt2rTldUfBqi40OLif4%2BML0b7luVDh%2Bu2jbMNzeFv1GD%2FUrgVdVzLnCMNOd7b0GOqUB%2Fm8sh6SmrkcIdHGgf1hasTo3IgXlFeStjykW%2FP0ItO%2Fakea8%2B7Sc51LtO2%2BchSuXtHDoDSM7%2Bp4EL1vnqaRqHfJQsGMM%2FMJxdF8atATX3N52Nl3elFAbzdNe4kn7DPEi16Mx%2F4a9w9iPI6kQ5pz1yPMKVT8vo8t0rH06yRNJpJq%2B13AYt1OmqdBGAsFgWbvZTYZLT9GS4sn2rOo7TQ27Py1NysoC&X-Amz-Signature=f154bc6cf0a821ac90e05c4f3541cac74cbb21f8ec8cd39dfa483f0ba2b82daf&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665TGEFRVI%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172032Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC68yc5bj8vUS75wPfEKCQDAvaDn9Vhl1%2F%2BhSQQtKhjvwIhAMBnQtifrNVz3uQXG0Rwfxb5Nmp4U8y34LwHkvgE%2FkTsKv8DCBkQABoMNjM3NDIzMTgzODA1IgzB6dnH9REtxyAJo6cq3AOroMfuqQxdFvid0qxIWa6GMuBYxOfcK9Czpxi9PDLAo8NaRHEfwg4GjkMd4v%2BuAC%2B03qxET2W1n%2F1ulxytqt6ctGVmusdbZKEYMakYkg672igSM6EMJbD4oZ29Ab3wvfMJkmPvhKTAtJxgbXEXITZ3vz0I%2FUr7W6u%2F%2BIatchok8q1vYi5rhMueP45atf8QZ3RAdW7VjmlCUsNgQ5F7Yg2GbS%2FGKTVQ87gD4uT9uKU2FXs%2BeogcaP%2FJD2WbSzA%2F%2BgoROK2urCvKFxCDkrpo%2FBZPmEIpRo6DptROwKx9ttniB4mj8f5SzK8kiLmUx1WvFWwPWhlUZp6kUdvBJYcltDZbp5jIn6BH4TZEaFhlGpLdtEwr7w2LtGCTrq%2BRKopGeD%2Ben6xj2jWbaXpTNRHyZwcd267JxqBKJAoHear4M4e8uBGjT6p8FAqy7Nmdl%2Fpm8AJ3gYiAp7Yz7ReMJf60u1luiPV%2B0cnScMTNVmmERtjsaDbPGCw2dD9bzeyKbOun5M4zrVInGH6arw3aVt8oDsVjdHJ62%2BSP4Oj9HZ3%2BoVr4P60hROFwzxd%2FhqpTAewvqVGVv%2FIK2hClaVuASHcUq%2BaV3Agc9Mh3XP2n6y1Q2Snbu0J2G0jNybqHSibiOjDWlO29BjqkAbHBG4gfv3WnFfohXNbkyT5JCk%2BHyaWcSGVQcd5BWQSR2LvdtlmiOOM6kBoruSnkK2jrTzeaRVSJnN5aL01GWssFLuj5e7nqgGtyixQJlmmU0ZqH%2FYvuj39DWy9jh9Gf%2F5JqBxGc26FmkGKhSL08C9YElpeOVtcxWVjheTpjV%2FUYOPWpqt1m63BI8BWLJwc31jX8TJJtj1yFpvhE0o4QEPiAYfHI&X-Amz-Signature=8fabaf13c12f6490102ec4ad37fd6c96601a8ebc1def6eaf767394da12962056&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172031Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=c4f0862b9240692bd3b8ca526c7c039d22246b280c43e04d78894f9d973e29ab&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172030Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=183f469a8afd61457127a49771a9f24801aa85fe4c27223c3f23b684a3d91d6e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662QG2JMSA%2F20250223%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250223T172031Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjENz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDnwZrOWT6Q9djpblzcU5%2FEco2NNhwkGIwqGI7qGUGf3QIhAPthz56xe%2FLjmvqRrYEkp0r%2BU0889fWOMmk2z96zDBDnKv8DCBUQABoMNjM3NDIzMTgzODA1IgxK1WbxLAcRT75TuSgq3ANyPE1NTfKmy5JHrO4FHXD9guN5ij2a1iwRTBGRr7q1XMYt4zcenwZLw3yspR9Y9B4NUAZ5bdHSTZUbqJrZ8PXK0V9ES7Ga%2FeCPveJslm%2F81LMNUkSNlMfGxj38Yuc66wcYPKLAYbApdfJi44%2FJ0ytuVpFUwywOzm7FIJypMgRHtLZpabI%2FlBkB02N4LQkDHVcbp%2BYa%2FtNoeutqfABVB6zh3zqgS6rEFwZLJLRTQ45DWJrwcL8yOQp2Hlk6zRPcj%2FdBW4uXeDzhqmKQEPUOrneq%2BXboLLVNcr54ndDaYSs203oDIEfjQLo3wjlOJLOlwZzJKoQ3j%2BvtOSslXF8x5dBPEjh7EzNvyoMI4Ar%2FqBhwTKxZTcKAUqOZNpacMsl0OlrGv3DRKlS%2Fvy5n9h7S6DrZ8%2FHEuzsQ5mgofmdjBV9%2B6sfVFS3yR6U%2FrFDtQ8kkkU%2FyFT87HNUXLwaQ9q0U4h%2FS9GLvW0yNaHW41%2Bb%2BVtpbVrR971IXTpUXBf1St0JwHdQpxSG2OFhdy5rFi9XyjIAbJNrdpc1Xei%2F2HoOojCuFR8HUXD%2FRi1BDB%2FZLWiDANLUG1s3JLKgdsxCMlOHrDZNci9syfs0HCNyO1mC0HLVT23TN7Y223KV5WXQYjzDpjey9BjqkAVDk6cblsRy19l0j6IO%2B8VeF9zyxTYbl7C%2BAJ6bYoMEd%2Fzp2FUGnKeWI%2FjxpbvJ6HWK%2Bfo3Tv2kizTfw64QqpjlOhCTaCSZbgEEwi73AvMCGTqAygwXoxoz%2FuEuYzwLpZxrcn7gcrSBFSnYUTRocxUtTcdKrMW9jVoIG5mZ1ZMLsRVMEaNu9w0r0CntLQ%2Fs3uLWcxHTG2U5syLPtk9XWNjFmFvhS&X-Amz-Signature=f7a87facc0189fb2a33c013c13db36b71e10ea1f96ff15073ed6b2b48e1b156a&X-Amz-SignedHeaders=host&x-id=GetObject)


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

