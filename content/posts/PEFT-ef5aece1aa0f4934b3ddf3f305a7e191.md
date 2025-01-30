---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466QDQ5IKQV%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250130T132657Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEJ7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIDpnwLkfWnlwpVjt7Ad\
  rkpsDofrrNZBMrtByUA3IscUMAiBooWeCd%2BkSUt1kewQIzb3f1PvlKVIb5eg%2FbfKzvdk7EyqI\
  BAim%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMuUDg7mIhhaQt9dU8K\
  twD5x3QEQ3FZ3EipUZ5KS82zOhfF4IENfu143OmV%2FIrGdhoT4GTST2760FJeX2h5v6jvOu645ZJ\
  Igs2S7QMFX8Yc55uLr%2FxAKrvKwj4dndxqSCMB8eNQXr8%2FNCDopZ20xlZWXBZYW4064OT5caj5\
  %2FMtW6cLaqDzeedCGmmp7oLAySGcCSOKm%2FY38EiEai4wttrkEkSp%2B9XEuSjuUBZ7oW7EES54\
  xoacBBjMS9KmJqQvB35Nj1Wp1kHUEW13WyT9It1TTM%2B9tmalGhhveoLjYWwaZjS5KyDBPK258VM\
  ORyhXHqn0vDTw%2FSprHEia%2BG1et4FfftXA6Lggvxs%2BeiJYB8Qjs5xAAtBYC6MJS84xMvQ0R9\
  2%2Bld7uhKtlWOrxvAOGgHi%2B6kNV2Bkn8Qxhnl4DSbcfQnICghO4tJa6ot6eTzliudcnrAfFevc\
  Oi4yCFh4zB54E1VUwGvnnUikyDzCIDcjyYAjz1EM1tHxQKM5jItmk7d2ctyDnuno1nQXo0TXy379N\
  g3fMxWgHHS2EGezYu8HP0jPZ%2B%2BhSTwmI54jAu0Kvz42Kl7uUp1iZAsAyJhCSe677HiyrbTegS\
  22Vsl3RY3rK26vYiFXCNhUQ7KP9%2BKHBKny3xxuGf4xt3RcHCs0w6%2FvtvAY6pgEym8lcQR%2Bk\
  zhuJ8Xls9tKGSPV0ULdcOE0DmXHweUt1Ybt%2F70r5pYHGJutolowIsCz2qGsw1eFa5qSefD0WqCR\
  vPvAXpiAz47R9nKp7TXOQJt9MXKFJauoIKnTnPtkFNqArww86Q4WQ29hgkNhxijZDo17Lyt4wh37L\
  3eYOXtpUpDo0z34v%2BC2JGHz7PFxw8b5es4QETmeWJ40%2FrsGC2baKLatl49Ow&X-Amz-Signat\
  ure=ba8127fd8ed8514376eb13c5e2f036a42f2389e8066ec678e78f545c1b17e0ca&X-Amz-Si\
  gnedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4667M7EJUSD%2F20250130%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250130T132552Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEU\
        CIQDHcNicwpTYOLiXvkDZQSl6H4vB4Yd%2B7ZsHBoIknFG4wgIgL590%2FfkuaKdBlfcxPw\
        QzjufZh8dZouo7NgCbqYq52mQqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2M\
        zc0MjMxODM4MDUiDBrPBrixWEcLH5qN5yrcAyoDpCBhEzhlQT%2Fo%2B8TqqPHdUyYpNAXS\
        zEyVBWEnewZn9GMNefL3fs5IgFhxLK1WhlDWynJ3xUTRS57Reto9%2F5Q3i4MTpPBbMcRvF\
        2lNXmY6%2FfdgvBQXbene1mfnNbIrapi%2FyyubqVp%2FxeRWH0b5sE3%2FPqaypW%2FKZO\
        AqznsOoMuCKSZSX6nKnud9CiqxZPNChGiQl71iwvyQO3Q0nh1NYKI%2BoZYXk0hHbhhU9jv\
        u28QVgLr6J8YEcb%2BJGOW3w0GpnyfijiytwCQaUW1r%2FSXT7Cz3vTB84eVncXl0RMgb%2\
        FGppC1DCUbN%2FfLwhTcjMrYn5joK5sLVTGOVD6Vj7nJuV7Rv8GD4fpnA%2Fnjnb1IDBDvK\
        lVLcAQahmMbUf28AL7HzJ6E6WTMDchd8vuPuMiij2QmNMtETYcR24iqowrpV3CvUOhweS5D\
        f%2BfiHXMQyZdUo44k4QagxZlaYGxlzK1QAqOZh2QEIZ0yP%2FwlsevY7dM2p%2BNYAc4d3\
        aU2CNHkPzmS72oqeCNMQSedebZn8wAfyHuSdf%2ByonxDqdrb3%2B3kfm2SDswx8nekhGWf\
        XHXuTw7q8HEgS5PMelw03NQ6MK5Yt7HXDBpJdrU844BkUbG5iBU%2FOpY%2F%2BGb%2FinE\
        1n4QlIeMLjg7bwGOqUBX5FpmoXR%2F6%2FZQdadMkm3IkordnvXuc8ROefBcyOpziN5ZNvN\
        0lANJBjAwiSazD04uhxv3VnWwNQbnNOY5ePbdcWItidzfVtw5Evm1ZRGabzkOH0%2FE6tG%\
        2FMoaAwdSrDF9al1xxJZRIjc9UWYnv6Iy%2BE5QYOxHQHYH5KKUf1vS7Sh6b%2F94fd7BlS\
        REvxaR3KWVIuH2fFy1j3i0YaBy4NQ205spVo%2B7&X-Amz-Signature=2fd36b3047a1a2\
        0966e5f83477048b0e166dc1a359f3614e5a9e6cf62d15da94&X-Amz-SignedHeaders=\
        host&x-id=GetObject"
      expiry_time: "2025-01-30T14:25:52.252Z"
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
UPDATE_TIME: "2025-01-30T13:27:01.221Z"
EXPIRY_TIME: "2025-01-30T14:26:55.425Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=d429e2d3f4cc53ac9fc9f8198a39308f6446b7dadd0b955dfaa6872f2a44f4d6&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=4efbec6410b838b251c4f29a0732df6146ab22d09276ff42376c4a086bcc236b&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=2c84d3e7a793373e78f2ad3288efc626d66d2c380bd8f2b63451891c84f27ffc&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=a98de776a5dbc0a8e988bde7c3064fc889cab115613a005b3e458490ca7526ea&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=0b7233887128791d706b7dd06b08135165d9786d1779eaaf3f2350809971981e&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466WPWDPKAK%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCICxsCyVpeyxv8iGXQd5uqPegNThgRg5qbxOfIvgZ5rK9AiEAt%2BCmT%2BDvFIe54M9l6zaywW9%2BZxKN4MisWKEQ4lQhKX8qiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFnlRLVOhgZSHQOF7yrcAxwxi5URmhCTnGEWBT5Nd84o8aW%2B6ADRpAU9WSXby9EOK6rbMw7m%2FBzTuED%2FV8vfR%2F8Hq8Wx0UXENCUQR2WLRfEI9NsLba%2BcGSvf%2BrJEuQI2KjlWT9EUaxIBa47xvPESK788dZ%2F35baplT%2B5HcZ%2BRIrLsFFSfD79lcFiB5%2FN56MuJdowakfLDn9WHAfkednH1V4Ue%2BE2foZXhzxBRUtUnPhfaVUAhb8pM%2BYwJQeYYhbvADMWPwMUzpofFPd0nONkCQp2ufa2L6B4pcAFSpMmSzlZvrM8%2FA5gJiA55T3siFHZ0DQXQtvx4bmBHizEVU%2Fn6UVZBTPmC7r0n0i2T20ip0aj8vpoXud%2FzaSBgxnklVD4cfPuY6HV0WpreN4bS6oYCCAmWbFlVY7xTJ8EACcHYNO2aijh0KqejHwiovqIkO7KHHmVeNRX3CFKSKFJl9qHh9ey6oFxHaReiov01Ipj2f1UT1cf1FsOxcnuNISHwpLIwrqmtsyC1Nn9V%2F2Emsc04XTcc2w1ucp0TOzAElo5EH1YSJnYt1gkbF6T7D2lFioBlZTKKb5kdTeNSyyB%2BS5DlMyIsaBaQJ17KM9wjvvTnaBqDhL04n8kGy8fQ8%2F7UQSM3FFStZpgOGbw8jFFMO7f7bwGOqUBVBmi3LrnRcdW7GYkiL8VqFcGBpfeXXNBzb%2Bug%2F%2FRI%2FXbTs%2FTXAtb1wIwC2z3HMKArH2r%2BTJ%2F%2FF8X0UlkX51fSjiNPlQiY4bVCbd%2Bc5qDRaRtdINjqc2LYMDQDOocrU7O6kJJ3SQ%2Bj2qfL3fE2Q6o2b%2BGqVdDyhHh%2BbITsYKeGjE0kIPiX%2F%2BNxRQexXeZe5WKPP5NUTRXgqnkqFHaQIQoDuPbP73H&X-Amz-Signature=d73036925cdd406faad95d3f39fa105bd7d7e69e73679a012c5f1bf1313eef61&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4664IZFOPSU%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDiU4iuGFYLOOvJNdi3ZMhY%2Fv2gKueKpRd9jN2lV%2BSGaAiEAuc%2F%2F0Ti%2FSyTQtljoIl3mLU7M4p7%2B1Y9bjMavQ%2FS5oAoqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDKVCe1bVywLVJR%2BDFCrcA7hJiMi1MbfUyfLKtBs40wg7TiOTzf8rIpGRBpGAwNhSZc7%2FkCB62wcRR52M%2BR4%2FFHoB77kRtnAKqP1cOeJIQsY2Cp6XH1UvHikq8Hnqj0ChfIFQm%2FAii94VjBu9WZkn9IIs5h2smOOkScYxxDBLrBFl25LHtWlD8Gqe%2BvE4APGZN%2FkE2pGeC1Ir9pDeVhy3OvN5LtJ%2BLJ9LZGFoT2lqNe7LmgF6J8MlsJGi82GCQ4l885DbXdSpm%2BOFLL7rsPRA%2F6F6sWAMq9f%2BZCiyfazpd%2FEWKX98ekOvxnGOPLNEiLeFSU8ebTqX05Jll311xaoKuqsoadSDoAKe55lqd1zGv%2BxbFVgtr9TaefUSFDrYluFLW3hEizlIQ93xV4utrX1p1jEReFDgQs1GTQWp9V%2FqSA18s9yPrnBo5RXSHXZkRezaEv9UiBdxrF%2FgBoWWTkjQDMbh9BmCm61adWXOEOTvr4iFUvTMWX1WK01plj1O%2BVZ0OPoiAe2gb5guyEk6oNQIdKl%2F5Bn4gm3BSFZEGP8xoG%2F2kDAFWXfsqvghGwGw8ET1QE67mXaE6u9mPnEePelyzV70sbHHEFWEfXHwny3rhoBZdit5isRye2YzYwIBXjNK%2BEe%2Fj0wIwPi8j1%2BVMIPg7bwGOqUBQvtFTLl%2BVfY0BFSc2rFr0H9r4lguaCajMydCN3zulbBM9s9Fyub7gznibNzc6o6DGRiZPr5FADCwG7SKHAB43S2YJ9vbQz%2FOZZThyJLIGORwxIETG6AwQTXBec4FZoqFw%2Bg5JoxE7HDaojya2ZfmGAZ6MBHN4SbQtY41vTut3%2BUCuSk8dV51hJypxbM0rVpm1luUdBJXW6oQkQuA4adpxNw%2BoGr7&X-Amz-Signature=14f743320a13e3e1b8c5d0e16daf79b27284fef84168f200e4fb2575a20340b7&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=1311b0ce78280cc23e563131d440694dcab52da536ddf4926b2370358d9545a3&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=ef85eaa2bd5691ba126d12a0fa16a28d98b488a94f98f79150dc5fe231c649c7&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466636X64QP%2F20250130%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250130T132656Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIF6J1XosC1KoBjpM8bz1TbgCEqMY0bXAM3Z5csJfheApAiEAiX39VfWJN%2BmIg%2FUZFeNKlLcDcwGIzFix0%2FyG6hhiuGIqiAQIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDGi%2BSYWLjUxRl4O46SrcAwFrn7lMzMiw3Z9WVGu38Ewpg%2FlRetvoEVtg8UBLzSx3GZHkCpjyaLWxhAMKYv%2FIGQlP%2Fl%2F%2B0fyF52oPrJpEjTKTjxXZjq%2BzebcotnQ0afId3XLNH5ocUeA%2BY6l3p7Ijrx6dbJIGf2KqDEo70fiitCAMI71sPJ5%2BKLfxW4JWIaGcbW%2FE%2BtET%2Fq77RGoPlQG7x5IIAPywgrwW4%2FJcuvwVN9Agtt8itH%2FnXXNv5NNnNID8B4hEKQUtrmaNMZbzf9ci1z%2BsMMBOT8PrlyR9pAs21fbb5%2FVtYmmaQfnu63I7RkcqBl%2BXeKYZg0l2ZsYOYiWoILsgtI%2F89frGxG1hPs6uwCG3S2unOGkr%2Botoc39GZ9dqNOrcoZoZnzTKK4b5voZwlYtj5mUtyYA5IyIF39tFeLW%2B63MD5AajEfvSecScxNqKwLgnKYCoLmGxYFrcfSkaLrTTNbkrBIL9s8dRydH2DgpfbocioOQzscbwfZ7CZ%2F8kMi8WmIVXKMqD1i3Jy5BwgHTRKlKpPQ4UwQ8L%2F4LSVNk55dijyYjHMud5veVCIHBtRu70qjM5aFgeOHo2m%2FsJV2Giboo9F5xfEIyUtUtQq73IpI3I6ZQ7y1pdt%2Bjqzsjg5iyCdduayyVTf1mPMMvg7bwGOqUBzVK78rsXYN1e7J4vTaLXClpze0fv1Z3CUCJx07fIyMoKiuUm81NId%2FD022mMjHUCVWPx63b5gT%2BWNMdPWEt2UeY0BDRszc78ubohEkJglVGJUYUUk2APeM5zy3hu%2BM%2BUQZfn5rdPuhyWQo%2FHpjsS8fqgwziqAtr4T5Yvi6k%2FB8gF0xMr44TsYM5M8yPtegPS1sk60jf4ctU8RWqrBTqafS8eVYTw&X-Amz-Signature=6811f2e63aca4b86b770c77c649046cebb8f42622184cf97589258c75a552bcb&X-Amz-SignedHeaders=host&x-id=GetObject)


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

