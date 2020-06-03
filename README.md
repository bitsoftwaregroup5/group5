# group5    **校园周边美食系统**

# 主博客线

## ***目录***
### **一．引言**
- 1	项目目的
- 2	项目背景
### **二. 总体描述**
- 2.1 产品前景
- 2.2 产品功能
- 2.3 用户特征
- 2.4 调研及原型
- 2.5 假设和依赖
### **三. 详细需求描述**
- 3.1 结构化需求分析
- 3.2 过程建模
- 3.3 数据建模
- 3.4对外接口需求
- 3.5 功能需求
- 3.5.1 系统特性1 
- 3.6 性能需求 
- 3.7 约束
- 3.8 质量属性 
- 3.9 其他需求 附录 索引


# 一、	引言： 

## 1．	项目目的：
  北京理工大学良乡校区作为一个拥有万人级人员的学校，对于周边的餐饮业消费具有巨大的潜力和需求，在如此的情况下，有一些已知的美食评价类软件不能很好地满足特定用户群体的需求，为了解决此类问题，我们小组计划完成一个用于美食评价的系统，来解决相关的软件需求。

## 2．	项目背景：
委托单位：无委托
主管部门：北京理工大学软件学院
待开发系统名称：校园周边美食评价系统
软件运行平台：windows系统（安卓系统）

# 二、	总体描述

## 1.产品前景

### 前期调研：

学生消费情况：
北京理工大学学生人数：约12000人
男生比例：65% 女生比例 35%
平均年龄 约21岁
平均月消费：约2000元，餐饮占比约60%
学生月外出餐饮消费规模：约200万元每月
学生预计打分频次： 50000次/月（待统计）
学生预计浏览量：  待统计 

校园周边餐饮营业情况（数据来自大众点评）
标准：以校内博雅园为中心500米内

按餐厅风格分类：
快餐小吃 50家
咖啡厅 2家
家常菜馆 33家

按菜品类别分类：
烧烤类 10家
海鲜类 3家
火锅类 9家

中国菜系：
西北菜 1家
东北菜 2家
北京菜 1家
湘菜 3家
川菜 14家
江浙菜 1家
粤菜 2家

海外菜系：
韩国料理 4家
日本料理 3家
西餐 5家

价格情况：
最贵：朝天门火锅 人均140元
最廉价：水仙小粥 人均19元
平均价格 人均49元

评价情况：
最高 走板 4.83分
最低 橄榄树 3.37分
平均打分：约4.1分

### 调研结果和前景分析：
- 1.北京理工大学学生数量较多，教职工人数也较多，消费能力可观，对于周围商铺带来的消费基数大，消费能力较强，消费需求多样。
- 2.学生使用软件的频率预计将为中等偏上，因为学生接受新事物能力较强，对于软件使用较为熟练。
- 3.在价格上差异，波动范围较大，商家和餐馆种类较为丰富，可以提供较多样的分类和评价服务。

## 2.产品功能
本产品的主要功能有：
针对餐饮行业的消费者
提供食物的分类推荐，选择订购查询和实时信息共享的服务。
对餐饮行业的商家
提供产品的展示，售卖和信息修改的功能。
对于软件后期的维护者
提供系统的各项信息和修改权限。





## 3.用户特性

**a.涉众概要**
US001	普通用户	

普通用户是指用该系统进行美食信息查看评价等功能的用户	
1.登陆并注册该系统
2.查看当天的热门美食推荐
3.通过系统查询、筛选所需要的美食信息和店铺信息和距离等
4.浏览选中的具体信息
5.对具体店铺和菜品进行评价打分
6.可以给商家留言或提出建议

US002	餐饮管理者	

餐饮管理者是指可进行菜品信息添加修改，对食堂反馈建议进行回复的用户	
1.发布、修改菜品信息
2.对用餐反馈进行回复
3.总览模式查看菜品评价


US003	管理员	

管理员是指维护网站正常运行并管理用户信息和公告的用户	
1.审核、修改用户信息
2.发布、修改、删除不良评论
3.维护网站基本功能的运行

US004	系统开发人员	

系统开发人员是对系统进行开发和维护的人员	
1.开发校园周边美食系统
2.对系统使用中遇到的问题进行维护和修复


**b. 涉众简档**
 
 普通用户
 
- 涉众	SH001 普通用户
- 涉众代表	普通用户代表
- 特点	系统的主要使用者，在校大学生
- 权利	
1.登陆并注册该系统
2.查看当天的热门美食店铺推荐
3.通过系统查询、筛选所需要的菜品信息，可以根据距离、价格、好评等筛选
4.浏览选中的具体店铺信息，包括但不限于菜品价格、距离、好评度
5.对具体店铺和菜品进行用餐评价打分
6.可以给商家留言或提出建议
- 成功标准	1.能根据关键字或者排序依据正确搜索到需要的餐饮
2.可根据餐后情况进行评价打分
不参与系统建设
可交付工作：无
意见/问题：无


 餐饮管理者
 
 
- 涉众	SH002 餐饮管理者
- 涉众代表	餐饮管理者代表
- 特点	系统的主要使用者之一
- 职责	
1.发布、修改店铺信息
2.对用餐反馈建议进行回复
- 成功标准	
1.能正确得到各种菜品的用餐情况
2.可调整/修改/增加店铺信息
不参与系统建设
可交付工作：维持店铺信息的更新
意见/问题：无


系统管理员


- 涉众	SH003 管理员
- 涉众代表	管理员代表
- 特点	系统的预期使用者之一，应具备相应的计算机操作水平
- 职责	
1.审核、修改用户信息
2.发布、修改、删除不良评论
3.维护网站基本功能的运行
- 成功标准	
1.参与保障平台言论的和谐
2.网站平稳正常运行
参与保障平台言论的和谐
可交付工作：维护平台的和谐文明
意见/问题：无



系统开发人员


- 涉众	SH004 系统开发人员
- 涉众代表	系统开发人员代表
- 特点	系统的开发者
- 职责	
1.开发校园周边美食系统
2.对系统使用中遇到的问题进行维护和修复
- 成功标准	校园周边美食系统运行良好
参与系统建设
可交付工作：校园周边美食系统
意见/问题：无






## 4.调研及原型


### 面谈方法
1、	项目的潜在用户采用调查问卷的方式参与需求调研
2、	采用QQ平台的方式线上面谈

### 面谈过程
1、	调查问卷
（1）准备面谈
     创建了校园周边美食系统的调查问卷
（2）开展面谈
    将调查问卷分享到微信群等社交场所，激励合适的受众进行填写。
（3）处理面谈
复查结果：对收集到的数据进行分析，舍去无效的问卷案例。

面谈总结：

本次调查问卷主要针对北京理工大学的在校本科生展开，结果表明：
1大多数同学出校偶尔才会出校品尝校园周边美食，能承受的人均消费额为50元到100元；
2食品口味和产品价格为同学们最期望美食评价包含的因素；
3多数同学期望本系统能推荐好评度高的美食店家；
4大多数同学赞同本系统的设计理念。
    

2、	线上面谈
（1）准备面谈
   确定面谈内容、主题： 对项目的功能需求进行确认
         确定面谈时间： 2020年4月10日
   确定面谈参与者：
甲方：第一组 
乙方：第五组
       （2）主持面谈
          采用线上通过微信、QQ等方式进行讨论交流
       （3）面谈类型
            采用半结构化面谈
            涵盖乙方预设的问题，听取甲方的相关意见
       （3）处理面谈
           总结面谈结果：
A.	对美食按照标准进行分区分类（分类标签）
B.	用户可对美食进行评价打分（评价打分）
C.	用户管理（账号密码）
  

### 垂直原型系统

A.	潜在用户范围较小
全体北京理工大学良乡校区在校师生，包括本科生、硕士研究生、博士研究生以及教师。
B.	市面上存在可供参考的美食评价系统，如大众点评等软件，其功能开发较为完善；
C.	本系统为非盈利项目，由用户上传美食评价信息，平台仅参与开发及维护管理；
D.	易于确定完整稳定的功能需求
（1）	普通用户 
-登录并注册系统
-查看美食推荐
-查询美食信息
-对店铺和菜品进行评价打分
-给商家留言或提出建议
（2）	餐饮管理者
-发布、修改菜品信息
-对客户留言进行回复
-总览查看美食评价
（3）	系统管理员
-审核、修改用户信息
-删除不良言论
-维护网站基本功能的运行
              
通过情节串联图版描述原型
涵盖了系统前后端的功能需求


## 6.假设和依赖

### 软件生成假设:

软件应该具有的基本能力是查找并分类相应的餐厅和饮食营业机构，对客户的分类需求作出反应，同时根据客户的搜索推荐相应的餐厅并给出评价，在商家方面给予商家足够的空间展示本商家的商品，对于各种商品的上架和下架具有及时操控权，同时对于系统维护者相对友好，易于后期的修改与维护。


### 依赖性：

产品基于广大的用户，需要用户保持较长时间的购买力和较高的购买热情，同时需要顾客对于本商品有足够的使用能力，最后需要客户和商家都具有相应的设备和系统进行本软件的下载与使用。



# 三、	详细需求描述

## 1.结构化需求分析：

### 功能分解图：

### 需求细化：

需求编号	A1
需求描述	用户可以注册账号并进行登录
源头	针对用户使用软件的要求
成本需要	建立用户信息数据库和交互功能
可变性	中等
优先级	中等

需求编号	B1
需求描述	商家用户可以发布菜品图片，价格及描述
源头	针对商家用户进行菜品展示和宣传的要求
成本需要	建立一个针对商家用户传输数据的渠道
可变性	较高
优先级	较高

需求编号	B2
需求描述	系统自动面向普通用户推荐美食
源头	进一步方便普通用户在线浏览菜品的要求
成本需要	在系统基础上运用合适算法推荐菜品
可变性	较高
优先级	较低


需求编号	B3
需求描述	用户可以搜索商家或菜品名称
源头	进一步方便普通用户在线浏览菜品的要求
成本需要	在系统基础上添加一个搜索引擎
可变性	中等
优先级	中等

需求编号	C1
需求描述	用户可以搜索查看菜品评论
源头	方便普通用户和商家参考其他评论
成本需要	开拓评论区并添加搜索引擎
可变性	中等
优先级	高

需求编号	C2
需求描述	用户可以对菜品进行打分
源头	美食评价系统的核心功能
成本需要	在评论区添加一个打分功能
可变性	中等
优先级	高

需求编号	C3
需求描述	用户可以添加针对菜品的评论
源头	便于用户详细描述对菜品的评价便于其他用户和商家参考
成本需要	增加评论区的编辑功能
可变性	中等
优先级	较高


需求编号	C4
需求描述	评论发布者和管理员可以删除评论
源头	针对整个系统的管理优化的需求
成本需要	增加评论区的删除功能并设置权限
可变性	较低
优先级	中等


|简述|对象1|对象2|对象3|
|------- |:--:|:--:|--:|
|需求编号 |	A1|	B1|	B2|
|需求描述|	用户可以注册账号并进行登录	|商家用户可以发布菜品图片，价格及描述|	系统自动面向普通用户推荐美食|
|源头	|针对用户使用软件的要求|	针对商家用户进行菜品展示和宣传的要求|	进一步方便普通用户在线浏览菜品的要求|
|成本需要	|建立用户信息数据库和交互功能|	建立一个针对商家用户传输数据的渠道|	在系统基础上运用合适算法推荐菜|
|可变性	|中等|	较高|	较高|
|优先级	|中等|	较高|	较低|
|需求编号|	B3|	C1|	C3|
|需求描述	|用户可以搜索商家或菜品名称|	用户可以搜索查看菜品评论|	用户可以添加针对菜品的评论|
|源头|	进一步方便普通用户在线浏览菜品的要求|	方便普通用户和商家参考其他评论|	便于用户详细描述对菜品的评价便于其他用户和商家参考|
|成本需要|	在系统基础上添加一个搜索引擎|	开拓评论区并添加搜索引擎|	增加评论区的编辑功能|
|可变性|	中等|	中等|	中等|
|优先级|	中等|	高|	较高|


# 过程建模

## （一）DFD图
（1）DFD-0层图
 
（2）DFD-1层图
 
（3）DFD-2层图

 


 

 


## （二）微规格说明
READ customer account-type
SELECT CASE
CASE 1 (account-type is Student)
	action 1 Add data to database
    action 2 Search data in the database

CASE 2 (account-type is Restaurant)
	action 1 Remove data from database
	action 2 Add data to database

CASE 3 (account-type is Administrator)
	action 1 Remove data from database
	action 2 Add data to database
	action 3 Kick out one's account

END CASE


## （三）数据字典
|对象|内容|
|--|:--:|
|数据项名称|				用户个人信息|
|描述	|用于存储用户的基本信息|
|组成|	账号、密码、昵称、邮箱、权限|
|--|--|
|数据项名称	|			菜品信息|
|描述|	用于存储菜品的基本信息|
|组成|	名称、价格、图片样式、供应时段、供应地点|
|--|--|
|数据项名称	|			评价信息|
|描述	|用于存储菜品的评价信息|
|组成|	好评度、星级、对菜品的描述、用户的感受|


# 数据建模


## ERD建模：
- 1.	实体
校园周边美食评价系统的实体有管理员、普通用户、餐饮管理者、店铺和菜品以及评价与打分。
- 2.	属性与标识符
（1）管理员的属性有账号、管理员编号和密码，其中账号为标识符。
（2）普通用户的属性有账号、昵称、密码和联系方式，其中账号为标识符。
（3）餐饮管理者的属性有账号、昵称、密码和联系方式，其中账号为标识符。
（4）店铺和菜品的属性有店名、菜名、简介、图片、地址和价格，其中店名和菜名为标识符。
（5）评价与打分的属性有编号、内容、分数、发布者和发布时间，其中编号为标识符。
- 3.	关系
一个餐饮管理者只经营一家店铺，一个普通用户可挑选多家店铺及菜品，一个普通用户可进行多次评价与打分，一个餐饮管理者可对多个评价进行回复，一个管理员可以审核多个评价与打分。
- 4.	ER图



### 优先级划分

## 3.1 对外接口需求 ——待定

## 3.2 功能需求
- 各种各样的美食分类更加细致。
- 增加了用户注册与登录页面，使得消费者有了更加完整的选择权以及信息的保留。
- 评分方式更加多样，使用户能够对于产品的内容和形式进行打分。
- 在交互方面用更加和谐的色彩与风格，是用户在使用软件时有更好的使用印象与使用体验。

## 3.2.1 系统特性1 
- 能够与用户数据对用户的需求作出反应。
- 能够给用户评分以及产品反馈的机制，给用户更多的选择权与产品发言权。
- 给予用户更加优质的交互体验与简洁明快的界面。
## 3.3 性能需求 ——待定
## 3.4 约束 ——待定
## 3.5 质量属性 ——待定
## 3.6 其他需求 ——待定

