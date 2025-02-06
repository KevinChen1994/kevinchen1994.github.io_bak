---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TD5UHMVT%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250206T042849Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEDwaCXVzLXdlc3QtMiJGMEQCIGNvo9cm1d49iJuu2AHqo5c%2FdFh3D2OJZ6A2hIl9ASJvAiAZ3\
  j8uOvRuvW1g6bDbFZeHnRTeDwEbzc7ZOqQVsW9Ftyr%2FAwhVEAAaDDYzNzQyMzE4MzgwNSIMn2Hl\
  wvv5D0HFWq2jKtwDRgr0ODG3w1dzwLDmvytJX4APPf%2Bat%2BEt9vjvZQtfP%2FP1PnQ4rFDewBC\
  UUsvpB8G67v5vYsxrXrgQwMBVCQ6SH5gsYkGqI7exsxE%2BOUzjwa3aX6CL%2FaqDYfOOq7H7QeUZ\
  vwkp6%2Bpp0cNWE8Wc%2FQjpixEGJUVMC7uA%2F1zfzap5mmZh95rWrkS%2BzL1S04OdIuQmiRS5Q\
  fkUTitsYKCHzQVXT2DnlMEY4LqBUrh2lqWDENntCX7Dps%2FpUrwD0XCnd%2FxtgL8W0D%2FIMowR\
  T8OKi9YL0z4vrzWlQsN8E%2FjLwLvOo5Sdgh%2BGtc%2BSavp8qUVbwVi9tGIdytypvYZRffyMiLg\
  QDpikxG%2B1BJuDBPzz1COjwD9DSz47TpD8hm1lxyYYx4%2FXSRt%2BiGgGjt7tNI0PdHLt0UBuAh\
  hT9Sc4Y207f8SwlCKVm7kqNU1mkcY37OFrVaUxvHprmZtCOISCuxfEFUpXemLpNCb0rA9DMnIkhyt\
  %2B8F4ak%2BsKasJCDtTCo954YSMu5ZrP2m%2B32sJ9yNC2Hqx5U7yoNBTyqGGkQRgc29ti7iUPDp\
  BKK%2BHsXTypMb4Sd4keoA%2B6ufag3Hkh17DWTm6QrVJNdNUQ4wcWKpSuC9uxodStQZ3Jef%2BwK\
  ZDO%2BvUwyOCQvQY6pgE0uBxCb14v4Iczd0cpwmQqX7ubXIlp52d25JIOUu2t5yS79JuwPxMCPcQe\
  7OVc3hQMbK%2FyVi1el3VZdqpq1LXUQhAmGvzlB%2BlS84JY80V2IVPpHpnl8VrBc7q7LU8%2BhQY\
  N8mBoBBfVwxtO7kfeCqffuNgimGvXb7ViPC24hUQ5x1UFEis%2BKj17EXpuJ1JtEyFKqxfHtzh58I\
  KcLnlk4rJbJtH58UMs&X-Amz-Signature=894618a31f626a9752bf5a006b84df32d289dbb286\
  7b6f34b7ca5fea9b986834&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466U5NWD4BJ%2F20250206%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250206T042734Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJHMEUCID2ROY5ridXJjc58WRBX13BKsUZ4qC8\
        PPFduoz%2FRlLbNAiEArWhFe%2FmZeMdeu8%2BQOuE6i%2FtIms5KZktpMO4vkosd3HAq%2\
        FwMIVRAAGgw2Mzc0MjMxODM4MDUiDN%2F8cXVmh7MQ724mGSrcA60Fpq6oDwsBpYeS1elo6\
        EgsaUwuItBeMR1nXWaDG8Kl5j%2BVkJkUFyipslvVPh2%2BqZ3FvJlKJn9J8Rli2tnBFxM9\
        vO0%2BEYEs7sSHYG50DQLpzqV6sP9qrVsPMMMsu9Vxa5FKTmNaRofgStc3sZWLMLbRAnCTY\
        %2BfjQ0Oc%2FzVn6anysVYSqpQxFiAT8k6F5WOWU8daQHBvSEaBl9RbIpWYG%2BzbnHaIYL\
        HQG1ibwlTchC%2BbIY%2FGNT4iWsVmNMn5IvoPBp6xSxPLcIRaJemtuzftf2FxyQbx3kp5K\
        R0o4aHFtOU47IYbRQMvdf1fq6KsmFqblTF3Pf%2F2JVUAW6eXDqmi%2FSISplzOC9QZWrSg\
        Q2eGI348Nscr93NwCSANnMLIEWvpoX64u8ftNtz%2FgSpmLyeEOYjFT8UGJ9xeSorq6EZPO\
        sUVqdeWMrzFSHLO93c95vensG3O1HTf5%2FoZ2FpRwtGSfEr1FKJj7S5HfNd9qMShOhQor4\
        nxMGA%2FXA%2FPb5ewv6B5g%2BSrtnrb1Nq8xUH9s8pmGru4pcbM8O1vlxrv6S%2FeBG%2F\
        nQYSPZ7a%2BCComxwmKQx2cPqPh9IJM6dM5WKkyV%2FNQL6eDWX9mZ3CwCj%2BLk52NCzkc\
        t%2F9m5dp6eo7%2FCFqvMJXhkL0GOqUB2jb1tjT9roP1UXS%2BtoRF2iFTfEuaVJixz0Qcc\
        vxLkKebh5px1XfANPKoQn85%2FKLv7P8P2xWg40GYPUitYXM0ZDdyg9K7H1I3R2B15jDP5y\
        pxYh%2BN8vSZHCmre4asO%2BwcrHMIvyCZElj%2F%2BZg9gucIqE5GvdkKkLTeFZnZrUvq%\
        2FnHG7pRQkf9fIwhWzOLVeRO8b77lB0u2h7%2FYVxzCP2JtoYDTQ0gC&X-Amz-Signature\
        =5b04223ab66dd60a21a3ca040c8492ca5e0c4a6ed2d7d6df83da0483f0b3035a&X-Amz\
        -SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-06T05:27:34.639Z"
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
UPDATE_TIME: "2025-02-06T04:28:54.803Z"
EXPIRY_TIME: "2025-02-06T05:28:46.957Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=b351757512b66d8d75905034ceaa5daaf3b4c5b6bf7a2660af0ec0d0e01d6287&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=c6791cb07c3d58d92be7864d8f77c8318b299e25e299c4087870c3870aec694d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=f48e988a78ea75986da14b65d0ede0aa90193d2a3e673b124828ef3216e8c60d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=e145b3278763c9c0fe17fdc6a113177c7459a7924a69fd2f8df23e47078e7a67&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=95de1cfaaa4058d1516e9670971fc0d2dda767c7ffded4d190cfbfaf7188313f&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663XPB3LGQ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJHMEUCIFfx0P6pbteLm%2F5JjVSbOf9eKcDV2svvAaXRecH4uDk6AiEAvPXnzJ6njatjLvyD2y413bKmksn5PaWH23C8EyNdMqcq%2FwMIVRAAGgw2Mzc0MjMxODM4MDUiDJU4W2R%2FU2X0yB4q4ircA5xjnjLIRhlpo1NGbJAPQDID1Y90OP54cdNaBFJFFvxhc8aABiZW%2FOWw3neuZNEMY3yFCs%2F2vspr%2FcKyp6vnp%2FdX9Sj4DRuwYtaNaAkbNtk9AH56z1jBDJSyhJWCl2k4EnMs55jAFvw%2B9bI7pB5hdpHRioMmrIztvugkZrnGFW1wlQE%2BB2wpMHrqaIwZ6J77VYt9AVMJDWzahDnZZL1JjqgUpYM4DBrjALCQVgjq53EcLgODEIp6TMHPdR4pihLwXesRwH%2BBvFsQ2o7ZMd%2FvsknXC71xiqF9flHS4cUzMAHsFiBHZLHlzsQLCSyLU7kdW559YQX7xxMwvkIaPtjbSnw368fWA2xITgPrNrdjAqlROdaERX85UH%2BkpvHuOsHnWr3lf1Iyg5b0xmbrThS3EY9DJuaRGa9RWlyU92r8M1Z4XQZM9ASEtfgdVqDQjaZgBCo5Dxi1VQsk3Xo8Lz5AdoC%2Fc%2B1FP2HVNcyo6xIqEXnSQ9ZK6Anzp4Nie7SiJI1a5HcNZhtnKfQcvBKUX8Mb7rHJqRxNu9I2Sdri3bRKfk8n6vrT7WgnIuR1x6trrTQ1XT%2FveF5IxqQRTC8aY9R%2BXr0wPgZ69SxcNzh%2FLpN22kT2LSPWVIpAcB35gLYjMMvgkL0GOqUBTqNRKFH1LslqLvmGNIIyeI6BF2TW5dCBwZWmJ8SHKnvJP90Yi%2Fyb%2BhDVIAYper4LW%2B7N%2Fksaa7%2B85knRzsfAG1SABfbtBOVA26bNYxGZXjaml1r4ffDLuSK2UuC9dIIIrupvVSh668%2FJFFOR5hp5s%2BQ4JY1jflKNV66YFKpgBS3kJm2la00fjLYR7o9ZONmD75jYTbAu3fOmMPVRHfZ0%2Bw6S9YSC&X-Amz-Signature=dbd0cd48a22a9a7fd4b0adb173ffc9b70f480f641b3059987280774215ec9759&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WGCVV2WZ%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042848Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJGMEQCIBQImf9EGtKWGQTJCIzh5OAc3M3JeyP5zNPkXupgItYMAiBwDLmVporV9pEBs4%2BqAfgLesbRyvzbFjVdJRxxGICu1yr%2FAwhVEAAaDDYzNzQyMzE4MzgwNSIMwxO%2Bh23XdxKmnzcEKtwDmyVrf6KwuCo7qZrbjf04zMYpRnbu%2FBrjncdHDyfJK7W%2BTlXacIHT%2F11avdRU0%2B3kDof8%2FdFypATSuh57VGUkr5ShUsQa1rh%2BlsxRDzw2D0pvNzSeYhiFvXE6W4R0L%2FpJXsDM8r7fcPh3RcRUFIRzFeX4Sh%2FNzP83dmQ0QhglkkibbPS7TP2RreC6HI9EjBdYKWIDYKscNx8O9PRWa4Z85vtrIExRhmOOacZLhOg6WVHl4EGgH%2BD915DpMh3wfHDd14yLlcSFtbESj2JQVBAJ6frrdwHcKqCDjxk4pUNhO7msX9%2FhEtvhnDVihax8rSr%2BuS92mDyAV0Ocu0MRn%2Bbu7%2BGw%2F3ZrMZgnF3yjeJphO96XyLA%2BX4ggjl1Nk9O21L58pJGPV0zvRAAtBbxEEsXFHrLbnc9zjuJGUD6pPwZVj4IJ%2FbtTlAR1Rnw7t0CNlsPibtt7vm6nE7BfYkpTR6mQrNgSnsZfqoMX5jE6DL6yaAq5nBdok3vbfsEUP%2Btgg%2BXmxzIwWNR32g4mXDEIznOVdlK2j60aewze8K3zAJT6CPvtxrzZ0iYDrhySIGJE%2BuOoT%2FdVWqgOfTGpadO0CRxCunBLq3ziLPAsUxWVVoGPcGPmen503hxCYw4Gcy4w6%2BCQvQY6pgFW7Tkv2LZ5NNjdi3D5A46hgFTLzMpwPGJQccuTrTP4Fn96Zr5EMM2qSgqsgiiZ7dPwysyRMVPW6FaQCzsQqLIYBIOUMzMZ14EcigoeQHNnmQDMzFTvLggHu1MWFl8l4cb3QqoJRerpoM7%2BslowM2vDNtP5xJ9cCKteCpDAqxO4EFcK6TEzDs2JUt6YJIE7tSCqRwT2xOlLwEPPxHtpBgG6ZoYaLIFE&X-Amz-Signature=77ead064eec054a81fef9318a839a12cd0f81c59c0646d2454da9d6e80ed5c8b&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=653e84ddd5df62b5e68c0ae7ef7bb639b9e045c095f5f25745e02c1161768a8d&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=00ee35105b05c7bde695252ea5f4221e3d29ae146c6726af494ba7eef9e4de9b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466SF7KFHBO%2F20250206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250206T042847Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDwaCXVzLXdlc3QtMiJIMEYCIQCvqCwmacSkj%2Bn%2B5Zk5XqrskH7mJcBm473pvBXvx4Y1MQIhAKUyUCDZAyEOoFzeIlh84scfax50lWHXE9GkI5MOoJDhKv8DCFUQABoMNjM3NDIzMTgzODA1IgwE80JAmklXOilaa3sq3AOkVLZ61lARhxa3gjgNeOdb2AHv1UQWtd5dZFk9GqFP%2B1Y%2FD7akyyhpO2Y78LUmsqAPxY7%2FXbSRtbDcddoOv5vNvRA8s2kgcNtZdM%2BUQ9TET45nFgczZgTeyHApx0zgjOJMVHMz27Ay9cT5fLoJtOInNsrmbsbKoUsQ4U11tS1Wref%2Fy9k5ykz%2BG4LBUrt092y%2BwGqKakQYkc8qw%2BplD8e98L4lGSI0OYPenInDxeG%2FSoTOZyB2QPeLGGYFOQiSET43lNzzOnWkVCmWyG2n3rWCNZI6FcZyLdAGc%2F1odBTkiVjO2nrFPiLVR%2B%2F93K0RqK8MLRyOhlSHlOSkx5cloiFZUpwa%2BXGy5DsdnnFejynRzP56tXc614UslPa4FiTtU21CCEtuuYgJY%2FTs7cR22turFnhEodCp5e3VIkhYJFcmXVRu3EUQ0%2BGJ3gXx5AnYFD5MdEi%2FYNqvboJu2q8dAX5xyh5BgQuSsVF3a862Bjl41CBQZ4rKKgxg%2BW3DfzeTFOIUOB9ibWLiiKEiUIJjMbavd1SRCp0Sn1iN8wyAgFvsYZTbgJKhzdNsPRKu2jgzRefbd45dwGT%2FGlSQ0oADeaWLiB4g8%2Br%2FBrzzi7rUjhBG4h52BYj2VAz8AOZ8DDDS4JC9BjqkAXQgAIrBwUXGsB%2BPOYcOL2IIDCGMCN6wbU5c9aebyzEKNstNeiju%2BeSV%2FtqZ%2BkTleb2r%2FpKpI9SJ7AlTXp%2Bblv%2BXYIYQez9DYbTot3YG%2BwYw%2FGyExTpDe0KJvdMD%2FU7o%2FZTH0%2B2o8El4LA40kxc28jFDySLO70swAiSrrdY3cRuNBrkNigh%2BJq0ynIs0fkzu%2FtlXp66MrzeKK92bmX3B2C0cjpZY&X-Amz-Signature=f45002f4141651653915a12f53b9c57aa2d1e017c3686c8490a25ba99341de11&X-Amz-SignedHeaders=host&x-id=GetObject)


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

