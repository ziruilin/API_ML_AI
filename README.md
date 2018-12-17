# API_ML_AI：行程APP

|         |            |
| ------------- |:-------------:|
| Target release     | 12月30日 |
| Epic      |  小程同学   |
| Document status | 中期      |
| Designer        | 蔡泽纯 |
| Developer       | 蔡泽纯 |
| QA | 蔡泽纯  |

##### 加值宣言
• 主要：做一款可以为用户记住行程并且不会打扰用户的行程APP<Br/>
• 辅助：调用微信好友功能，形成一个好友行程进度挑战，增加用户粘性，更有竞争力地去完成自己的任务行程<Br/>
##### 核心价值
• 着眼于用户的最基本需求，解决用户日常忘记行程计划的问题，通过好友行程进度提醒，促进用户竞争完成自己的行程挑战自己<Br/>
•	用户案例：每个人每天要做的事很多，但是很容易会忘记我到底要做什么，而且一年有365天，你可能不记得哪一天是谁的生日，你需要一个备忘录，提醒你这些事情。• 小程同学是一个很简单的APP，你在每一年输入要做的大事，如哪一天是谁的生日或者哪一天是四六级考试，他可以在这些节点上提示你或者你在前一天晚上输入第二天大致要做什么，他会提示你第二天的行程安排，并且可以语音播报<Br/> 
### 市场竞争对手分析
• 手机系统自带的备忘录、行程助手APP<Br/> 
• 手机系统自带的备忘录里面功能单一，没有像小程同学一样多功能，其次小程同学拥有微信好友竞争功能，有趣味性和竞争性，能够更好地帮助用户完成行程任务<Br/> 
• 行程助手这类型的APP都是专注于某一项事物，很有针对性，比如说旅游行程APP，着重于旅游行程的计划，跟小程同学所针对的领域不同，而且旅游行程没有像小程同学一样拥有微信好友竞争功能，有趣味性和竞争性，所以小程同学行程助手很有必要出现
### Goals: 
• 做一款可以为用户记住行程并且不会打扰用户的行程APP<Br/> 
##### 前期目标
• 完成静态原型图，思考可行性，写出大致的PRD(35%）<Br/> 
##### 中期目标
• 做出APP的流程图，并且评估进度，调查市场竞争力，寻找更好的方案及其用户核心价值点和痛点，尝试使用百度API(70%)<Br/> 
##### 后期目标
• 做出APP的思维导图、地图，完善交互原型图，运用百度API，做出Web APP雏形。（95%）
### 用户
所有想要提醒自己按时完成任务的人，如：懒癌晚期、拖延症重度患者、健忘的人
##### 用户痛点
• 蔡泽纯：大学生，想要考过六级，每次一考完六级就说下次要做个完美计划去复习六级，但每次都是做好计划丢在一边，最后又没过六级，此用户有目标，但是做好的计划没能随身带着，他不知道自己定的计划应该分散慢慢做，他需要小程同学每天提醒他该复习六级了<Br/> 
• 黎蝉：大学生，拖延症重度患者，每次都说自己有一堆作业，从早上起床后就开始坐在电脑前，开始打开阿雪的作业，然而舍友说要一起买美特斯邦威的衣服，他就逛起了淘宝，然后作业一拖再拖，最后一刻才真正能提交<Br/> 
• 卢佳燕：大学生，每天卢佳燕总是在别人做作业的时候，“你们在做什么，啊！！！有作业！！？？？我怎么不知道”，这是一个很健忘的人，特别是作业，但是他又会立马投入去做，最后成品总是在中等水平，现在他有了小程同学，这次的API作业，他在小程同学上录入模板，开始提示，从14周开始他每天做一点，现在已经做了一大半了，看来这次作业可以更上一层楼了<Br/> 
### Background and strategic fit: 
• 我在平时学习上不够自律，每一次作业都拖到最后，而且经常有些茫然。有时有些朋友生日我会忘记，容易淡化友谊，这款APP我觉得对很多人来说都是需要的，帮忙做好行程，并为你规定计划会让你更有效率地完成一件事<Br/> 
### Assumptions: 
|    Assumptions     |       Answer     |
| ------------- |:-------------:|
|   为什么用户要使用这个软件？      |   用户想想要更有效率地完成工作   |  
|   为什么用户想要有语音输入功能      |   用户想更加简单方便，懒得编辑   | 
|   什么样的人会使用这个软件？      |   所有想要提醒自己按时完成任务的人   | 
|   用户会在什么情况下使用这个软件？      |   用户需要一个监督提醒自己的机器助手   |  
|   为什么用户想要看好友的任务行程进度      |   好奇？竞争才能更有兴趣想做   |  
### 需求 Requirements: 
|         |    Title     |       User story     |      Importance     |      Notes     |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|
| 1        |   输入任务行程    | 按照自己需要设置行程任务 | 重要 | https://github.com/ziruilin/python |  
| 2        |   查看行程任务模板    | 选择自己想要的任务形成模板 | 重要 | Hutoma、Web Speech API |  
| 3        |   发送任务行程挑战    | 可以查看任务行程进度 | 重要 | 有效地使用时间 |  
##### 语音识别API
![avatar](./部分成功代码.png)<Br/> 
### 使用者交互及设计:
• 产品原型图：https://ziruilin.github.io/API_PT/<Br/> 
• APP流程图：<Br/> 
![avatar](./flow.png)<Br/> 
• 产品功能结构图：<Br/> 
![Image text](https://github.com/ziruilin/API_ML_AI/blob/master/%E4%BA%A7%E5%93%81%E5%8A%9F%E8%83%BD%E7%BB%93%E6%9E%84%E5%9B%BE.png)<Br/> 
### 问题 Questions: 
|    Question     |       Outcome     |   
| ------------- |:-------------:|
|   如何用语音输入行程      |   需要使用百度api的语音识别API   |  
|   如何查看好友行程进度      |   需要request调用微信里库   | 
|   如何向好友发送行程任务挑战      |   暂时Not doing   | 
### 不做 Not doing: 列出诗论及记录过的功能，超出范围的功能，下一版再改进的功能，都放在这
• 后期：在做好以上的时候，我想要实现规划行程时可以有多个行程选择<Br/> 
• 向好友发送行程任务挑战
