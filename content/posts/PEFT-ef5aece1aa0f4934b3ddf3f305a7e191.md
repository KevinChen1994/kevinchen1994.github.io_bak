---
title: "PEFT"
date: "2023-08-25T08:02:00.000Z"
lastmod: "2023-08-25T08:32:00.000Z"
draft: false
featuredImage: "https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-8\
  2ce-4f96-ae1a-879bd6c9f3a6/71dec1e8-795b-474a-bbfc-a4e4bad7d5b2/PEFT.webp?X-A\
  mz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Cre\
  dential=ASIAZI2LB466ZKEAXSFU%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz\
  -Date=20250219T052307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2\
  VjEHUaCXVzLXdlc3QtMiJHMEUCIQCDDiOdT4UTPx%2BB8qI%2BsgtOSjUkK4gZ9Ys2t8Mqb3%2FWi\
  gIgHqsaK6a4oOtw8c6uhwKM1MD6dZcpMqA6rGFF89mXEeUqiAQInv%2F%2F%2F%2F%2F%2F%2F%2F\
  %2F%2FARAAGgw2Mzc0MjMxODM4MDUiDG9TAq9Z5lzubx0mMSrcA%2B02KzMslPBP4KK8s6z1TCzqs\
  SjwAo82%2Bi3%2FwSVpSxgky2XQmcU45fxGnR0UvaOhLBVjbl5hpw%2Buj6vO8ihVhTvZGyCtuDMn\
  %2BrRcd2FHKyldi%2FN1HEC%2BwcLQcOqkbuE4iGmFN4nlDXcaQqmkYVp%2BolJ%2F074WNGUE9%2\
  Ba5ZHIXVF5fsCDc3CeuTBMqES11vodXfy5L1zVDK0ROzL0qlLolbmyICsHwNtwELJ7cpteB5kO5lm\
  P3o2R7IJf77HilE1nD0ZPHJLEG8D41QIZj3aRan4lKdJ2l9SJKIN%2BOyGeIVcYxt6iLe3bMBuzV1\
  VZCda7e7mezxvsd7NNWdTtUXwSaK7nqRP3jzbWJYFhYuuqVtOR1fRRNICI5WC2UqKQ%2FnCtfrLLB\
  EKAqIBgLU946xNyVmmjbICKxb%2BwjKQnoY3aCHgpgIWWBomAMsevhAbldSxdzTt5ivK6tLA3t6ks\
  7ovwBTdYAUWBSlcm6NHoo2RpZcAz5j%2FJz6FtpZNxt%2B0Ni2f0cP4Fe%2FNjnhASAp7ywIUVCD3\
  nlx2xV3tBd2SNgE4OkgLHIAKBZ5xyK2IfbyBhssdWfmwwuvM6TG5SFeB54bNwHsS6HVgsv%2FBWis\
  IHL%2BiVzg5ksL1%2BlG3mTODMYKR33MIvF1b0GOqUBQKWFE5CqUbAI%2BT5LGY8%2Fu78E%2BN12\
  VTGW1PNxZHaB4maZejlvzKZH62%2F3B42yN38YvDhpqtNQlAbmHwcl1cOCa%2FB5Qz9ydxWJ6TNBo\
  FXp4HjmNi2jkJ3%2F5A6T4YYt3E%2BNclCbwgIdCjDT5fuqJxkFIqriLMrKdutEc8sDxmAfaNHhyb\
  8txmygdHStB6c4XQpQ8nMhnGLwE4mnsUTA0rELQA9kry8T&X-Amz-Signature=ba1ccde3ff4e8f\
  3871d32ba97112baa18c1f486aa0320d938d7df3bc7b2cf99a&X-Amz-SignedHeaders=host&x\
  -id=GetObject"
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
        redential=ASIAZI2LB466ZXJPK254%2F20250219%2Fus-west-2%2Fs3%2Faws4_reque\
        st&X-Amz-Date=20250219T052159Z&X-Amz-Expires=3600&X-Amz-Security-Token=\
        IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJHMEUCIQCPYqfLNdrisPO8nHTQi3%2BUaqBST\
        Wo%2Bz9Cyz7ysYEpNowIgJBMfVKkd2%2FH1016Lln571oXBr6MW2OAdyOAk5qmflDYqiAQI\
        nv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDD9Ymn0JN8cCCxA\
        uUircA9dVVuv1kt7yDR2ZhAnYtDsQdaaBsMH%2BcRV8CdBDrFI%2FToExtIyJwFq0fOTxmu\
        ChOeg%2By9OhLBSY6MsyI2WkIwMeGku1okf568Pndoj4tE029hhZrUDSSBvnu1Oa%2FsSob\
        nVYPAsPgGtiQas%2BJzPp3zM0IzS75tdso0lgRgXkgIUV2gvR8a9I6iBBAwqIZX7ui5AeKS\
        8d%2FGwFnqbEk024i1SNdRv0UwvlFmegdHXUMLQ%2Fb%2FZ58ZZF1EDJaZkXYq5gnQ16M88\
        8uk62QmEHOgdf9Bu912W53n9xx29EgIb9DE0YUwlaBbaeRhFnFSTX01L5fv%2Fj3g%2BKPf\
        x%2Fyk8Iq7N%2FNJwNASN4PtJmHn%2BmikvxVfBuflZlAsnfTdL%2B5zTyAVMoboSAmhKqj\
        O3nD0SHli2AqIxAKRXZgCwH4EsDU8%2F0waydwpcWHkRdHPctEILpV3xTVep6kiHsfdICv0\
        ClOEGMlhU3jorpXbHh%2BR97%2Bj6XGE1dYwfkp7MW75GaLo2EKqOPEWO%2FKyANV9wIB73\
        WMN%2F5ANMtIIGUBfqeCGTM3QEgH%2FkvlJsMmmxxfDcUby7J1KQ33n7bn84lPT1RVJXQMa\
        R9oCC4HHJ7eqf9n4wXHoI9dC%2FH%2FfWOE1FDDoaTVEr1MLHF1b0GOqUBNEoBxx2QsBYt2\
        vFxpW0KUtTG2kQZfBLfL1TPznKCmK3AHGNpJMOK%2FgmO8Abx%2FvVU3WLiASA50g4xffNF\
        qLUPhdBz7kAEB2YA%2BcNu9XU2oTI1pjXvivrxD5E1GFKxoPSiZK%2B37WddbyKcl4gaRM5\
        IaJHDGU%2Be4QG8No29eyZGU35ifvUaaWOe1voT%2Bo3fBxZqWYRcDpqOhCsWEB4GZf8fX%\
        2Be3VZW6&X-Amz-Signature=968d218946304c27620b2832cb7ffe6c429bf94f6d6415\
        27c782b08896ba9c47&X-Amz-SignedHeaders=host&x-id=GetObject"
      expiry_time: "2025-02-19T06:21:59.131Z"
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
UPDATE_TIME: "2025-02-19T05:23:16.552Z"
EXPIRY_TIME: "2025-02-19T06:23:05.819Z"

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


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/75e2cf07-b2cd-4739-9ef9-c77d8bbf4c32/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=d98b0a88d30e9d148f516007153de48c803c66da469c4b52e5e7fa041ef9b01b&X-Amz-SignedHeaders=host&x-id=GetObject)


prefix tuning可以应用在decoder-only的模型上，也可以应用在encoder-decoder模型上，但主要应用的任务是NLG任务。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/5703ecb9-a68b-44a3-84a0-745713812d06/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=00c3b14f4a9ea3be33af425c0f5fb4fa60e12befa2173d4d312afdc74c2c1071&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning （2021.03）**


_论文题目：GPT Understands, Too_


_论文源码：_[_https://github.com/THUDM/P-tuning_](https://github.com/THUDM/P-tuning)


_论文地址：_[_https://arxiv.org/pdf/2103.10385.pdf_](https://arxiv.org/pdf/2103.10385.pdf)


背景：人工构建prompt效率低，效果差，想通过自动化的构建模板而不调整模型参数。


构建连续可微的虚拟token（与prefix-tuning类似），该方法将prompt转换为可以学习的embedding，但**仅限于输入层**，并没有像prefix-tuning一样在每一层Transformer都添加。


另外还通过使用MLP+LSTM的方法对prompt embedding进行处理，加速训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/ec199841-2c12-4b48-bfb2-e8a31b4720b3/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=329ad73a56bdc26166ff18d8e140cc3c33718f208632d56ba6d2100b825d6d9d&X-Amz-SignedHeaders=host&x-id=GetObject)


### **Prompt Tuning (2021.09)**


_论文地址：https://arxiv.org/pdf/2104.08691.pdf_


_论文题目：The Power of Scale for Parameter-Efficient Prompt Tuning_


_论文源码：https://github.com/google-research/prompt-tuning_


背景：有人提出了自动化在离散的空间中自动搜索prompt的技术，这种方法虽然优于人工设定的prompt，但是跟在连续空间搜索prompt仍有差距。


固定整个模型参数，对于不同的任务，设定不同的前缀，这些前缀token是可以更新参数的，将不同的任务数据同时输入到模型中进行训练，可以理解prompt tuning是prefix tuning的简化版本。


实验表明，随着模型参数的增加，prompt tuning的效果越来越好，但在小模型上效果不明显。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/2d0c434e-f749-493d-815d-c59644b92411/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=6ed82c6a225010705805d05332873073cbd7bc4d7c6435a7a8854233c52c20bf&X-Amz-SignedHeaders=host&x-id=GetObject)


### **P-tuning-v2 (2022.03)**


_论文题目：P-Tuning v2: Prompt Tuning Can Be Comparable to Finetuning Universally Across Scales and Tasks_


_论文源码：_[_https://github.com/THUDM/P-tuning-v2_](https://github.com/THUDM/P-tuning-v2)


_论文地址：_[_https://arxiv.org/pdf/2110.07602.pdf_](https://arxiv.org/pdf/2110.07602.pdf)


背景：为了解决P-tuning和prompt tuning在小模型、跨类任务上效果不佳的问题，作者提出了P-tuning-v2


相较于P-tuning v1，P-tuning v2将连续提示应用于预训练的每一层，而不仅仅是输入层。P-tuning v2与prefix tuning类似，不同的是prefix tuning应用于NLG任务，而P-tuning v2应用于NLU任务。


通过增加prompt可调参数量（from 0.01% to 1%~3%），P-tuning v2提高了训练的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/d66eea32-ca00-40f8-a68f-44855e3ce705/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=e2eeb2c2bc34843a8ffa7545f6338ccefdcb5937e8a985d83c9fcfc9f1f5a09b&X-Amz-SignedHeaders=host&x-id=GetObject)


## LoRA系列


### LoRA（2021.11）


论文题目：LoRA: Low-Rank Adaptation of Large Language Models


论文源码：[https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2106.09685.pdf)


背景：当前PEFT方法中，有增加模型深度导致增加了模型推理时间的，例如Adapter，有训练Prompt，同时减少了模型可用输入的，同时Prompt训练起来也比较难，例如Prompt tuning、Prefix tuning、P-tuning，这些方法的效果都差于full-finetuning。有研究者对语言模型的参数进行研究发现，语言模型虽然参数众多，但是起到作用的还是其中低秩的本质维度（Low instrisic dimension）。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/06c54517-a664-4e66-8d14-817354da433f/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665UM6YVM5%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJHMEUCIH3%2FkP50WL6OBux5wmGzn5BS8GA88vlmdxD70F4vFjjVAiEAvRyhNXxUdfsAVz2Y045dopYIEmQUwvXc%2F01KdNsDpnUqiAQInv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw2Mzc0MjMxODM4MDUiDADYMYjeA8KmMbgseSrcA1MULaZKuO1cg0cfqQPvv5oFZc5PT1%2FhTfu39CCfXhCz%2F4X8zx51ahW85AxJD1W6AkUxBv7uwu2egxsX7qI4gd4k4gQSXyOIRQJyj93FLMfNKM1XVV7A5%2BTUYjYf62VOweGesLuEhXCyyuWYXTu6v1ww3RofQQ2If488ArlS9LxOd0rWGF1yFgUgZ8LDprEyvZjmcFrzaeR4G45NfdJBaspYcqu2PSKciOdY8WDQoKJ3BgN%2FBBj19PXEUDghD3ov73cGxXPyb6dIp1M4eD3fZ67h1SKDaInr9SpjUKnxAwhxCmRcDSh8EvESNef8MV7ZI5568RdhN3uW8RqeWh8cvu74vsUq4WJau8be5ZRqkAxtJcPvY3R6tqJnfzrfc2Ta2iLOUXL%2Fqmsz08EWfHMu5LLCizkDGf%2FgyUjC8lzKj7Yf2MTbbY6SWWVnG6jlenFKB1kRfMpOMJUPAE6GbWQmwLL4F%2BaePBisXmnsRZ0HNBD3v9Es%2BQNOY%2BdOj3fFbqw6%2B4EkotMK7O2nHTnNEg%2BMys8cnoNmCe7G%2Fl31ry1fDBOqTHm1h1SYkDXi%2BGL7W6FqgtiqiL61TFe7Y1BK%2BvJ63dJpikPH6RkFjLRdlLw07BRi9eKfXoevVVZ0zx%2F8MPbE1b0GOqUBpH0RDMCeIRa9yt9YSHMUaNPhPwo9GonKGZaePjnZRx4bSgq2j0f3VHqhZbKLHQjwZiBZyHARUUOTueLr7outmizNeEKbwekEYjs9GIHREqPYHxKppunchp7VDvX9jQHrSbmQnMQrx1fXX%2FmVN1D4OfUAPwL3Krk%2BPP1YRgf3ty%2FO6Y5MwA28jv5KIQRvSA0QIlbq%2FDdGqi3Ggae44wyrbu%2FzVVzC&X-Amz-Signature=094eeb9ad5ea6f29ba052446bd81b147fb3faf140d26a4114613f39cd22e9c10&X-Amz-SignedHeaders=host&x-id=GetObject)

Lora核心思想就是通过低秩分解来模拟参数的改变量，从而以极小的参数量来实现大模型的间接训练，在涉及到矩阵相乘的模块，在原始的PLM旁边增加一个新的通路，通过前后两个矩阵A,B相乘，第一个矩阵A负责降维，第二个矩阵B负责升维，中间层维度为r，从而来模拟所谓的本征秩（intrinsic rank）。

<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi mathvariant="normal">△</mi><msub><mi>W</mi><mi>x</mi></msub><mo>=</mo><msub><mi>W</mi><mn>0</mn></msub><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi></mrow><annotation encoding="application/x-tex">h=W_0x+ \triangle W_x=W_0x+BAx</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.8889em;vertical-align:-0.1944em;"></span><span class="mord">△</span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">x</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span></span></span></span>




在训练的时候，LoRA一般只对每层的self-attention进行微调，即对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">W_k</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3361em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03148em;">k</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>o</mi></msub></mrow><annotation encoding="application/x-tex">W_o</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight">o</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>四个映射层进行微调，实验表明同时调整这四个映射层效果是最好的。在推理时，只需要将训练完成的矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>B</mi><mi>A</mi></mrow><annotation encoding="application/x-tex">BA</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span></span></span></span>乘积加到原始矩阵<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>W</mi></mrow><annotation encoding="application/x-tex">W</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span></span></span></span>即可，即<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>h</mi><mo>=</mo><mi>W</mi><mi>x</mi><mo>+</mo><mi>B</mi><mi>A</mi><mi>x</mi><mo>=</mo><mo stretchy="false">(</mo><mi>W</mi><mo>+</mo><mi>B</mi><mi>A</mi><mo stretchy="false">)</mo><mi>x</mi></mrow><annotation encoding="application/x-tex">h=Wx+BAx=(W+BA)x</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.6944em;"></span><span class="mord mathnormal">h</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.7667em;vertical-align:-0.0833em;"></span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6833em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mord mathnormal">x</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">+</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mord mathnormal" style="margin-right:0.05017em;">B</span><span class="mord mathnormal">A</span><span class="mclose">)</span><span class="mord mathnormal">x</span></span></span></span>，不会增加额外的计算资源和推理时间。

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/81337d4f-7c6a-4b78-abed-f607a526554e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4663YDEGUW2%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052307Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJIMEYCIQCx8F0AOURu0mFeyXRMcBK3QmbWGh9PvwdrDs0Hjv2VxQIhAI%2FPaWCvj%2BWdTmGatNQecMqV70SZm%2BarK5zFnOhklkemKogECJ7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQABoMNjM3NDIzMTgzODA1IgykHsUpFdhBch5FH0Uq3AOwc4BnSTe5EjL4E6GnAVooC3ZwP7Nj2Btc7je8OVlgYBMMoTCpttJibh0u45C6R49pD1yukBZUtHtqM%2B5rMpGAt6jU9atXO5ApsQ7yQRhJ3%2BAlrZfXOt5SGf%2FDz2SKUkGtBK67QPnqU7Lal2GYLnLxcYwMIr5mokz0RhgetTb38BcnHEjvJ2teltLQjj2kn3urWx%2Bvef73fFiO8fqKaGbY0v8wK1G3sSLT%2BElesYmvDQKBseRwqMbA4%2BAJFe2Q9W33hUkJrmgOz0fBDxM3LXTeRg3Mu4ivdHvx5Obvu4pTd8cDMM5EV1usVjtX0ffZh7tL4Bh%2FKozTyWyf1%2Fxnlg%2BYuTuI4RU3CiTmOnrREDQMbq7MmkowZl4F59zcaWT4wqk%2BRnciNiAU6BioklkNIkySNdIujWo1WcU8wH3cZBWwNdENt%2Bvi44nk1Fa8JbfXFHeSpuJ4i2ZEGptpxxkfdRFGx%2BDsoy%2FmBYEYJi4VomTvomS9UMi8SB7ACmDv34dB40Ma4%2B%2FlGHIgtvrF0otTf40uS5NRacAS2KEhIgeuh8mum6qByDWlPWKJiogjc%2Fj8IwOJnc3UIJbBTZjpfr3MN2znZXlJh1Bb%2FL18ucwlrg3cYVuqdJqFLsxErlD3szDRxNW9BjqkASIUn%2BtY8crfMQ1hIwXlhzXW%2B5YPlxIsm4vbPiGqYJSU9wOwzexJShFbtrJIkL9N00YwzKt%2BCUYEcg7FTqqwtKCxQUPM6%2F%2BIOjnvotJLr2HErm8DR384HESFUFTK%2BVAqTQ6ZKj1eo59anQsH4JSVMjgR0kpBueKWjSLrkBUB%2B4c1YxlAzw1lkF7gn8lAnQDRDoZ2Xv6Z%2BlxUI3N4c5ELRasIXxDQ&X-Amz-Signature=da60563774ce72085c3c838a54535aeaa6e18fb3834e48efea3e79914ce40a79&X-Amz-SignedHeaders=host&x-id=GetObject)


对于LoRA的秩取多大，论文中进行了实验，从实验结果来看，在秩极低（r=1）的情况下，对<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>q</mi></msub></mrow><annotation encoding="application/x-tex">W_q</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.9694em;vertical-align:-0.2861em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">q</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.2861em;"><span></span></span></span></span></span></span></span></span></span>、<span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><msub><mi>W</mi><mi>v</mi></msub></mrow><annotation encoding="application/x-tex">W_v</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height:0.8333em;vertical-align:-0.15em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.13889em;">W</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.1514em;"><span style="top:-2.55em;margin-left:-0.1389em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right:0.03588em;">v</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span></span></span></span>微调就能获得与高秩相当的性能。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/83f05cbb-bdd8-464f-a675-7282a4c1eb68/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=09ce094d15e27f7f3934ae1180b57b15d18d3f749a19f5c1a6b9a60379f248c5&X-Amz-SignedHeaders=host&x-id=GetObject)


### AdaLoRA（2023.03）


论文题目：Adaptive Budget Allocation for Parameter-Efficient Fine-Tuning


论文源码：[https://github.com/QingruZhang/AdaLoRA](https://github.com/QingruZhang/AdaLoRA)


论文地址：[https://arxiv.org/pdf/2106.09685.pdf](https://arxiv.org/pdf/2303.10512.pdf)


背景：LoRA需要预先指定每个增量矩阵的本征秩 r 相同，在微调预训练模型时，LoRA均匀地分配增量更新的预算到所有预训练权重矩阵上，并忽视了不同权重参数的重要性差异。


所以AdaLoRA提出了动态调整增量矩阵，对于重要的增量矩阵分配比较大的r，对于不重要的增量矩阵分配比较小的r，防止过拟合，并且节省计算资源。


**以奇异值分解的形式对增量更新进行参数化，并根据重要性指标裁剪掉不重要的奇异值，同时保留奇异向量**。由于对一个大矩阵进行精确SVD分解的计算消耗非常大，这种方法通过减少它们的参数预算来加速计算，同时，保留未来恢复的可能性并稳定训练。


![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/b9367bdb-92b5-4683-8bbb-8f94b166a3a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=f83505ce39c70cbc357a2536c406710a4b8d811a3bec01db637d62e3b2de97d9&X-Amz-SignedHeaders=host&x-id=GetObject)


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

![](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7dbc101-82ce-4f96-ae1a-879bd6c9f3a6/062a3d3e-c3c4-4994-b310-c0c6537a4844/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4662DI77AD7%2F20250219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20250219T052306Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHUaCXVzLXdlc3QtMiJGMEQCIE2mH7cah9frQboe2XGGd%2BqFfTvcHpcctvfcjm21%2BcA8AiBq4BE0IkcXa5rUQvL3WHV9ftRDNMWuJMq1fHC%2BjIClTyqIBAie%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDYzNzQyMzE4MzgwNSIMV9eU2dWciu2kus0xKtwDgTcTHy1PzWV5zk7n92%2FyyLU3v2NrEW%2Ffbd6Ztzh%2F%2FWmS1hDX0vRuoYrcagYmjx31sEUZMjTirQpVbD7PC4O1IJb6xvGkhK16Cx9sBCVfOshGWU0k47pC6jzGfmoLAFg%2FDoUVt5irg9XKe8yMYb2J9BNRa9BOUlzBgb1GyFYTMpP7UZZgzhmMHEqitVwhLf5QluWIE9X7yz62xj7Bo8mXLRd2ptvHcf85BQqhX3X2x7yr%2BSdVWxyijXVkgnIvftBRykf4fa%2BWjO3BfOoeU93BRLKoKTcEts0TJ221aJ7chL4lvp04tQ0BxD%2FI%2FAXliiy8tzHKW2LH9YcKXe9Yl44k54Qh%2FxDl5nWfn7TlyX6L9uy%2F2cBALI%2F2ST19%2FEyprY1ZmfOzazmNrCLfdNjM6azUBRL5Z34vWUoIbNnmebComLQ6ktBuQea7%2F6ExveIFSDy5yJFTdQHqS7kpOzaz6NDJLzWEywWPkMsXHAh0aWqbaPqsU7iaz2Kb7svmZd3yteqsJyVYhQ%2FPmoXj0HFD%2BD5F7Ejc%2B4H4XBYybeGMYVisEGj4h3LWsK2Gi%2FvCZi%2FA3dpGRjscL%2BNjhDOd7TR%2Bsq38Mtey1Sm%2BD6ngzUt3iU6bcbYa4F3ZjPh2BhgaGg4wrMXVvQY6pgH70%2FMyD1p%2BgQya8SXCnSzmeNYhKupksvS2A4y7umw%2FEhnb24GEMbyYHcdeK8S9Ng6bqD%2FQ%2FQ0Q28GlD1Q3%2FiY%2F1BZQBAbhy2BE%2FdpcdjRFqAKYEqdhx0SS1j8reMcWS%2BHBWBhWAQtl80ahcBU0cQHDXFDDKIqri9onc3XMjbBpS3Veli7VFl2HFiqaz7Ovawcw7XPkm4OowSq%2FBUdDk%2FC3fMJEZI3z&X-Amz-Signature=ae42b21b8e4f28a58c0a992d4e39c5a20326e9f7cd73491c6ddf1bc8e39a5c5b&X-Amz-SignedHeaders=host&x-id=GetObject)


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

