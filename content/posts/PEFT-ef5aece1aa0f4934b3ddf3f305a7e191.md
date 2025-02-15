---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4662VVJPRMG%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250215T092358Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEBgaCXVzLXdlc3QtMiJHMEUCIF1FxGyo2hO3jBmOnZEganBgsZ5t6eFy3qKqV7KWiCVsAiEAllJ\
  SdJjJUib8eVR3ZUuwQBZJiQ77f8r%2FT9VfR3xdC0sq%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDHIm\
  kLCjWIoXAmMm7ircA0uRmyPPu1dmy8VoJPIjl%2FnE7fCRS3gaim8IMJKEuDws8NtrRa4%2FAs927\
  xqINmvmRXWddKV7OWd5WaXuuJJMpE7XEKldXhFLEG55WfprDXi42Fox7QNjWP0FkyqkCBUbhGWQok\
  a7aMYky3ppVSD63%2F8jhSpWOpd7%2BPjx3SQcKCq3I2GrsDd%2F8X9hzkWWhwDWrTwETrWfeF7u4\
  abeKhS40VxSmcFkvcCWDV537cG%2FkPF6zg77O6ZmzXtqc1EXd8TQ%2FQH1vccYFHTB99Tvc%2FIu\
  lm%2FVj25EO0uz9k%2F8tJE2SAHjDSJTsLZHB9UIIsZvwa9g15nS6R6VtM3Me8qybiCw7%2FFTn5u\
  KATK7vTIgewDxpAwOvkbHSSnJWOmKSGvmMQJKyx%2Bs1lTjCZ7HewzedD2%2FwHBtwXlltnGHDgO4\
  SB3k0U3xYZMhqufvWWp7BOU%2BWmZG8wsl0lG1PaSRLV2qYe0szbVcWRqDjugOPvVYF%2B1QYg8dZ\
  lwNGL0NUygFD%2FZk1E3L55Fu1pBrTOlU3qhYjCLsAgl%2BMpVsGXqp%2BbMaswXlV85pc89e9Rqn\
  Tc%2BYc6ckbzL9Unpx4goFHzAb9qRJGCWti9N2BgzTb3Cyc5KallJpnh5lK9bwZvJ72JRC6K0lMIW\
  Fwb0GOqUBCkmkz0zjSWqyQLk8mJPTH1wk%2FYuHlXwkzWiNFLCkUDDqCn3Gk3C7eblhWPktciIJrP\
  op%2FfZSW8Pe9QSXwFGICO2DN40z9dU8jS0hAafmBl3oclgH%2BJz7RlBEb8IlKd7hIgj0Van0DLQ\
  NionWLKjmLeh07OHmOOiOS3F63G%2FNCEr7lqvZA84ZF0WUbq116iQYxJbAVhtwd3YoUF4wNc5p3z\
  0boMaj&X-Amz-Signature=b3f83f0864b06de0a8da3431d43bf956e42accab111fd4aa6c92ca\
  e3f4eeb7ce&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466QCYMED57%2F20250215%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250215T092247Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIQDog0XIE%2BikESzWhgF6BY%2FlozP\
        dRoW2Wpuc8RKQGkvWdgIga0nO1E4zs43dqVK5aiSUWJAegd%2FpQSdPnOg1OmKA7mgq%2Fw\
        MIQRAAGgw2Mzc0MjMxODM4MDUiDJsOvH3C245KobW6XyrcA%2BFfAz8jKFN8gUS47TsEVMx\
        FEpIPSB5D3cm2MR2bA3UBh2JtV9pCCuR575%2Bh44Iw1NERqjnuoNgDq6sJ0G13zX9JoH6O\
        P050xBqrWXGkYFls3a1HzrGFNx%2FmQt%2BYuSYT0mI3nzxLAzioqgBbALgtHej4DZXGGiM\
        2n4nmlWqNxM5CTIj3mTfrar8cagpPbCatH6rOz3RV2V1a8PW3cmlIlwwEWUFiKfmE2WUbe4\
        A0xwmvUwZhbsIaX1JU%2FcI37g0LFeaiHJ%2BtdqmVhFWqUVzP37vuGQ6AGygkDvBCc2Cxl\
        awdmIhup1E8tof8ptxUx9ytSueur26CV4LJQQvH96DBSm6nrpqJfTU6iFPfTJRd8q%2Fde4\
        z4sHTVRQyjde9dGS8A3YxNv0dyesmGiFL6lloDJDW0Q9fy6D8%2BiK2nyO7pCP8g9fgnciD\
        FSqjNB9cE6hgAi0B%2FOr4NxAFg4yYnc8W2BPNiFUe2Z5gyv0lvvOTLQKiXv4RzVGZE8uBu\
        BAiZA%2FqKK%2BkBBiPRTe2vRKS7Ac6rokmcswoGeVJ7h4KO4E5y2zVP907lmjiUWnoaX8c\
        5Hy64r6n8J%2F3lGW26FgjE%2FAM5B3P6xPlLg3ejLGg6VPuszIMFlpQX4FE8RBpdJBSvMN\
        2Ewb0GOqUBct3V%2FH7Vwd8LqhSfGo8T4fslUEkuxRFTT8jQtrd2OABx72T6Xt1sum6JVVn\
        x7c9UxmG5OUTOxtkvyGdw31CJ0r3ItMzDor8RAkFxIm6wtWT5xOk4no12PK257ExZaxjn%2\
        BYTDzxVfkMA32rwZz9zOURhRpLD15804Q4joPqQs4rUEoXwaUsf4vBt7J5fj7j6C5xFmg0K\
        uYGgF5Gs4%2BGgMCrs335Vf&X-Amz-Signature=a994c2cc388b5c560121a743b9a5c46\
        1f6ba5a932d923fe505841ad0253aabb1&X-Amz-SignedHeaders=host&x-id=GetObje\
        ct"
      expiry_time: "2025-02-15T10:22:47.535Z"
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
UPDATE_TIME: "2025-02-15T09:24:10.853Z"
EXPIRY_TIME: "2025-02-15T10:23:54.865Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=a69add12c1d6f4cfab0bd35ea188bdb720b94a3594f7b54236d0575e80219d7f&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=7f8f0c3b545a03bad89e8a631bdd399b1fe4a367b86d16ab4d13be9190522088&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=8eba046356853ace239fa1bcc175a01c1ba719f961046c02b63d8c5a3459f2d2&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=fdf56410f6f36eb926ec494cce5d8b2579c48f60790cdabed78fa291bf6d4a37&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=470f6783ba73453932dfc41c056236a09412f92680adb06d7df4ed83c53ad90e&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XRI6SAOQ%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIBIoPT6J0vHYDImqQdaUQSMQ0pz00pYNrGKEm%2Fo%2F7KrcAiEA3ZrdLCAyoltSRwJSYdV%2FBD8tyQsNv%2BVxjmohEYHNrfgq%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDNFBStL1li9Y4LbG9ircA1JIJioj%2BhDYDoKDyvNCn2cDdx2nuskC56R%2FZbJ5oBtDLbzUyd6X6BAn3NqSGZU2m3HlJ03LHCew%2Bio2%2FE8nz3o2OlwknqTXFL6lzoDryD6E5vaZej89XbD23mNnwnGaCoLyJ0TUTLjrFlgDl6AcQHbacwLD6KvnYkbR698ATQbU0N53vOs660fs3owMg6ZbhLOYlSqQVLAiGweO9lscN7VMn%2BrQa6okFcjkPXtZJJBfk2lhpxaxvJCMgZ3bKGhAe3tuQSjWw%2BtCGjJi%2BDyBMOzRA66%2BUBglkb2c4hysHU8aAZjYOMu6TQioxAg%2FN1DhzYZuPpi73TWevOdPJrBlV2E2%2BryyOvClRfEZi0xQfJ%2Fd8miStJUMjncLJVtDbLpKztATIfJJNn2JHBsDGfi%2Bq%2BCUysiVxnn440PCzGSmJW%2BS40eXAj40k9VH3%2FNh9v1Aug5tka3UX2q%2BePGCs%2B6ohjgd5juwn4AI6umpaIJCmLLc3M4GfUw%2BduNRqXcW%2BoSL8zRZjX7AokvlGHYMen3%2FB0m4l6zvVGM4ZG9XA%2BcgzFNwmTYDJ7rYWxjZnOLdIsDktKvh%2FThtLSWn0dYzZpp6BecggI4KR%2FxuwIjzokvCJ8KeMNp%2BlEKrrOJzIzPmMPyEwb0GOqUB3dvnXeuPzj%2BwydnE0kPGQsTgzj629PqABwGkO1IBStU9nBP8ZY4qtmbr4ELG8BkbqXshTUxcNJdrZzZkk%2BabsEMEQvo9PcH6X9i1cGtilQ6NVj6pIAFwzUTsoGd5ku8yljZqIax06vQat9%2BFv3xM%2B%2FaoS%2FZYIavHCt2AOvLzA7eK%2BoN5hQA0oVmg7R%2BeZMwhrKQmtkqYtfT009kNSZYg0rXVbMc8&X-Amz-Signature=334584f9aaedeaf7c97c5b49180dcde539293812fa3a81286d9a7fb5d12892f4&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SNF7XDT3%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092357Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJGMEQCICWem0xo6QAj9faBaHkPuwBQptqpFCMOJP%2F6rftaplCVAiAbgXDFx0c20ZoRMr74yhRIk%2Bn%2F9%2BC9yHLm6YTeXrkVNir%2FAwhBEAAaDDYzNzQyMzE4MzgwNSIMIvekajZ9BP85A%2BG5KtwDihD2hSlGQPy%2B0i%2FJNG6%2BISq00L%2B2HngKCip9r2s0eImzsRV8924Y%2F8I%2B3jrrriQ3AdPB5Sz3Wqhvh3P9TScqLJN7EgKvTPPafGFjSJ0OGFgB%2FoFoxvDat%2F8FmPRcd5rO1IlOGsRqE608OZTIVtG0KSterGALPvG33zuvrvWA4cVDhMsDgeokiTF%2BUniEiuGft9aE3IXmpYvQ8IzN7rMbpBeA1snxEdCruaYeMko75Vv91uFWjgtH8iheV%2B7EbLz9sQdVGMPILLQlZifoD3DEw%2FL4xHrgqw%2B%2FZOjBA1DGoMqGlwdoB3nu5LOOic56ggHt85diXSewhDOT6qEbFL4ZPmfc7BIJfoa8idqcg0DR4%2FqCG5dkXo%2BrcC976ZL5xnHswF6qgLdSZLi%2FnlclmiWSeAx1kb9ZrBOmjYO9a5khjMWL%2BYvPbdzWg6Q5arj60daEVtnWMkiBXtGK4ujuqthuhzmLdAmDB6iNopTNN8VZ5BaJEIQVeP6%2FMEl1tYOHA4wi0G9RnhAoGInbRNEWqZ4Q446I%2BvvRaTYAqqHaSFBFcM01o769ShXxggP3EYcG5K7YWApiEkt6Yf9if62is7yxUWg9D0sW5hRBvFg1tkUGkH8jgxJW9g9c7kRrlBcwpITBvQY6pgG4%2FFZoGo0xubHq0FD%2B8vFuYVe0RE%2BB3VMwT0KDidrAsF2muvvwsgvYE4E1y3LWhNedoYsB5Ou4d3pT9wBl%2BdrXZrPdAb2w96%2FNi2WTIzb89t%2B0phFKhbbooNTJ6uQZ%2FDr%2BOigOkL6YoziTOvehErxtTRhz4aoC%2Bbcv46QcOlBncuU04uEf%2F4I5VH%2FzfQDOhvoeF4ZU4O7BxM1eKTlqr5ZgoWmKdVgk&X-Amz-Signature=4c2d1e8f897b17765fcfd1b4bc34495c2f6169ebace12e48f287d27fcee67a0b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=62a3deabf4ad9126917c888e2828789eb34afc6ae0906fde8a8c8fbd56398515&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=86dd47c569a54113837d891afa881e2328523d7d0809e43cf89456cade40fdc0&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663KNHFH7N%2F20250215%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250215T092355Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBgaCXVzLXdlc3QtMiJHMEUCIH78vh9cZaMChRJ6ZlzkgbWUf6M74N4JGIL%2FyXnuMFC1AiEA2G0YxjRM3hn1ok7vegBSxY3ZZDHWbSEHqZqcrkfzm94q%2FwMIQRAAGgw2Mzc0MjMxODM4MDUiDMgK3VgKRzeN7XbbACrcAxH34c%2FxVLT9ZGNSQGlIx48kjHNTvpaW7iNT4ZvaD9ZPnrTBjCnT0gGv9CO1U8W2VOEISLN3RfBls8FveFJWmS9JjLL6Lx4C2vMp8SXiks067%2BwwE8YU%2FQl2vJ54G7AQ5xBC4w%2F%2F3i3A1cIreKttsrmja7yzxOXfjC5YeR3DM%2FVfupLHFar1dJhhKS96Hj%2BcVKJVatYnZWVBPrcB4n4v21pLVMr0CBmjSvECMf54SgYjVt7PQbFwDXedFizm0FIwwzoxs2CgX9XWfOxVaJzKgY8nf7TPSYjT7HT1EMg1ZZqBXcEXsvu7GZfe%2BF9V2xqKFoP4ogZzfIXHRKgfVomoVUnL28TzxO5oF2tOCcQyEi0Q%2FT9vmkgUoi6EZhMHNtE8ZBGp2wZS5tDf64pkBvgzy5NDfIBAb7h3FXeyxV2YZBn99aGqE27E9iBxobwBsuYPO9l8HkqgqvfyJ0FlzGkugE73H7SN4HXPtvl3W8ZFcYq3IcAEE4vgg0nRSVDkVTmr51zlmuT5qkMBTbd0eZtuQWoOccNjT64EqvmLL0EAENnrRQ11hGBR65WTLBGLNMafCwq%2F0pFFpNz%2FOuC99M4YcXBgUlVT0EO%2FWA2osCCWhP%2FxfPi4Pk267RTdWsrOMMqEwb0GOqUBKZaCBfqKcOoIIKxrSw%2BQsPqSUR7SXyTEXk4mi900M4%2Fn5tkMB34zm%2BE%2FAKWsg17PRQan9JZcRZgRqDeX1iLsfqCR7qQxpzccrtT3Lcg22b%2BHsS%2BRZ3Lk2Otjh3xH6LUJUF20pPgKE09Xrf5OO48pBSyJD0dYpr1ZKVIkAGJ6T7W0etj%2B2fEMCimxV%2B38Lx9Y91MrmsJTtlzgTQjdxDlG21fss7RK&X-Amz-Signature=a5006b06bc277c2caca80bc9e63e1876c316e9fcb926630856a4fb76f91c1337&X-Amz-SignedHeaders=host&x-id=GetObject)


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

