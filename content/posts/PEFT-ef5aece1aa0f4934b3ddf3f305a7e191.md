---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466TL7GJTP5%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250222T082711Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIAfWBegtDa5K9h7tmVj\
  f9W45opEQ%2F9Q%2BshCNQ1NDTfX7AiEAuPSOopAE59QsMTYUYPor0rYh79RvryGlQkgiWi7f8Lwq\
  iAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDFu9esKhwRZe8aZ\
  tAircA6Z0WTLXTQUY1y8Ss85IP%2FA44rFkRQL0HDBcNlnWjvhrYW573xQIEHy0pvDD5xUHj5bgN1\
  fa1m6FBxZCqBgE0r2K1XWoT8VilhRbts3nwgATGzW%2Bv%2B4Wkdq0meRp66qJkNFiGR%2BIdQTDP\
  GLs%2BrHzbCmgS%2Bp56zLLjZ%2FZ30qMD4JPswxCAJ1m%2B7gZrAlbUAdclQ9bVOTH%2FCiFiRsU\
  rLDfhjYknEYBVVou1KQmjwRF%2Bdclt2EaNjz6%2FTSDG7mnKtcZjlpnyDs3q032UnEagAoyLCMxn\
  xMDcXjhv48Ta5W%2BYzR%2Btg4e4IW52FiaZhjmIGv1mXj5wuU0X%2BfCqmWRlup4kjI2%2BpyBcQ\
  ZGQg1CHhNHGvM2Yzg97QFCHwGfMna2iIaSrjl83cXlnET4KE5LTl7EgVp60J2yu1WgcrLOkBq9ARf\
  sVqfNjhKKlC7UzVenZI0d6g0yXeq8uswxs%2FncwrcK%2Fzsj%2BCXpzE%2FazB7WMlqmwedQJ5WX\
  XBmiAgZyJj1AdgwNIq98WT%2FCE%2BVj9G6V8KEajX112BQWVjhzxEaSeHxNUJvtwnO7pgNpklsyk\
  PYLBxF8CAwP6QRC0GGzvWljUEaT1dDWJ8A1NSGiNRErhHkbmdydlcO8dnuk5JLHdSngMJDI5b0GOq\
  UBI1XBC%2BJ4tQyVWmHAXgY04lF3z1BiWqa9llnslek5rXqPxRFu4wtpp72%2FEGIxZAKslnwG%2F\
  6W9VHndOaCzaNOR06tCTsLUbS48Dz%2BinNHHdZXhHZ6b8MOfKoc%2B54yVmB4d8osEzMP8JOKDFR\
  kmIiSvWPNHIxEbWr7piqKk1jknY3WdaTikE6CheCsl3r3QK8dIeT%2BV4OglU7DSl2DhCUFCofZdA\
  zSI&X-Amz-Signature=d6b70b52722d8e4ab7a9531d9dfb3fc045ee5b109a79ca1704451fe6a\
  5a98052&X-Amz-SignedHeaders=host&x-id=GetObject"
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
        redential=ASIAZI2LB4662XL6VUEB%2F20250222%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250222T082543Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEY\
        CIQDks%2F%2FWF%2FneTS%2BSgNtW3DP1r6xnYZHKQYpvGoFKhfx2rQIhAKt6xFsLmI%2B9\
        VmmbUcqHmunfqENXV1S%2F7JE3HWYovIkyKogECOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F\
        wEQABoMNjM3NDIzMTgzODA1IgwM9bMQJv%2Bl%2BRxI16sq3APzolFTIuGUK3gdkgXHyLM6\
        zbVMyNceGZ4gqjEySnireGB68u%2FvigT2ksNL1B3l6iSL%2BUVl667xtqC1cSkb2vK%2FD\
        HdSNjjgm%2FCSPfEapMC0P2yF32ZbM0OElsZUYTc7G6cieB4hXTzCQb2hfTglpLqFHI4rP0\
        %2Bs1Ns15aXUW1iyfVDyOeDSmbUXrEmUUSsxlQM2iO%2FXo%2BB4vczGxV5c3oelZL5QnM4\
        dNzR%2FGl1RW3hPYQniTxdmUsORiN38LIL%2FdS3s1YMgGwBIdgkQ0HJxCIlxl%2BLrlVks\
        If4tlIXovZMlVuRP8XEq8A9jOUG7QRvX2Rs1LuYoPVkZj2uAxCez8o4JEqeDxWjHZjMnPE5\
        Ti5KS7CZoOBKS2hImBySH9nMujtC2lHyms88imdp9aaQxtanXs3x5eQO2KbCzsOcoqH8hCO\
        I8bLTueLVeOMZPS6j21s4K%2BLleNfS055JCQKSxWCU6trHYOQvdtZCFc7UDiGEQey6CuBH\
        xX9SCk4SC1AI6S2TUTxYea25pa6trkajXYaldpfy1lEXR%2BoHnqoKNIgrB7o9p2ZIubS%2\
        BOmva34M5vCIxZwIOaZGmSVGSMYYH8rBqlBqvDHPO%2FCAAst85iRr29olv3CTZfzuny5cN\
        ySjDOx%2BW9BjqkARC3cBQEMfcXnfxyWBwB0hVf9mhuk97%2FuIBce6Vlu%2FkMtXl6ZE01\
        67FvfPx2Ws5hgKhtF0VhaaT4fBVLN4xnu%2BHGbRWYsaq9NUAezxAJ8yYz04BFGf%2B2tSe\
        MLVh%2B%2Bs5dHYuxLIczoZ%2BnfqKhNbwJmqTcxr%2BtvX98bDWTUHMPcC%2BxnBr6D33e\
        3ixcI5BVpl32TO29AZAGgjQMheFqP25Z1%2F%2BmPFRT&X-Amz-Signature=8aa6c58692\
        62f6f9deb26c941646bba2f7d04fbe8d2fde92fac180e73a1b7390&X-Amz-SignedHead\
        ers=host&x-id=GetObject"
      expiry_time: "2025-02-22T09:25:43.930Z"
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
UPDATE_TIME: "2025-02-22T08:27:17.364Z"
EXPIRY_TIME: "2025-02-22T09:27:06.078Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=80a099b7ba3bb09105ead3c366347e6b6a11979f0e156d73b45e36995ebfcafe&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=c770e7fadbaed75e1b7f6506d965cd54259d51400ce92e6a99a33e263d1579e4&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=3b0314b9aecf01d265a1d426c94a7ef2142430990a0884b3280e15a856d1c242&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=6e6befb798cb9b6adaeb6ca8eb8b6b4e919332eb142e4095458d90f5ffbb67a3&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=d27ef22f522ab3c5c1426423bf4cfa556e693b0da777fe434f5e14b544bffdfa&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4667OMB6IYS%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082710Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCICzAmJjHCFyVJuAHKvVYZgputiGfr7N16b20M2lpYke1AiAvI3SWK9k3kct7At5OWPpI3W3rUzC6SYE2IVgRL9R17CqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMK9B568XPkZmQmWoqKtwDeXp%2FhVonoB1yas%2BIeRRpchtGC3uFLE8oj7Q1%2Fxfx7oTJCKRL2Oinwd4Etlnsx%2Fgl4nOqAzq41mu0Vb9DBMWb8GvIzaCuRkG8gN1mxUUN2ZEPM93Km5VAW3NH4PbcWmMo8NYvyBa2Fc5l7ClJydqfyQnDiua54VRdzSF%2FXdrRoLgDusgJVvre5MbQiCPj7whKDEdLRk8rD2oskNeqNs2Hjl2kFMHX6tSH4pquIzDHAZUStGWCI7nrrKRQ9dl3uzFXTVSkEvRSrYSYaJA17fvSk%2FCZjdyQ00NK7dNN8L8QKBykE28uGvmlgVJmq08uUq%2BkI6gFli64itWNooYp8OKHkoDvJ1yFnzTS%2FNACAQBVeQnrbPSBZyUxIvkwaUjF46uxQRqOjJRr46iLBuDFgRiqAlUj6koBKxTdf2b5rL4HmQEUbXiVFAmjjVyVIMicBMqJlrDHNqlR7GCpjI%2B8v0figJg035cOaqy2gfp%2FtYmn7JaBhdCI2MFfANK3sRx5JqwsWSv3r75e4qOml8YWrd7MGX9EeYPlvBrmRZ0rWvLppoUp8EaBQdoJHjHZvhM3%2Bt8GQHeTqt6XTU0u3lj%2BU8aUwDyzzE9CMv8Uyr7sR2tbLO2nK%2FAGD20R3pqjZ3Aw7sflvQY6pgHezDhvKVYud12LmCeVT2t7SR3N8t6gHaesj6WE40GAYw56%2BaUcKojKEZu%2FUT4QDxEf0HrYqts70z4hDhI8GH7zJUc6fp9i%2BJkBfS9DGoAAG8VaMaOxF8mfbdV31LlwzeFTINylg59k6OfnfxuhgZG%2BiGz65gD3PsBmeRRrmqHzqZTZfJW%2Fi5J4jQhZf%2BFqzvJLDot2V5UwqHd07y8V8D0MnQMooaj9&X-Amz-Signature=068e7e69c557f7a8058d16dcb18ffed0c003e84580494e851a9f616c78aa9dca&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663JA265KU%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082711Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJHMEUCIDfvXC0Lc0DokfxyEYx5wG9E6Pd7cdEp174Iu1UrpeCDAiEAn%2FmDxaR2UOv6f5tCNwAy0T3Gc24dOebGLVxvFYM9uNoqiAQI5%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDIYt4mkTM1XHt5qD9ircA1T1CmKO7WJDupB2NCxY2Gq7bPy%2F1qhbcNMH7O9xfCBwBe2cKa619lRr8ug9LLJ3oHVhxCFbNO3JE%2BK%2B7f%2FwcHmT0JCauDklHCYVeaDmpphB5orRql%2BeQae2fRao%2F7%2FSP2Fn%2BKgaReP2ZmXzkRUDgqTwlb8VYRquFSDrUN8zKFVzf1az3FKmMibFC4aUAETiLNRjETog8noHFOT2NURPU3yw3iKj%2F3cqos3q00R5c%2FZmxl8kf8aYKu4aSJfN%2BfGWAvN19vyx%2BJ7jlaAwXPwaeu0I36B0HF0dvQEuI5cFnMQQH58V0%2F5y5JUWkLKna%2FYqezvc%2Bec%2BKKhTffGZFzBogfGbYqFeQN1q7clp8iiBEG6K7kk4KckGKB3xPHUNdykEDoKFoy5FkhRflRDu0r%2Bgw%2F4JIB5JyGduvsoBEO3STWzHCc9NlYjHaP5oplP8SPfgK%2BKfWLIx2peeeVhAh7SDwK8Y5W3rK7uJoH7Pu541XCvQQ6hLTHdsye3VFsR7kd7i6mvpAjAWn2NbbGb3lNyjVpu2x7E28iQUEbh%2FW9AaxJxDPDWJFEbWRWXUdoiFs2RLf1j5ulWh%2FJ8Ts10o013F%2FPsTYhPreaDbN6UKFZxSXi5nBBXg360wOo1J9xUcMOzH5b0GOqUBRTCOuHRycAKR4F93Z876v9T352fztvo6nWk2oCI7957Y1YjMkTU45Dh7C%2B%2BuPHW7ngQNQmsMybY5aYiqSwEgP5Ytm6FpysykA%2BBAehp8aIwXUfMBiso%2FE1P4hIl8fxroC%2FsyVgRQCKdKbmHfj5Ag46r7r0GnnP0IGPwWbP97kuTZIf13H07NjAdcgoMsv4hFKuySCvEHvdJzARKtyeVORa0d7tz8&X-Amz-Signature=db20a8617be011636fc64c8a81ad96d509aab761122dc48847dce76ca690a5d8&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=0848da6efb01fe1997d42f64baa4a77bcb7d70e2d7d38b5db3584b9cca8272f8&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=727a989bff8b2a01a0c08f4d0eda9a0ca252489f6c6ff986e5c63abf680bc934&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662PBQBKDM%2F20250222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250222T082706Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEL7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJGMEQCIFlifu81SyNdFWT0K9SGuAQQ8CZeYPTe1kjXXDyxLLyfAiBjRzp1Wkaa%2FyrRN0xfc5NxQzj5Nx9ETvSs18Ht%2BlsFpSqIBAjn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIM%2Baz3qYFJgX0RhYElKtwDpCIUZJ15lNPFv9NFZ1W4TJG%2FoMSp9yQKvGSsR0Z50DZD5xdfGsrMwLO62F4H9U3PzMsT3P4AG8Xz69psXqLgLEwMh2BwyNcVBYL22izcp81rv7eivNNS6URiZAhMGAcDMaBsNayxOB2eobSDgL3F%2BZvisXUCrIq39VKRCeKN8C176b5wY51%2BHPJ4wQoI2ZoRr2K65ghMkQcscn9%2FVPCuH5F6U8wKWFhC%2FYIekpXSYayzcIDzys%2BZcTXJISGfEs6Kh0HASY9jWPeUzqJUJwEBFsrc1CUe4iGWIhC92doRm3Alm6ovP3M%2BW2Gao6QVGHL32PVcmiOeSx9dTGWWZylBxDorWXwuv1KmKTLSg%2FKyJ1soeFuRTbKzjYbnvslmJamR0NP9Nd4wPC9NTHyy3dSi%2F2YtMvp2m4XbF2HQnYETYA3H%2FpP%2FVBzKFwi0jJIl4ftCcpFv8r%2FDHElBYNcBjXXUKA8TfWtUzvHGmpdCn7Ip57NJYYdLdKALfGXVY5Bb1af0JzaXIcSwBNfSitVdiYOKPsAKHtzTyPWriNb4bnh%2FgAwZRQ6mrvCNJ6QEi4R%2FKLGTVJmeOlNMhf%2B8PSJ1IwWwZ3uHFqaCP%2B73dr1RQqDCg37VRyNycPnfKMztAJMwsMflvQY6pgE4xjidS0Yd4yB%2F4b2YP2z9k%2B94KGf3bwsi5jYlUNcIh5VrAR%2FtbO%2FeScN5hFiHMG54KpIslZLvSB6Zk%2FewkPXqJrzPOPwcsaDAnSnil0BeHfcvs8PEYaGky3eCGgTPi1B9Bb5%2FHZDr3v%2FYa7657nBRErz8sy2q4IC3h26JbOx9m6tduC4bYIjXlmO2pGgd9EyUhNVq1dZHIdblSoLWnplcAnPPdzlk&X-Amz-Signature=554fcf01e7c006b021db8ed3d947c7db98989241d1e44c394ee2cdc551af9b8e&X-Amz-SignedHeaders=host&x-id=GetObject)


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

