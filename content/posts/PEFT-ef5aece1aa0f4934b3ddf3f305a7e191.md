---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466VIO3B5PH%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T202310Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEMv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCFi%2BlRaRgVnNP74\
  z%2FKcykbSyDY3pcVaQeWzmT4H5PvwAIhAL5x64%2Fy21y7RlvN9x7v%2BdnLPB4p%2F4o2gl1RMm\
  CoeTy7KogECPT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwZN0Xzte1\
  QAtP7r%2FQq3ANlops4Za5RdGcbXBDR0EtS3veKmma5joXiTV5M3XGLY9dtiEyoBe%2BspuNtMLwp\
  mG%2Bt57md6teIW0R0sDFUJ1%2Bopgik0Oz4WgGyEf6TcM5rgwE6i%2BamqjD%2B5QUJLRGUTdWsh\
  w65s6sPII4ITVGIqb%2BsZYPzi4hQLJ7zhlYAqY%2BKaEXSRvUId16gEjL7UNneUFvCyI1LVAhB3Q\
  nyUHczYOQImIz8v0fBA6plQiiZ7fRMMcAqTbkOOJd5DlqxF72G7AZpQ64Iyq30JhIV7qqDuuHmQPZ\
  VJHNSWfyb6JQwp%2B9yWJFdLwzNUV%2B3cz%2B7PiydhCxopYUrBvFFm4A6BRjWsJK9jQV%2B%2Bx\
  Of4ErTJx7GmfWtfV6s%2BH6ItrukpArSFx%2F%2B%2BTgJeMbFjb3%2Bc3t3KQJQBUCd2ys5xezMi\
  241lokt6KbgffogcIVHE5jMpAuV0vSBwR9IlQ9KUxeEkfc23PF6aQ2QyQ%2BtQt8rraTZsxmLzweY\
  wdASFiJMhuvUQSvx6zx%2FGki8CGjHJSnQR0PcIGBe49LkFQ4pJdCpcQncccRYxJNLBC0qWFeR4lV\
  x9jYIaCb7f8mHBwEgC%2F%2FEhBg5v7qeOuO6kO8gTht9nAlXgQMn%2BpNEnFg%2FFjgbPcjuOe0K\
  ITDYuui9BjqkAaWkjVojJzn6qkOuVwZkS1iHcut27BHbyeTCwqSVdjXeEHAQa4sK5o9gRKoUZEktW\
  UGDt%2FhkW6Iv5YuwCgfn485ZP%2B9DRgqQEpU6yKBsIhT%2BeDi6YmUuZUymrkYjSBWtRsTY3NkR\
  Iq5OATn8te8XNRNiYhOSCHPRFRoAwRT2%2Bi%2BMdtGquBELaC3uVfYBKskTnheE5vRwR5oKVEiGJ\
  zUZLwEKFlq3&X-Amz-Signature=f86ba75468eaf9a71b931e9ecf652be4a662ad67568ac45e4\
  f3d421452a6aa6a&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466RGHSIYNI%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T202149Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEMv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQC3RuyTL%2FNXwQU03OWUB0KATdPEpCOS7aZ5H90%2BjBnlfQIhAOnudrHC7Nm%2BXRyp\
        YqVZr6SEhiVmEetkWocVRohgzAqLKogECPT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABo\
        MNjM3NDIzMTgzODA1IgxKSfCGV%2BLDfY9Mv4gq3AOpQowvhTYq85j8Inytd%2B2IOZ5wk8\
        Hb7JIRMiyEWKkz5T2M%2BzG71aTIZoKTKt4irvt%2F2bY1P6pVuAnu%2FI0itBtaw9sMrPC\
        OKaFVSz4Q9AnoWVB06tjgEVTv4yx7Tg98gV6GbOFZigEOIhz5QXrLMce5pYb9eJUlb8nKdQ\
        6PvJm2xvP97%2F4%2FV%2FiCBtrvnySFWBjNRhVkc9GxoBv7aqo7aWS5XoxstinsbP0C0cr\
        6DIvE2l9eq1UPqn2lTZ7Y8PLQawTHuGXeVf4nqGUZNXj%2Fo3yWgxmhuRgAX9PIteNF51tO\
        JHFcfdvv9g1ohMpiFgcGTh7bRNX%2BPez16EMf8z66qQhM0TR8xpnsGJHQXdFM2B3j78GVq\
        IXu58I%2BKA%2FooehVwAIombYyLgCL4yt7jfHDz4Y1JjZMZt9%2BqYaq7t2Fj7mYnez8PQ\
        murG7izuHKQMtrArzrn2sFt3MTIFCPLoE5W%2BPM5ky7ux9AaVByQBgV5cjj3g5IexpzVYy\
        S5EDYQxKeT7L4aKhdH1qUqUJwV8dfjNur4faZC6A%2BlJ6NOeOFa0MXCu2OVBPWX4rHERPo\
        LhPLNTLdhaUjvf33VWRgFuwelWa%2BVFR5d4UzfigvPmwyhH9XeIBO2QkCnFK5heKOHjCQv\
        %2Bi9BjqkAXj7ZJbZvDPlc9T6F3QZpr%2B7qKi1CNL7yO7B23%2BPYH0zuqj49ps3ORL7wX\
        exY6nbMxtSnhIdknZnqouETZx2BE5jc9h2Nuf3BlQPClU0FmpwTqWWICq30zgd41%2F68HT\
        VLJkp2Ayx8vV9Vvh9CoZsD%2BxmtW4%2BaFLgZr3JeW93I8feWl%2F3Byo7sIUceK9dYgBC\
        U0rCunt%2F6u6gRS6awrXXu2Iu4kLg&X-Amz-Signature=b1ce35bb3ee8a9bc5267986b\
        eda5a8965e4ac0f422851cd82e07979b44776d75&X-Amz-SignedHeaders=host&x-id=\
        GetObject"
      expiry_time: "2025-02-22T21:21:49.686Z"
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
UPDATE_TIME: "2025-02-22T20:23:16.777Z"
EXPIRY_TIME: "2025-02-22T21:23:06.909Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=9b529a1abc2fd40608a0671690105f45cd87d71823d2964c59c51272fa062ba7&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=6b5b3664b434bce26854b855c2787608aa56108f9f39d678a2403155c16e0026&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=ed03078989d4163774acd8e1acdc624e80125c372196bcde744625b492503fce&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=b57e61cceade83dc7735c6ae356697caaefcd5380c9aee7b881c3daf96f22127&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=d990a6cdd52b3b2af2ee8c136e4098da628cac875a14f41a76419e5b758d2f9a&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KPHUQD2%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202308Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIQDTkRYZZrCnKNo8JvQMxUjLZXjW3PxWMkEOowS1bEMqEgIgf%2B37NMMYHjTdZWQpUIYLyrewj6k87cK4fgwkwJJk6QUqiAQI8v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDNt5NDJFVyGp4hs4yircA06qec4sl027cnTd9IWVn65oyqFpQe2wSE%2FZD29wOJu4LrqQfHKxw7JuiFJ%2FhLyruaslCuFmm7X0rUwl4KINRPjGzbNDsSi4IxfiY1hIDJ8NRIFwNwi1d39QM0klmfDKfR1RplBlzGp1UiZED%2FK6t1o47kuasJTswgrv43%2F3hwR0%2BRyF8dyjY%2BA5QAcTZEBMncqbL6FTJdoZbR0eMcuOxnH6HeGqTyyzkshIaUZIRuSCyL0mMFgsPOMtmyMspIyKhCIhkE0NIORrm7o3zjTO1gyP4p2ljocLkDTnnUBVhWFTEsKXu%2F1aBiErTIY8hS1r01ACt6Rxfk78ylMQ7azmgAX5ozJ%2FdTGm%2FDjJC%2FHOnNY1juuM4PVKCTvREqOTCSMYO5AE5UTdXbsCiwdBmj%2Bo2UtkOBQRiZxq2RT%2BTTAfJ%2Fz1edlRMSaXqv%2FGKsNqMNNfvRIk3e9TClyjkBv40LnsLGEK01t0LglX1q%2BDx20Uv9IG%2FSb6xclCYtWWYV%2Fe1XnuwvbZmMW8qAim64v4w6i4iQ0xym0Ic6UbPnOQTmOBZ5yZV1qXwJ2%2BRskB7QedKfwkL8igDeHA0Pj%2F6i9VLG6RX6xW%2Fpr5jSX7S5vX%2FuQ5CQ6sBi2IPxjJ55vNsXWQMJeD6L0GOqUBICnb%2FF1CHfPLqT3Kw4odwmZCXuAXlGgsP%2FRBowjYnBBJielJvZN%2BrVcRTtpHnlcHu%2BDkZY6l2PWcJQneqCWRiKkWXdZ6CMvCKm9BpD2q6BzIvQx11qFXegRUfml%2FDWmFtJb6ekR3gKTpJsQTp15fqqFlhStjOgaho5ww4ucZvJRF%2FDxirJeG0qEuv56iVGNM5KXmtwDi7THXRPkV91dEhy9jnG2R&X-Amz-Signature=3ed125c84866a17fcbc1731622f8667b860c685b84c264fe1861ee064c55c29f&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XU3OSQAZ%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202309Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQCnr3fMQDlzRWxzBx6KZUCxhTKlWZ3Z8NAzGVKwMcadsAIhANzNgn9NGifEKwVJ7gUzRTRUjztmXIxd0Qb76DGPWD%2BHKogECPT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgxPicD8LbkCWPmnyJ0q3AOgF2HYO%2BqQIslS4Lu%2B5KHZTfXdeMCwg8jqAOqfR168FnwCIQHo5aQ7VamCmdXZUPATBCeuI7d8M5FI608ngosZ%2FTz8tylcqUfLyKrmACaWoT0ksQPxM1inIQg6ZiT8%2BScopKo0lod34wgiV3%2BZGcrpL5UJ6dsACIlpuI7cIsTt8cIGG0id0UtEi4hcXCdWiziWCMEd%2BKjUSMRqshzKhn3lLFkJpD%2Fk%2Fe1FrXDr%2FZKaFmkNfHTUHpI9ofyHH2nbqUMebP72V6iu%2F6pmXLgxTmMwwN1bAT546MB%2B5fiMXmPUKAncxdiXuV0ivqEpqdd5QsNd631%2BUe22clOHjSPgx17u5AjWhI8BiNckYRXTuYX%2BkLbmjI8tGMMJ%2FM6DdSWLbT%2BT%2BbPHODD8V%2BsWSsbUWsaGjOMLbRPWTH%2FOVilBrpnFWHXY0i9DMekcYsqlt0AX2uvEJlLgsKNmZYfOWZUKqIQZubFsxXb3pLU947vmIx9YZdPatRywZYoOLh4HxPvIGaqD4n8Eut%2Bsj3Rs7oZWmIv2CUeK0ZoQ6R5TBz7Au%2BmDqkhlQDprLqq1jQVc6Iw%2BcpWuPjqqN54TIKZw3nONEviFLzH0%2FSNKP%2BuxtzFgl%2FIWVSAeMA734Ghx9QMZajDYvOi9BjqkAeb%2Bq1M6nkn1MPG3R%2BEym23kg8fKQ5bufpE3WWA7W65LbmMLhzUo94cDmtqddO1Z8lun1yS5Ilui6OlqB9%2F4nv8sOIe2CtTrY6fXfSury%2BJYWg1YiGniOodXP78PCciEVKox7pMCk160nI7aRea5BQnArWemXy2RIXzrgKOC0EFPQyzFUL4PvecKqP6sYst0f4LhOzWQXEhrKfnIPvwb56ElO5p6&X-Amz-Signature=d40ce32c95818a56361de5e1acc0de2ef7cf5e758966ab91c0310d56f23a6d4e&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=ea4ceee0f78c04eedd75bb6e84fd1d2fdd3ecd109cdd86a27f8f5bf15913c4d4&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=7cc2a9a237b0995cce79604769b6c38807011e5ab3432012adeeba16b25df2ac&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665JEXLOKI%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T202307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEMn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQC5qkNWDbh5xw6GsIuTN39SftQueSnHTzgd9kJEpSzeAAIhAI9yxw99ywBFW3CCY54DXUgPHOCUBq%2FFAyi5Jppzc6YBKogECPL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgzlYJgRLCJnjQCtNPYq3AOaOgOpnYUH2RTlAIP79eOMhsfpUgDjIii9xd92jCzJrY42lfpbnpArPX7yvKU6sLwgtHvdjGPspvlqoCi3eg5%2F6yr3oYwp7caVhd%2B0TKvIh43WGm6U58cje%2FidKxeXfdFmax4Snbgh66NRee3OxYsWKOZFno2sfPJJKZC8ICYANcnPMNjfL9HPunC1N4AToy6q54MLKVLo2oXx6KFUEPmUqZxQQWc%2FZfHOfAbErRxZ%2BXknc0WQA%2FxB3yC2cPSAwM9p5C8bpHjo7xVHnwkGvLsWs03cf48X6d%2Fyf%2FPs6WpAnDIB3mYql3Rac%2BLQrd4AK%2BcTOZIT4bNbg%2FOaaQZHVb6rRL34e922OikO%2Bs4dYiYwEApA%2Fs9fX3ti4yb7PF%2FGomL8jPBR5pSV51x5KvD3CIC32MtdYDQGKfTwF81zQAOAA7AxqcPdtBlj4Hb%2BQNZAi5AqxasvV8PYREN2GE%2BvwRYQjGdP8TNvlvZtoKP6v676Y0nKDBbthwTHK57lJwjDyZE7AkBYT9ryjvBzrsI5oWZtChPtJ%2FsxMCKS3xvPgRUHOKj%2FhzWPMVnywpT8KNZrqLMbpOjpdrgFkbIgZSfjR3WqLgg58irZBZbCpRq0vtf%2Fstv%2FzkAVa1rMo54IpDC3%2FOe9BjqkAVU3aC%2F2fJllChu5EXyNXhHphYm4zMw0myBKvig%2BqEgwvhdgM8SwciOrluQgGi4r2ie4USgSnRV%2Bm%2FcIjyBX6fTekVuSW2d4kTVoFZJfjdK1v8nNSIwsVNf1RYC5qlFsQu2tVs%2F3lSyzvckvy4WzysuEE5hpnE1WqXljjX07dgK1wG%2F9HZ32RwD06bPI5c5CByoXy2jB1B7eeRhDecXVu8Vt2AXx&X-Amz-Signature=45bf13a451f81b7e521262ed314f8d8a1c71193dc81e3eed1e855f0a2390a40e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

