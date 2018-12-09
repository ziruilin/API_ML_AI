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

### Goals: 
• 做一款可以为用户记住行程并且不会打扰用户的行程APP<Br/> 
##### 前期目标
• 完成静态原型图，思考可行性，写出大致的PRD(35%）<Br/> 
##### 中期目标
• 做出APP的流程图，并且评估进度，调查市场竞争力，寻找更好的方案及其用户核心价值点和痛点，尝试使用百度API(70%)<Br/> 
##### 后期目标
• 做出APP的思维导图、地图，完善交互原型图，运用百度API，做出Web APP雏形。
### 用户
所有想要提醒自己按时完成任务的人，如：懒癌晚期、拖延症重度患者、健忘的人
##### 用户痛点
• 蔡泽纯：大学生，想要考过六级，每次一考完六级就说下次要做个完美计划去复习六级，但每次都是做好计划丢在一边，最后又没过六级，此用户有目标，但是做好的计划没能随身带着，他不知道自己定的计划应该分散慢慢做，他需要小程同学每天提醒他该复习六级了<Br/> 
• 黎蝉：大学生，拖延症重度患者，每次都说自己有一堆作业，从早上起床后就开始坐在电脑前，开始打开阿雪的作业，然而舍友说要一起买美特斯邦威的衣服，他就逛起了淘宝，然后作业一拖再拖，最后一刻才真正能提交<Br/> 
• 卢佳燕：大学生，每天卢佳燕总是在别人做作业的时候，“你们在做什么，啊！！！有作业！！？？？我怎么不知道”，这是一个很健忘的人，特别是作业，但是他又会立马投入去做，最后成品总是在中等水平，现在他有了小程同学，这次的API作业，他在小程同学上录入模板，开始提示，从14周开始他每天做一点，现在已经做了一大半了，看来这次作业可以更上一层楼了<Br/> 
##### 用户画像

### Background and strategic fit: 
• 我在平时学习上不够自律，每一次作业都拖到最后，而且经常有些茫然。有时有些朋友生日我会忘记，容易淡化友谊，这款APP我觉得对很多人来说都是需要的，帮忙做好行程，并为你规定计划会让你更有效率地完成一件事<Br/> 
### Assumptions: 
•	用户在开始下这个APP 时，可以对一年中的所有大事件进行设置，然后对这些大事件进行一些行程的安排，如：我2018年9月在APP 上写下2018年12月我要过六级，那么小程同学APP 会为我规划今年2018年9月到2018年12月我要做什么，并语音提示；API技术：Hutoma、Web Speech API、语音识别API <Br/> 
•	用户在前一天晚上输入第二天要做的事，可以语音输入，也可以文字输入，小程同学做好规划，并在第二天语音提示，也可以文字提醒，技术：Hutoma、Web Speech API<Br/> 
### 需求 Requirements: 
|         |    Title     |       User story     |      Importance     |      Notes     |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|
| 1        |   输出植物名称后，想知道类似植物植物信息    | 需要点击知道更多 | Must Have |  |  
| 2        |   输出植物图片后，想分享出去从而打卡形成植物地图    | 需要点击分享 | Must Have |  |  
| 3        |   每分享一次将点亮一个濒临灭绝植物/稀有植物的卡片,并获取其信息    | 需要点击查看 | Must Have |  |  
#### 所对映的标题（Title）丶：
• 年级规划<Br/> 
#### 重要程度（Importance）及：
• 有效地使用时间<Br/> 
#### 笔记（Note）：
• Hutoma、Web Speech API<Br/> 
• https://www.jianshu.com/p/ac690e784371<Br/> 
• 百度API的语音识别<Br/> 
• 代码：https://github.com/ziruilin/python<Br/> 
### 使用者交互及设计:
• 产品原型图：https://ziruilin.github.io/API_PT/<Br/> 
• APP流程图：<Br/> 
![Image text](./flow.png)<Br/> 
• APP流程图：<Br/> 
![Image text](./产品功能结构图.png)<Br/> 
### 问题 Questions: 
• 在做完上面需求之后，我可以做出一个运用Hutoma、Web Speech API等API 支持下的一个Web APP ，这个APP 可以解决我们日常的记性差的问题，让我们更方便地规划自己的行程，更有效率地完成工作<Br/> 
### 不做 Not doing: 列出诗论及记录过的功能，超出范围的功能，下一版再改进的功能，都放在这
• 后期：在做好以上的时候，我想要实现规划行程时可以有多个行程选择<Br/> 
