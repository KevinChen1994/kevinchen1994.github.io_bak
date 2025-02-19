---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466YLPAMH4B%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T025318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHMaCXVzLXdlc3QtMiJIMEYCIQDEJ6kpW5yxFQENao7egYaSejcpTKTCoYWX089B1qJvJgIhAPe\
  O4AXmpZ4VXrbS8FmEc2PL4gIriW5f73gbbI3GW46JKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2\
  FwEQABoMNjM3NDIzMTgzODA1Igw%2Bme1i1UtH9W%2FhM3kq3AMfmJAE%2BOVSFiN1i9ax2fhC%2F\
  xTYd%2FFRppUPtinAiLE6wnMdYeFOuurdCr7OfuSnjlq9v8rqXNIHdjgPVyaNXF4Bg1Og6CgQ1ntc\
  mET%2Frdv0LRhpfstrg32pq%2B2ptK2%2B1yxkAfPG%2FXgdOHqoZGQ29Veu5t6nlc8b%2FHw9RHx\
  qWrHi4LbohJ0AGRYcypNmDtZvElhpb7rERM7%2BUXZUaMm6W%2FYdJ8%2Bc10fKhwm69WQp%2BrhM\
  BLsBQ7Bg6BwdkyC9EKN3OG2hKzi4lLMhWMD3O1%2F1U0eLJIF%2FZFzDfEeQzoYYKICIjPj2wwTyW\
  hiUoZ0cHssiNXR0RJRvf%2Bynt7aQLYgl9ddBBS5m7HA3tAqvt7XS6f6q7674pNShpx8jw4hUYjUJ\
  XQmN5K6SaUmt9erwXHl0f79rzkedWoIdRTCFtyZyv9SRP4On2Zgog1vguoaaF1osJArslHBG25MUX\
  2pNtQfAxgaq1bKDQqPWIDPxJrSMwYubsXM16tFT8tqhbF0VYvrJQPnbAu6so22eXEu%2F7UwLitQp\
  a%2FJRM5rIehx3T40WbOXX9JGIao6nvcxq8Fi8pVV896qnlZol6u7HfazKixynrLAC2qmkFIyGU8Z\
  zX5BJMzxgdY95rypEoB%2FYwZG5gzDFhtW9BjqkAYeIljSEkib2LhpSQXneh9MoCzHUnxaYaFWkdp\
  7HBrwEHhhGk2ztCoxxBp0KGxPPw1yPQZRxsCncoy%2FugA0eQ9urwXf918XVsXvVSJiqAUyQLApYI\
  Br0BA1e8V072YejAgjJlDaU%2B20PuH5n7r0Wmqw9%2BSLF51GK5YENz0Qf1fcXJteOVt59nVYtFV\
  jn1%2BE0S5i%2F0oGzO7EWibsAhCshpO%2FJtcQm&X-Amz-Signature=c2087fc56c75021dabae\
  5daea9f14511202ae5bb15dd95a051a5b1f96a1372c0&X-Amz-SignedHeaders=host&x-id=Ge\
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
        redential=ASIAZI2LB466ZB7H36YA%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T025213Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIHT%2FBE5tfgfaUv9D7h7yAFzod3f4S\
        e9JfwFxiLlfSXIxAiEArE3EYZwpi7JY7LEpS%2FvK3ZiTM0DEkKcbBlkSsx5t4roqiAQInP\
        %2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDJJMl7hDKmozQKLiM\
        CrcA8JFUW6mp%2BOmFegI1Ct%2Fh4uPjgf4hxa%2Bi6lJJ%2BqeMTWzPCogXpoPda5K83CM\
        r5my%2BQNiJNd%2FjHGmvCFLSbCGk235GKcA83Fnu3WYFy299JtJrdpvd4BR20nIFotytW9\
        f3rfdpZarhJpZ%2BBbG%2FW4gTa8Ip2hIq7ugH20JoFXAB%2BSuLx2mLeve4LRuaEPnff7I\
        RSjE85tuiZQ2%2FYGuojZLDOGJUVrWkWu9IdHCFk9KioU%2BoGWw1ippZGTkOCiu4yyAQTC\
        IdMuHl84lNYihDaWIc1y7UqGov%2Fi%2BOkhb%2BsFEFw1siVP%2BAm0CboydwHgOyst6IP\
        EMSUVa7mWxMmwUe7uhXQyEl38Eiss0xq57%2BQhc5J0TAyMmNcejB3qCQwTnKu9VTqOawCm\
        8zLN3ZmkozTt2RZLVRsUV63KngfgJisdd%2Bgy%2F5hH8vh%2BUGhvOWEIMHqzvb7LDl35%\
        2FcIeUsv3Vdlny4XDhkBcT%2Bw7itsNleFHcisufh%2FR1PSXOppPLVLjDwg03EvNM4hajG\
        Vkxb6taZs35rYH5L5tfSMiu0VFUh6Q25NAcsPKiK0seXjAIfX9iFwQuWUBiVXr4Z8wPZ7Vy\
        VVJOFOCed9cLS2SdBzoVDhfq4BgWc3Rqr8Vr5G2%2FFZMkMIqG1b0GOqUBIk%2BNJ7mn8eN\
        2YjyBdoZDF5vt%2FBNDRqaSCs5j5A21bn8v8uRKFHNBBdnEUV0mKkqrFVuyoCaQxAKm8Lo9\
        u38obK4mMXAxaSs6sMRjWsWpXhI0lUpna6mCPLX2tt5CClZHEYAuAnSG9Kj4fMR1IYGWnsA\
        RKfIcEbXK8doH7hzsBGqGVsOjFWbIPp0v7vyk75%2B6gzKA9EIUFaIJvav011%2FDRsyxCm\
        EZ&X-Amz-Signature=13e2604b4ce17241a7e8598dd0c8eeb5cb060e2c06b0f4a3ba15\
        627d4e1a73e4&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T03:52:12.968Z"
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
UPDATE_TIME: "2025-02-19T02:53:26.239Z"
EXPIRY_TIME: "2025-02-19T03:53:16.497Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=c25a4c0ed70910b5bdbf41dc472b0afd8c113c21fec5f4d45628ef00d744ff7f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=484b24f920544b514436939bdeba2d200154fc45fa7ab24f4c7beda3a5444d91&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=820a3c30a24137bb1ca99401cd27103a8cafab9a936260b5acd6e0605bc5df2b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=c3bd8b615915d2b1ad2d33c0ef8c013eaa9c6b683f370aa0ca4aa568b0ec785b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=83d4558a9dae1f3c604220a57cc434b327c1cd9993ad9af954c79357c0e8fb53&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB46626H6IKNO%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIEBVeQzsXmmVA1ywHvDUpfQCKkfmqlM1Ye8s%2ByskDA9QAiEA%2F5cGS2il1mnkM9VsQmBYDdP9DVQbGcWXHWJZVKz9CbEqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKF7I9d65fPRscqvaCrcA80fzygoJW7SAS6WrJHADgKGAggF5E2R7a3AAMhJNARKOGT72kdMuCb5Z4Hqfl3K5XVvXr7MH%2Fytrq9QgIo7LXE7Ga65yGNnPPVSzicDK0X3j2UUmrr3GPWxFlo%2F7E5xmm5chIfyBPsc93H%2BPWw4Rgn013P7tWTKZpvl5ZVxVv%2Fqatjs6k2%2FvwJ8NJlTOD%2Bi10BHgNdjcH3tY2AP2rENEFQMsJKPhK3ipmC1adQPdhoB1PvAoYBeX15Auxa6sgCZ4N96xCPGth2VojM7Ir%2FODvDUfW9yRHbzqj48ZhPxmkK2HcI%2F9POi0QjEo%2BQvJ9cBUuF3kyVScec8zhtdDSRy8g1tLW6OodCJfNFgNitmjKAobnCIq1u9lbMYgGa2ipegAjhgmjH17RKck17M%2FVo9Llzf37MPy9qBNJwO9DY4Kktu18ao7diIS9bAMAx3s8TAVVtS6OG4YH%2BUNHITxrvFCYOt3C4vefYZk5V2FF7INeqWsdqrkZm77HVmJ5rbXnQIg8KBXkCdn5J2pC3IxeVzkKHZncKktf3AZ0488%2BJeYlatk%2BDIKwNOtdfyrrn1xyiYR%2B%2FppmIRi4xAKg3W6fLiXWy9844kXf0dHcFTzSPvNFci9SgCc%2BF00vOhaBGjMMWG1b0GOqUByJKYhPE7x4BnpTUIfc4GHgFgKd%2BCYCUN4ksIbOKgv3FGAbkBpoTPaw8o08w%2FizvSbSKYWKwa%2FHNUeSnm9twcGdRjBIObL08hkpvWbg734rn%2FNlJymrgLuttGZ3Dy8o5YeeOLehOCUYByPf1oe%2BKC0PUNuGLEo1%2B3BBTd7QFaXLMGFhz12XD%2B7cIFsEXmslbu4KEAXF3KVZ6psmnHQfvtnR7hIGTD&X-Amz-Signature=e22310418c2c5b02eb07217006932c0380fca99a6903bac1542b15c1d179dcd3&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662YXR5DPJ%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025318Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJIMEYCIQCtJfere20%2FZoAAVgg12jkKVIUySKI2Um3mWdPSLW1wSQIhAIP4IKRguEyh5HfeRj2BIdf2%2BWmeeE2yhMiLcxNsuH%2FkKogECJz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1Igw2Pr%2FT8yzQ345IAPIq3AMa15Wp%2FEnkl%2BzsAurjpF8D9TXRAJcKCIlR1OYMSNknF5JGbosWQmMMfGmXI5cBVLa7c4JmN8o9PH6t2HRAzebkXz0CZlhNaKq14kYWVrsTgaByduO5WkJVMcX2%2Bk22aBhCtclUXAJjaMvMSBu9plUnFZQMuR64d6cuqWem22fqhy07rzMpNnH%2Fqat1Cku0bCeqavlT0Rx3Ny6QcGigeADqqSSnKiE0EtsvOpkrA%2FxyhLdFoJQJGglKt0J11kCl%2FtBI7mNsqtpjn5ohm%2BFim045UeeTOVQCU2lB9CQ%2FZuOXG%2FKC%2B6E%2Bv%2FYOGaUZHk6bdf8C9yPPzU3C%2BrDwTxxfZXmONZTGol8lBX6xS2pJ5vy00NjOVXRNWjRIn5Fh7Rb%2FL4kww4HhkGuJUm99o1wEKg2MyOOvphCLv7m63QTl3xQTC1p6zjn1FQBbpuiIvCLCnTfpwCAPE2H4FX8hLq4r6jh6UDbpPWnf9eHgGTfOcau1%2Fi%2FrIG8QNQhk%2FTKwI8xyDp8JhtbsjQTw5mqv4VQ2CgATJrsQeA8j3Zu4K7EZ2xEcyMH5V6L0mWq5WV7M6QCkiLKmDE9vgbMiefcsZMF4KvsYTlMyacyvEk5E3Sf%2BjdqLMNUMCbyoCtw3i%2Ff%2BTTD6hdW9BjqkAa8CLB6Bw8i%2B04QyE2dgHL4ix0gFC3SR%2FpSXSyXIgupouES9IMrN4%2BzjcyRaBX2Q9v5EQUrT9Jivm8X6%2BvqeiYSsRBCLkSKoE1xIGXjqFu218SssZuBcLyl1fiwY6pxfzidBVVVG3TH%2BjZZulscEJ4VVX%2FvPzahsdCK2sENkWkqD1dgirkDWSpncbaT%2FzuNfByGND0DCKVvACNTHpvFpySzsrfP8&X-Amz-Signature=4f5f34c54aaa7e77873593e7765ad68904b578c16383c3a373fd4407b1334068&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=0eabf138580b532b445d0c9c50a00c38bc249b5a930123515cbae11ed3a45e69&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=a3e6cff072f00595abc27b6c21e491bfab647e1f0ca184d7a109a28937e678cf&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4666LUE5FSR%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T025317Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHMaCXVzLXdlc3QtMiJHMEUCIQCov04Ajzk55BwZA4VQUH%2FjXlXapt3JlRfoT1EM4CP4hwIgFVjW%2F68a9y%2Fd71FIxGCif1T9PE6JectxTFupeMrr7WUqiAQInP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDDYVdC4BBuZuItkThyrcA6t%2BrrLFaGpiMD0fS%2Ba%2BKz%2FygJkjjF%2Bz0MhK8n2nY8B%2Fb7zpYGtqt3rZAbY61sH6ByzkhIftdXo0zwMSLqnvHqAwdHsFXKSC7j33GpxC87Ho9bKxAyYTmaaivfx34rW6Y4A4qJZE9pjj%2BQyrUDZIwD%2Fo4uCP8YlW34Ml81ZOfGyK7z9tREpBlNRYolylQAFrojUcYxowuV4OfDSqSKmypfVaQi1dH27EbOfkMXwxnfUkjuR3tV1WdxSRhXUwYu5N2twAVCmrNAttvwXfPVaxZWddw33X0XDPV7RXUmclPSB%2BUPAa120ojUm%2F3FyrPHeLMB%2B5Am%2FKm7cPL1qf%2Bw6dNbl3FC2VfxD%2Bd%2FA1yRJdaQ6llUf%2BCRMEoTJXTkBejCZon6rCebdrHaKjoalV9%2BUgtyP2o%2B6O3681wwUGm%2BylcTntDV4qKnJOoojqxgblWNZpvk1xZhb27IlLDsZsHyH6N4Zd1h4RoTv%2BmpuNbdblEnJi8YGwni4Imey%2FCN9MwqC2jKWJthA86PYQcEMjBBkkrPKU0Kb%2BsnjpIRGhNhR%2FborbRbwk76YskSy3gwoAXsGUcac3BUs2eiP1ozIhydbfj800FYVCVcS%2FYughpGWWlpgr%2FQCrlAA9TSIpu%2BD0MOuF1b0GOqUBPrZvpdkhZMrH5nogXYsd8jELbK2HzhFZIk8MEyPCoAOd%2F0LLxRev0dR5pIHOl0hyA%2BmqtNK%2FntEpnC20R2iNwRVj5dDOq1c1hdnx38a6%2FClToCOFPyv7ReMmAXM4Zm%2BEOekkVxJvp4liAaFJeqjqXenSLipY5TbhgyA%2BvjkHgqxFxmumZdFeqCIgY5As7XDsI78sCtwaAE9SZ%2BY9fJie3IIjkgcv&X-Amz-Signature=38b2520fadacf1ca6f9630e66159a913aea05fb28abd04601a2fac5bf191d435&X-Amz-SignedHeaders=host&x-id=GetObject)


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

