---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB4666YALQIJF%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250218T032713Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEFsaCXVzLXdlc3QtMiJHMEUCIHEZA9%2FzHCvQePLdWfLOhLEq9JODTzU%2B0e7SL0ZDhq4SAiE\
  AlFr5MxQYI91y%2F%2BgVrIhs%2FGD2BbbtsRteA3kxkPbRT%2BcqiAQIhP%2F%2F%2F%2F%2F%2F\
  %2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIIjTN3IpdexGKYK%2ByrcA0nP3YRqbug%2Fv6fgh\
  v8cvHd6u5RGbOssh%2FAPe8uMOGkG%2BomrJGbC3rglOfi%2FR0%2F5ZfmdW%2ByRI%2BmfX1db1d\
  xBRiV5aciYCMLuUP4%2B6xEOn%2FfJD3VFdDpLAx8FI7n%2Br77lMP3VzvLTrhkYdOXXzQKng%2Ba\
  S5OiXPrch%2Fli05C091geK8GV6pc%2F8yzcpG0DqxZVnyn2P4AGlYMIr%2BeeC%2B8REpFdE9d0z\
  MLKGQZ1bq1%2FLFg8japmOkknw5cP7Wd1bdkVzO9Jb0LAmxr8%2FVgI%2BpTj2qG5zQdiD9SGaTa3\
  uxwyoJzlGg1qvMMJhJs6Jfas1KFXMo6KJEER%2F1mhhKbyPoB6sjQYSwF%2F5f4U555jnkAYHhuX%\
  2B4d%2Fv6eXpfME3T9Sz4UA62%2ByPfID3FsM6vfW%2FkM%2FPTn%2BGMpLrkAfNxSes7U%2Fd5r0\
  0TXyhlJDOWvqAm7Fhw%2FLxDDQjYSG6MxW%2F%2BmBwUDO9sz0mEtjPApWELErWlfAYTuTcWrjfT%\
  2F0m%2F%2Fl59UEkZavJvwbJTdrr%2FAtjy2HgBjr%2FlcGFWgZqw6SD8vXxXuvMnmaPpLCR3ZiPP\
  F4tdqtztoqfKZgMfIEf89PeRjqTvExQIuHO8MjKfSHg8g5MMrD4C4PzWTigG1fts%2B86PFFtMM7w\
  z70GOqUBQANxdxCgzWJL7EBRoAZr38PYhPrNFOcSIrpgamqBJGIntc7%2Bnxf2iUO46GEThMLGG34\
  o8NbXND4%2BWDrirw2GCDgpH0WoEwyUoC3Xs2n5JGRZG%2B5ZiDp%2FeZ6SKExrTE53RuBQBQCCq3\
  VFY%2FFymrr8X5PKJrNyIY5en5MVc3iOUHG1DJlV93E9%2F%2BzynBZ3kUiKY5vtMnaCwrWeGZId2\
  Zu7KV4KkNrj&X-Amz-Signature=6e3963b1fc9ca817addbc85bb768362e371886c55ea6f67a0\
  c581dd29f461a45&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB466TLODOKU5%2F20250218%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250218T032540Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJIMEYCIQCB%2FyTei6OpvTXP96%2FI9RbPu0J\
        CWVVT%2FARFP%2FHqqfQplQIhAMHDepaYT30vhhQw7%2F39pivHRRgVnuOtgOyYQp3qm2DZ\
        KogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwpYKqhNcY\
        C%2BPJarpAq3AP6ZJhBZo6ywQJ3BlCDGvE4JBToUHHe4kpyqwVx%2B57SrzauljBuv8zfP%\
        2FsOvPVQ73zw5yPc8nIIkVoIHevj0NuFPxE2bHa%2Bs6O1Gl7B%2FJ%2Fig83oLLfcNbf4c\
        93oh5nmhLG%2B8SZqLdZcyMaaMBQJFs8KSY3pRiP8cTKONN99RsZMBNYLNRSXHoW2Mm5ZA9\
        kDlEjY6c2%2FHVAdqUTACjwdkhE5uE702SpzttNjIhlpheygk4Fg4Fp%2Bs9%2BMdE%2BWL\
        y8Zl%2BkEIvSVUzUxCITNVGNYeIohfCq%2FE5J%2F7%2FZgjSqp5fBdYLhmUv7IafURHDnG\
        %2BTLeO2PObQzhYchHyXZ9EVXR96YCJyeKsc7%2B%2BvISdaY6XLcVUmR3PdwDZYaX0LpSJ\
        tl%2FMkEiHne7rZnQGC76P0BtYXp03rJSLASSx7vw1knJGUUl3JNpexzKlKq%2FTnYLjBQN\
        P4AMhZPGhLZeY1xUlXpipjJM8nm8Kzd46P8wn0k1xzmYl3bhJVqy%2FBdP2tCfkQEHewB7w\
        Wv6uHOU5GsJd9wUMrs01bSot7az3mttiorzFoUurTCFr7duhmmLYRexPSopuJzbVPNlQdjm\
        hvp6pciT2HbUNGZLd4dd7fRQQWQJxnOqXLmYPCAmYbkYB7WUbTDE8M%2B9BjqkAb0DmUJha\
        HW7RO4sFvgG%2B9ejth%2BuKF2Xyv6zfKsaO%2Ff3h42%2FLdNFO9Y9K%2FJLSNv1b%2FSb\
        WfR8XqhHPaAJz3FhiYPow50Po5mlaaUyAL2qJOXprODwP8njMM5Et5G0DmRZgQY4f3KpjqL\
        JUhK9cv8YtEWIoH79%2F2qsZ%2FXApewXUsaew%2B5XzwWRipNZPBJX1btUJdmF8Hn6paq0\
        HMIqAA09nCSwZnSj&X-Amz-Signature=64771ad3749ae5a5d023f9b803f570146ed0be\
        ac6efa662a2dc5e1cb7695e796&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-18T04:25:40.591Z"
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
UPDATE_TIME: "2025-02-18T03:27:18.164Z"
EXPIRY_TIME: "2025-02-18T04:27:10.045Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=ea9fad2521546a1d2f55163f09538934a37166ffd5e02e9e8e9787507d505938&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=fd8e570c88b3afdf7252dcde1c427779790030cb622f8ed4d42e77ba371980fb&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=752e17358db10a9f9874eb24101d8754351ecd42a4ff6851ac589eba932d406b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=a3394861debf7295dfd56bd227e6b962fb4ced36325f4892a9b2eac16c1f4368&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=72ef483d1154d6703d63ab33fb045cbd96602a264a2353fe3f8992d6615daacd&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663WKZYFS6%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032712Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJGMEQCICBRuWT5ccdG%2FrcfeulIP9D5QYRTEO07KRnMlPimw5G5AiAxK6x6lkMA%2F2AkcYIo72gGFRg1mnyy5FYm%2B0H%2BCCZDEyqIBAiE%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMTB%2BOPAP98a1e6etQKtwDC2mLwVTaFJJCInWW%2B0Y0m307ZIzpVvTsXEdnlA%2FmDZ5paIVS3M5bfXlinv3Q%2BsHVWsjXeZlAx1j9QGVh7VUtB%2FLEIyCsgEFtQ9rNw9%2F6lpMb4E%2F9EIm7kMFJoYtzA2tkjXvqNDZ%2BjYnzcgf8yijIU27iPWYtd%2Fy%2BE5DU1HQ%2BymyYIEBAxZ0qMnoYpt0n0jaPBe8XiC4d1zKOhqJ939b7xlOP3KO51bB7jZZJWoOSdUkpdq%2FJ2AaUj3V4o3p12m3zT9E8HomFm%2BCIXwkkgtw7shNI0K31BVwi5GVRG%2BHqQ%2BLXQq8m9wrW421UWkPmKWQF7tfDMvTvwMZtcIVxwk%2FViVpLqsdP%2FxOEAKYvtwUku9x127QpyoFbOfjyF1JzABAWP5WaSxLRFULd3XMxctmCqSWsW2YuibbIB4pFcqlrlNyYrJpP9JqQd495uVC%2FnjqJtjzdiNx03zUuHXXpayeQF%2Ff83uKpA7aan1iT8yqJkVoaXXLCode%2BSaxNZz5Ioom9M7xme%2Fgn5GNKtYw45OiGkv5%2BVwwaQSjRwmA%2BxGVmSWmfCD3Adaf%2FWGsELz19J8ej5CIbgLfLnWDn6hUl4F2FjITIwLz0rFcbv0qCRX0%2F698bDVMbhHAwYepMCb4wqPDPvQY6pgHGAvghcoea1JIIIYf2Q5zwsXrx7xheHzCRDIvZhT9Jwh757F0Qx1bhchnCY%2BjdjUiw45ZtaXkCOZX4KrSsAjZEDw7xWIjNMLnSOCR1IUgNomn93XmXSWcNZiCcHkaydqm7%2BRgXqNifXz1iMmVdqzNwf%2BMk%2FyqsH4zjD5wpLafogrRaxsEsO0IGMeD%2B8EFrxRc1xtNuoMFlZwOdT5%2Br8PBAfIogMbtu&X-Amz-Signature=4cfe1a493137cf418ec1a8259ae7df110fdce5ef61426bb18702c85f022f866a&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466QRU4OGFB%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032713Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJIMEYCIQC8JlBzAOKipjRZRypGaeOnkmjUiQAwqxt%2BPeAMOrG7cAIhAL0rSn1bLbRKwu99Fws5y3TBfQXJPMboE6li2sAljAP%2BKogECIT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgwQyv0kbR7tM6nWCrUq3AOGcJWt29z5w1nBS0kBeTTEYn6Xz4opc9pmjnQI%2FR%2B6byw0%2BrdV%2FhCJqllg2JytqM25r1BvMNgTbA0W8HjTE82r1jAvFPGqUIYKxEOlDGpT05oJmGgOGiKkukzDqMPyWosg4wFyEd32c5b7LaFOREdnGrK2DQumKvLNrAORAC%2Fu4drGvK5ocwhrF0WF7vbF0vospp7m1VGrlIP1VSC3QpDpICIib0uWBxa04h3edtTQ3P4zFpq%2BZy%2BAnIiKSJernzuKtvs5b2cqIT%2FBNsNOY1OS9b%2F6ovi7SxhFqwlan85U4DaJ79cZoOHUOjUOXjV7ZIPb4MdScSzym6bj9A1%2Fx71A8paEZw9L4tTwtizOyIjFnKMqCpppRuRMOWMgpPeZzF1uhYl3W%2FYYst4o4%2BrzsyQD7WOLC61qYfthVUPMQBhf28x%2FHU5YDFwpxlCRkD%2BbqwmT77aHhl2WC%2BuYjHF8G5v0leIGaQ0fYX8pk6Oo1OD3Dyy5oinkXPlWzURe1buQ9L1n2UoGr52%2F6GOyroRumGgFepn3Cv892VUp1Hv7k3pZE4NIG8GY6Qg%2FVgcNZ6FcRQqGc6o%2Fga%2BkMKAQqwPtmY%2F8YO6igPdhqQX6Rmg3bZtK4WXq7Za2ur%2FZYCQ3IzC08c%2B9BjqkAXQGbqCM4gh5DFcDDhkY%2FaFHUNjf5tv35kJHB%2FdIdwCJoNH07j6HUaHhddWtv%2BSvdj0TXZ3ndX3%2BH0BDzGK5hqgUSzdAev4xS4C6JgfrIy9wz%2FV9DvBr0B8Es0tuE2mthOSIvE1bcB6bCWBW9IRB%2FknAIr4bCA5kMcLc%2FGxlTVh17CriYPhCevZ733MeTkVMIDDwQQX5eyrlLrG6SWILgBGioq%2Bn&X-Amz-Signature=e0d988701d0d289a1a27f0884e40b06c59f4cbbecb6a58fcbe8c82a2f7603b7d&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=63d5596c70916456fddb4ec5b99497999174a7b8e717887cdc0d1fe136b9063e&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=90cad7d76ddd83f9be1f47ff9379822c0fe0c982aae5feeff5d5c0879cde8441&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667J2FSTJ3%2F20250218%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250218T032710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLXdlc3QtMiJHMEUCIG62NTsZ98cr5ytp9ZfvKHzQpuG2TbrAcbDESgdp4xFQAiEApbX6eyG6yVXUoJhhmE6ndcUTdUT0njCPP13ozGRN%2F9wqiAQIhP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDMdLxEtJ4xbc9rf2MyrcA%2BerCxKSUyUb%2BUCdSlW75s9LMADnprXGyCSHCsqmN6daN6MOuv5xH5AVYUrwyrkGGKcyNhfTlVtfPDacy6mxB%2BS04N%2FXA40F9K%2BCtPFuyXk3APVn0m2KO66JCFlwH0N%2BdolUE7CzJdxST57zFwI0BwqPyyJbF506S9t0iA2VZwuDZT%2FBT%2FWXNxMB2wdsohSKU6dVwE8YyYKna23wOGADT7JeYcj5znTzdWPL9iIsjsgAUPD1ibACwhGEKBMdWKwSlpo9cUCLM%2BV5YZyYA89Kkm%2BpWanPgswU6eCbBBMsEnbK2KhlZhSEa%2BYyss3sYjUC2NtsRbvF7aeF19v3Tc33oF5TfnrM7kNG5AEc2ycPCGK%2FUQLA%2F06BaG0OOZVYweYRonojQA5YFdejK1L6YkR%2BsYrPeiIocsWB4X7VtaU7yRLvr8ypGqgkXUP8o%2FO5%2BJK%2FXAgDHSbyM9raR0UR6NhxHVvZcXR5QN04mM%2BFbIhBiwsWStezoIg5ihSFlY9lny41nhFfjEvbMB1yecEjx90qWS0vEvSIgEp0OtdawBEqW4azts6YAi5Bnd8zYgMGOWz3DawIaFZj3697rG4n%2B2q066p1BY3UlNOp4Xs3WRqfgx0BHirkZQb9Rvzwqc9FMLnwz70GOqUBL1Bwqnq2cgnQFUmiNNTLXOLZ%2BaIyajMSc1TilJlKfpdPBfNgzW7PrlIlysKok%2Fq3JRhVBbpXPJ5D7a89rjmZ5QjL4B55x7UiqR8K5CUUDD1rZgVqG70Za8XwocSoOaXa3eGWsJ%2FVLJqX5Uj138k9xNZECMt3n4CxUr1NT%2BtQrq%2F3hwrM%2FgucG0ejpz7IH7IFQbraLIzXKcJ8m7yDqDqSw%2FIKyTlu&X-Amz-Signature=eed5e7311dc4ebd85ec8add7288dadcb94c8a40589a67bdb52dd8d31bd2ed5d4&X-Amz-SignedHeaders=host&x-id=GetObject)


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

