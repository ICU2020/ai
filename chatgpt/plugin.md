# ChatGPT Plugin功能

## ChatGPT Plugin带来的巨大改变
### 1. 实时即时搜索
可以通过接入第三方插件，直接向ChatGPT查询互联网上的最新信息，例如比赛结果、行情、最新消息等。 在此之前，ChatGPT 只有 2021 年之前的信息。它无法回复 2021 年之后的查询。

### 2. 访问包含私有域信息的数据库
ChatGPT 无法访问或了解一些曾经属于私有域数据的公司内部文件和个人笔记。 ChatGPT现在可以使用这个私域数据来学习学习，这要感谢第三方插件的加入。

### 3. 协助用户完成任务。
用户可以直接与 ChatGPT 对话，将一些应用任务分配给它，例如订餐或预订机票。

简单的说，ChatGPT不再是一个只能让你回复，不能更新知识的语言模型，得益于这个第三方插件的帮助。 它就像一个可以用人类语言说话的人工智能助手。 该插件类似于在ChatGPT上安装“手”和“耳朵”，它不仅可以获取特定知识，还可以协助我们完成各种日常工作。

OPENAI 有远大的野心
我们还可以从 ChatGPT 提供的第一批第三方插件中看出，OpenAI 的目标非常远大。 这些应用既涵盖了常见的科学计算、AI陪伴、程序交互等AI应用方向，也涵盖了出行、购物、订餐、购票等日常生活类应用方向。 

 以ChatGPT为代表的人工智能的应用正在迅速普及，我们现在期待着人工智能时代的“App Store”的到来。
 
 
## 部分已经上架的部分插件产品
 
 Expedia:  使用 Expedia ChatGPT 插件合理规划如何到达目的地、住宿地点以及到达目的地后的观光和活动，让旅行更加方便。
 
 FiscalNote: 让用户可以访问精选的行业最佳实时法律、政治和监管数据和信息源。
 
 Instacart: 允许用户从附近的超市下订单。
 
 KAYAK: 查找酒店、航班和汽车租赁服务。 可以使用 KAYAK ChatGPT 插件查看人们推荐访问的在指定价格范围内地点。
 
 Klarna Shopping: 用于搜索和比较价格。
 
 OpenTable: 为附近的餐馆提供建议，并协助提供预订餐桌的功能链接。
 
 Speak: 一款人工智能语言虚拟老师。
 
 Wolfram: 快速轻松地访问计算、数学、精选知识和最新数据。
 
 Zapier: 用户可以与 5,000 多个应用程序进行交互，包括 Google 表格、Trello、Gmail、HubSpot、Salesforce 等。
 
 Browsing: 与 WebGPT 扩展一样，通过使语言模型能够浏览互联网，将可以访问和讨论的主题扩展到训练语料库之外并接触到互联网时间的当前实时数据。 它也是 OpenAI 自己的两个插件之一。
 
 Code Interpreter: 不仅限于简单地生成代码，还可以将结果应用于用于其他地方。 这允许用户将不同的代码片段链接在一起，使用一个代码的输出作为下一个的输入。 它也是 OpenAI 自己的两个插件之一。
 
## 从0开始开发一款插件

### 1 资格申请
访问 `https://openai.com/waitlist/plugins`,申请测试资格

### 2 官方模版下载
git clone `git@github.com:openai/chatgpt-retrieval-plugin.git`

### 3 使用向量数据库进行插件编写
[使用qdrant数据库进行插件编写](https://qdrant.tech/articles/chatgpt-plugin/)  
[使用pinecone数据库进行插件编写](https://www.youtube.com/watch?v=hpePPqKxNq8)
