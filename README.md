# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0747springboot论坛管理系统 

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=103)


﻿**论坛管理系统**

**摘要：**

在社会快速发展的影响下，论坛管理系统继续发展，使论坛管理系统的管理和运营比过去十年更加信息化。依照这一现实为基础，设计一个快捷而又方便的网上论坛管理系统是一项十分重要并且有价值的事情。对于传统的论坛管理系统控制模型来说，在线论坛管理系统具有许多不可比拟的优势，首先是快速更新论坛管理系统的信息，其次是大量信息的管理，最后是高度安全，以及使用简单等特性，这使得论坛管理系统的管理和运营非常方便。进入21世纪，因为科技和经济的迅速发展，人民群众对非物质层面的精神需求正变得越来越多元化。本系统是为了实现这些目标而提出来的。

本论文系统地描绘了整个网上论坛管理系统的设计与实现，主要实现的功能有以下几点：管理员；首页、个人中心、用户管理、公告管理、公告类型管理、热门帖子管理、帖子分类管理、留言板管理、论坛新天地、我的收藏管理、系统管理，前台首页；首页、公告、热门帖子、论坛新天地、新闻资讯、留言反馈、个人中心、后台管理、客服中心，用户；首页、个人中心等功能，其具有简单的接口，方便的应用，强大的互动，完全基于互联网的特点。

现代社会的网络和信息技术不断提高，人们的生活水平达到一个新的层次。这篇文章研究了基于Spring Boot框架的论坛管理系统的开发和实现，从需求分析、总体设计到具体实现，最终完成了整个在线论坛管理系统，从而方便了用户和提高了管理人员的管理水平。

**关键词：**论坛管理系统，Spring Boot框架，数据库MYSQL，Java语言


**Abstract:**

Under the influence of the rapid development of society, the forum management system continues to develop, making the management and operation of the forum management system more information-based than in the past decade. According to this reality, it is very important and valuable to design a fast and convenient online forum management system. For the traditional forum management system control model, online forum management system has many incomparable advantages, first is to quickly update the information of the forum management system, secondly is the management of a large amount of information, finally is a high degree of security, and easy to use, which makes the management and operation of the Forum management system very convenient. In the 21st century, due to the rapid development of science and technology and economy, people's spiritual needs of the non-material level are becoming more and more diversified. This system is proposed to achieve these goals.

This paper systematically describes the design and implementation of the whole online forum management system. The main functions are as follows: administrator, home page, personal center, user management, announcement management, announcement type management, popular post management, post classification management, message board management, forum new world, my collection management, system management, front page front page, home page and announcement. Popular posts, forum new world, news and information, message feedback, personal center, background management, customer service center, users, home page, personal center and other functions. It has simple interface, convenient application, and strong interaction, which is entirely based on the characteristics of the Internet.

With the continuous improvement of network and information technology in modern society, people's living standard has reached a new level. This paper studies the development and implementation of the forum management system based on the spring boot framework, from the demand analysis, overall design to the specific implementation, and finally completes the entire online forum management system, so as to facilitate users and improve the management level of managers.

Key words: forum management system, spring boot framework, database mysql, Java language


目  录

[第1章 绪   论	1](#_Toc56688957)

[1.1课题背景	1](#_Toc56688958)

[1.2 课题意义	2](#_Toc56688959)

[1.3 开发工具及技术	2](#_Toc56688960)

[1.4 国内外现状	3](#_Toc56688961)

[第2章 系统分析	5](#_Toc56688962)

[2.1 可行性分析	5](#_Toc56688963)

[2.2总体设计原则	6](#_Toc56688964)

[2.3 系统需求分析	6](#_Toc56688965)

[2.4 业务流程分析	6](#_Toc56688966)

[2.5 数据流图	7](#_Toc56688967)

[第3章 系统设计	9](#_Toc56688968)

[3.1 系统功能设计	9](#_Toc56688969)

[3.2 数据库设计	10](#_Toc56688970)

[第4章 系统实现	15](#_Toc56688971)

[4.1前台首页功能模块	15](#_Toc56688972)

[4.2管理员功能模块	16](#_Toc56688973)

[4.3用户功能模块	19](#_Toc56688974)

[第5章 软件测试	22](#_Toc56688975)

[5.1软件测试的重要性	22](#_Toc56688976)

[5.2测试实例的研究与选择	22](#_Toc56688977)

[5.3测试环境与测试条件	24](#_Toc56688978)

[5.4系统运行情况	24](#_Toc56688979)

[5.5系统评价	24](#_Toc56688980)

[第6章 总结	25](#_Toc56688981)

[参考文献：	26](#_Toc56688982)

[致谢	27](#_Toc56688983)




1. ` `绪   论

1.1课题背景

2021年处于信息高速发展的大背景之下。在今天，缺少手机和电脑几乎已经成为不可能的事情，人们生活中已经难以离开手机和电脑。针对增加的成本管理和操作,网站非常有必要建立自己的网上论坛管理系统，这既可以让更多的人体验到网络所带来的方便。

以往的论坛管理系统相关信息管理，都是工作人员手工统计。这种方式不但时效性低，而且需要查找和变更的时候很不方便。随着科学的进步，技术的成熟，计算机信息化也日新月异的发展，社会也已经深刻的认识，计算机功能非常的强大，计算机已经进入了社会发展的各个领域，并且发挥着十分重要的作用。本系统利用网络沟通、计算机信息存储管理，有着与传统的方式所无法替代的优点。比如计算检索速度特别快、可靠性特别高、存储容量特别大、保密性特别好、可保存时间特别长、成本特别低等。在工作效率上，能够得到极大地提高，延伸至服务水平也会有好的收获，有了网络， 论坛管理系统的各方面的管理更加科学和系统，更加规范和简便。

本文所设计的在线论坛管理系统就是在这种客观条件下进行的，在论坛管理系统管理方面，传统的管理方式显然无法与在线论坛管理系统相比，在线论坛管理系统正发挥着越来越重要的作用。在线论坛管理系统的速度快、信息量大、安全、简单都是传统模式难以企及的优点，在本文中的在线论坛管理系统是一个基于MySQL数据库和Spring Boot框架的。

1.2 课题意义

社会主义进入新时代，经济实力越来越强。我们也变得越来越忙碌、对生活的要求也变得更加严格，对快速和方便的需求也在逐渐增加。因此，对论坛管理系统的管理要求也越来越严格。为适应时代的发展，各大网站开始广泛地使用电脑来进行管理，为提高工作人员效率提供了一种新的方式，并且减轻了他们的工作强度，在树立网站形象的同时，为用户提供更加方便、简单而高效的系统，实现双赢。

本系统即为方便管理员、用户而制作的网上论坛管理系统，结合了用户的需求，设计出的一个基于Java、MySQL的网上论坛管理系统。

1.3 开发工具及技术

网上论坛管理系统从本质上讲是一个电子商务模式综合而成的系统。实现了首页、个人中心、用户管理、公告管理、公告类型管理、热门帖子管理、帖子分类管理、留言板管理、论坛新天地、我的收藏管理、系统管理等基本功能。

主要用到以下技术：
### 1.3.1  B/S架构 
B/S结构的特点也非常多，例如在很多浏览器中都可以做出信号请求。并且可以适当的减轻用户的工作量，通过对客户端安装或者是配置少量的运行软件就能够逐步减少用户的工作量，这些功能的操作主要是由服务器来进行控制的，由于该软件的技术不断成熟，最主要的特点就是与浏览器相互配合为软件开发带来了极大的便利，不仅能够减少开发成本，还能够不断加强系统的软件功能，层层相互独立和展现层是该B/S结构完成相互连接的主要特性。
### 1.3.2  Java技术介绍 
Java语言擅长开发互联网类应用和企业级应用，现在已经相当的成熟，而且也是目前使用最多的编程语言之一。Java语言具有很好的面向对象性，可以符合人的思维模式进行设计，封装是将对象的属性和方法尽可能地隐藏起来，使得外界并不知道是如何实现的，外界能通过接口进行访问，继承是指每个类都会有一个父类，所有的子类都有父类的方法，可以进行继承，但是只有final修饰的类不能被继承，通过继承可以使得代码得到重新利用，能够提高软件的开发效率，也是多态的前提。

Java就像C语言、C#语言等，也是一种程序开发语言，而它的特点就是面向对象。作为一种程序开发与设计的语言，它有很多特性，主要特性就是面向对象、夸平台以及可以分布式运行。Java语言项目不但安全性高、稳定性强，而且可以并发运行。

为了提高开发的速度及效率，必须做到代码的重复使用和简化程序的复杂度，要达到上述的要求java语言通过封装、继承与多态等方式实现，这样可以很大程度上达到信息的封装，提高代码复用率，减少冗余度，提高效率。它使得以往程序中大量存在的内存泄漏的问题得到了较好的缓解。所谓的内存泄漏就是程序向操作系统申请了一块存储空间，比如定义了一个变量，但是由于某种原因，这个变量一直没有使用，但是仍然占用着系统的内存空间，可能一两个这样的变量对程序和操作系统造不成什么大的影响，但是试想如果这样的变量定义的多了系统的内存空间就会一步步减少，从而造成机器的性能降低甚至宕机。但是在Java中有垃圾回收机制的存在，这种机制极大地避免了内存泄漏的出现，在Java虚拟机中，垃圾回收机制会对长时间没有引用变量指向的对象实施垃圾回收，简单的说就是将这个对象销毁，以避免内存泄漏的情况出现。
### ` `1.3.3 mysql数据库介绍 
MySQL是一款Relational Database Management System，直译过来的意思就是关系型数据库管理系统，MySQL有着它独特的特点，这些特点使他成为目前最流行的RDBMS之一，MySQL想比与其他数据库如ORACLE、DB2等，它属于一款体积小、速度快的数据库，重点是它符合本次毕业设计的真实租赁环境，拥有成本低，开发源码这些特点，这也是选择它的主要原因。

本系统使用了MySQL数据库，建立了多张数据库表来存储租赁以及汽车租赁平台相关数据。系统中主要应用查询（select），修改（update），删除（delete）以及增加（insert）等语句来实现系统功能。

## 1.3.4 Spring Boot框架

Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。

1.4 国内外现状

随着计算机网络的不断渗透，人们的生活与工作、学习的方式也在慢慢发生变化。传统的论坛管理系统相关信息管理方式一般都采取人工的方式，信息的获取、整理、修改、存储等工作还停留在人工阶段。这种方式一方面需要花费大量的人力、物力和金钱，交互起来比较困难，而且会浪费时间；另一方面对用户等信息的管理，特别是随着用户数量的递增，查询、修改起来特别困难；最后由于用户等其他信息的不断增加，信息的存储也成为了难题。

一些发达国家，网络发展比较快，已经很大程度上完成了从人工到计算机管理的转变。我国计算机应用起步比较晚，而且发展区域不平衡，还有很多地区或单位使用传统的方式进行管理，但是目前计算机发展较快，包括网络也已经普及，很多单位和用户也开始慢慢接触网络管理系统。

`	`第二章  系统分析

2.1 可行性分析

可行性分析的目的是确定一个系统是否有必要开发、确定系统是否能以最小的代价实现。其工作主要有三个方面，分别是技术、经济和社会三方面的可行性。我会从这三个方面对网上论坛管理系统进行详细的分析。

2.1.1技术可行性

`	`该系统主要使用JAVA、MyEclipse和MySQL数据库进行开发，Java易于学习和使用灵活。在校期间也接触过MyEclipes和MySQL数据库的课程，对此有一定的开发经验，因此开发难度不高，所以从技术上来说是可行的。

2.1.2经济可行性

`	`本系统设计所选择的开发工具和服务器都是免费的开源软件，又或者是适合用户使用的免费版本，并不需要支付费用，而且由作者本人单独完成，也不存在团队费用，几乎没有经济成本，具备经济可行性。

2.1.3社会可行性

`	`社会可行性主要包括法律和用户两个方面，下面将从这两方面进行分析。

(1)法律因素

`	`本系统是学习开发所制作的程序，并不用作商业用途，是在根据实际调研的结果结合现有的网上论坛管理系统后得出的，而且系统制作的全部过程都是在个人的工作电脑中完成的，使用的都是开源和免费的开发环境、分析软件和数据库，不存在侵权问题。

(2)用户可行性

`	`操作人员或者用户只需要具备一定的windows电脑操作常识，不需要精通计算机技能。此外系统管理人员，只需要在windows常识之上再熟悉下使用Tomcat服务器的操作流程，只要掌握一定的计算机知识即可，在正式上线运营之前，仅需要对操作人员进行简单的熟悉流程培训即可。所以从用户可行性上也是可行的。

2.2总体设计原则

`	`一个系统要在开发和维护的过程中方便使用，必须采取一定的设计原则，其主要设计原则有：

`	`简单性：系统功能简单易懂，只需要掌握基本的计算机操作能力即可使用。

`	`针对性：针对特定的论坛管理系统用户，没有多余的其他功能，使用户可以专心使用。

`	`实用性：能够满足用户方面的需求。

`	`一致性：设计风格、命名规范一致，整个系统的各个功能模块色彩、摆放位置、功能等都是一致的。

`	`先进性：本系统的代码采用读取数据的方式，方便后续开发、拓展。

2.3 系统需求分析

论坛管理系统需要满足的需求有以下几个：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现用户对信息的控制和管理。

（3）方便查询信息及管理信息等；

（4）通过网络操作，改善处理问题的效率，提高操作人员利用率；

（5）考虑到用户多样性特点，要求界面简单，操作简便。

2.4 业务流程分析
### 2.4.1登录流程
登录模块主要满足管理员以及用户的权限登录，用户登录流程图如图2-1所示。

![](/md/blog.001.png)

图2-1 登录流程图
### 2.4.2注册流程
未有账号的用户可进入注册界面进行注册操作，用户注册流程图如图2-2所示。

![](/md/blog.001.png)

图2-2 注册流程图
### 2.4.3添加信息流程
用户在添加信息时，信息编号自动生成，系统会对添加的信息进行验证，验证通过则添加至数据库，添加信息成功，反之添加失败。添加信息流程如图2-3所示。

![](/md/blog.002.png)

图2-3 添加信息流程图
### 2.4.4删除信息流程
用户可选择要删除的信息进行信息删除操作，在删除信息时系统提示是否确定删除信息，是则删除信息成功，系统数据库将信息进行删除。删除信息流程图如图2-4所示。

![](/md/blog.003.png)

图2-4删除信息流程图




第三章	系统设计

3.1 系统概要设计

本论坛管理系统选择B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式。适合在互联网上进行操作，只要用户能连网，任何时间、任何地点都可以进行系统的操作使用。系统工作原理图如图3-1所示：

![](/md/blog.004.png)

图3-1 系统工作原理图
## 3.2系统结构设计
整个系统是由多个功能模块组合而成的，要将所有的功能模块都一一列举出来，然后进行逐个的功能设计，使得每一个模块都有相对应的功能设计，然后进行系统整体的设计。

本论坛管理系统结构图如图3-2所示。

![](/md/blog.005.png)

图3-2 论坛管理系统结构图

3.3 数据库设计

数据库可以说是所有软件的根本，如果数据库存在缺陷，那么会导致系统开发的不顺利、维护困难、用户使用不顺畅等一系列问题，严重时将会直接损害企业的利益，同时在开发完成后，数据库缺陷也更加难以解决。所以必须要对数据库设计重点把握，做到认真细致。因此，数据库设计是这个在线论坛管理系统的重点要素。

3.3.1概念结构设计

(1)管理员信息实体属性图如下图3-3所示

![](/md/blog.006.png)

图3-3管理员信息实体属性图



(2)公告信息实体属性如下图3-4所示

![](/md/blog.007.png)

`  `图3-4公告信息实体属性图

(3)热门帖子信息实体属性如下图3-5所示

![](/md/blog.008.png)

`    `图3-5热门帖子信息实体属性图

(4)用户信息实体属性如下图3-6所示

![](/md/blog.009.png)

图3-6用户信息实体属性图

3.3.2数据库表设计

每个数据库的应用它们都是和区分开的，当运行到一定的程序当中，它就会与自己相关的协议与用户进行通讯。那么这个系统就会对使这些数据进行连接。

当我们选择哪个桥段的时候，接下来就会简单的叙述这个数据库是如何来创建的。当点击完成按钮的时候就会自动在对话框内弹出数据源的名称，在进行点击下一步即可，直接在输入相对应的身份验证和登录密码。根据系统功能设计的要求和功能模块的划分，论坛管理系统的设计与实现以下数据表。下面就介绍一下各别主要数据库表的设计结构及其功能建立数据库表。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|


表4-2 gonggao表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|gonggaobiaoti|varchar|50|default NULL|
|gonggaoleixing|varchar|50|default NULL|
|gonggaoneirong|varchar|50|default NULL|
|fabushijian|varchar|50|default NULL|
|faburen|varchar|50|default NULL|
|fengmian|varchar|50|default NULL|

表4-3：rementiezi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|biaoti|varchar|50|default NULL|
|tiezifenlei|varchar|50|default NULL|
|faburen|varchar|50|default NULL|
|faburiqi|varchar|50|default NULL|
|tupian|varchar|50|default NULL|


表4-4：yonghu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|nicheng|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|xingbie|varchar|50|default NULL|
|shouji|varchar|50|default NULL|
|youxiang|varchar|50|default NULL|
|shenfenzheng|varchar|50|default NULL|
|zhaopian|varchar|50|default NULL|
|beizhu|varchar|50|default NULL|


第四章 系统实现

4.1前台首页功能模块

论坛管理系统，在系统首页可以查看首页、公告、热门帖子、论坛新天地、新闻资讯、留言反馈、个人中心、后台管理、客服中心等内容，如图4-1所示。

![](/md/blog.010.png)

图4-1前台首页功能界面图



`  `用户登录、用户注册，在注册页面可以填写账号、密码、昵称、姓名、手机、邮箱、身份证、照片、备注等详细内容进行注册、登录，如图4-2所示。

![](/md/blog.011.png)

![](/md/blog.012.png)

图4-2 用户登录、用户注册界面图

热门帖子，在热门帖子页面通过查看标题、帖子分类、发布人、发布日期、点击次数等信息进行点我收藏，如图4-3所示。在公告页面通过查看公告标题、公告类型、发布时间、发布人、点击次数等信息进行提交操作，如图4-4所示。

![](/md/blog.013.png)

图4-3热门帖子界面图

![](/md/blog.014.png)

图4-4公告界面图

4.2管理员功能模块

管理员登录，通过填写用户名、密码、角色进行登录，如图4-5所示。

![](/md/blog.015.png)

图4-5管理员登录界面图

管理员登录进入论坛管理系统可以查看首页、个人中心、用户管理、公告管理、公告类型管理、热门帖子管理、帖子分类管理、留言板管理、论坛新天地、我的收藏管理、系统管理等信息。

用户管理，在用户管理页面中可以通过查看账号、昵称、姓名、性别、手机、邮箱、身份证、照片、备注等内容进行修改，如图4-6所示。还可以根据需要对公告管理进行详情，修改或删除等详细操作，如图4-7所示。

![](/md/blog.016.png)

图4-6用户管理界面图

![](/md/blog.017.png)

图4-7公告管理界面图

公告类型管理，在公告类型管理页面中可以查看公告类型等信息，并可根据需要对已有公告类型管理进行修改或删除等操作，如图4-8所示。

![](/md/blog.018.png)

图4-8公告类型管理界面图

热门帖子管理，在热门帖子管理页面中可以查看标题、帖子分类、发布人、发布日期、图片等信息，并可根据需要对已有热门帖子管理进行修改或删除等详细操作，如图4-9所示。

![](/md/blog.019.png)

图4-9热门帖子管理界面图

帖子分类管理，在帖子分类管理页面中可以查看帖子分类等内容，并且根据需要对已有帖子分类管理进行详情，修改或删除等详细操作，如图4-10所示。

![](/md/blog.020.png)

图4-10帖子分类管理界面图

留言板管理，在留言板管理页面中可以查看用户名、留言内容、回复内容等内容，并且根据需要对已有留言板管理进行详情，修改或删除等详细操作，如图4-11所示。

![](/md/blog.021.png)

图4-11留言板管理界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图4-12所示。

![](/md/blog.022.png)

图4-12轮播图管理界面图

论坛新天地，在论坛新天地页面中可以查看帖子标题、用户名、状态等内容，并且根据需要对已有论坛新天地进行详情，修改或删除等详细操作，如图4-13所示。

![](/md/blog.023.png)

图4-13论坛新天地界面图

我的收藏管理，在我的收藏管理页面中可以查看收藏名称、收藏图片等内容，并且根据需要对已有我的收藏管理进行详情，修改或删除等详细操作，如图4-14所示。

![](/md/blog.024.png)

图4-14我的收藏管理界面图

新闻资讯，在新闻资讯页面中可以查看标题、图片等内容，并且根据需要对已有新闻资讯进行详情，修改或删除等详细操作，如图4-15所示。

![](/md/blog.025.png)

图4-15新闻资讯界面图


4.3用户功能模块

用户登录进入论坛管理系统可以查看首页、个人中心等内容。

个人信息，在个人信息页面中通过填写账号、昵称、姓名、性别、手机、邮箱、身份证、照片、备注等信息进行修改，如图4-16所示。

![](/md/blog.026.png)

图4-16个人信息界面图

第五章  软件测试

`	`测试存在于软件开发进程中的最后一个阶段，它可以保证一个软件的开发质量是否符合设计者的初衷，也为程序的正式上线做了最后一道质量检测的工序。软件测试主要是控制各种条件、包括软件输出方式，使用模式和运行环境等，来评估一个系统或应用是否符合设计标准。在软件测试过程中，我们一般刻意的去制造错误和极端条件，不能仅依照正常模式允许，而是多去尝试那些意外的情况。

5.1软件测试的重要性

`	`只有在运行和维护阶段之前经历大量的测试的软件，才能说明它的质量是经得起检验的。最近计算机业界也都一致认为，测试应该存在于软件设计的每个阶段，因为越早发现错误，修复起来就越容易。

`	`实际上，对于一个软件应用，错误是必然存在的，无论使用何种技术或手段，都不可能绝对的排除软件漏洞。测试是随着软件开发一同诞生的，两者是共同发展进步的。实际上，测试可以大幅度的降低维护的成本，如果一个漏洞在开发的早期就被发现，那么修复它的成本远比上线后再修复的成本要低得多。

5.2测试实例的研究与选择

测试有白盒测试和黑盒测试两种方式。

其中，白盒测试是将软件看成一个透明的白盒子，按照程序的内部控制结构和处理技术逻辑来选定测试用例、软件系统测试的逻辑路径及过程需要进行管理测试，又称玻璃盒测试。因此白盒测试需要选择足够多的测试用例，覆盖尽可能多的代码来发现程序中的错误。

黑盒测试，也称为功能测试。它将需软件看作一个黑盒，像一个普通用户一样来模拟软件的使用流程。黑盒测试通过大量的输入边界值或错误数据，来检查是否可产生正确的输出。

本系统测试 主要选择黑盒测试，少量采用白盒测试。通过测试达到以下测试目的：

1.检查各大功能模块的运行，确保其能够正确运行，并检查各页面的完整性，保证页面完整。

2.检查各个接口是否可以正确地输入和输出，保证数据流通稳定可行。

3.检查数据结构，保证其和外部接口没有访问错误，访问顺利。

4.检查原计划的性能需求有没有完成，运行流畅。

本系统的测试用例（部分）：

|**登录部分测试用例**|
| :-: |
|**编号**|**对象**|**项目**|**操作**|**预期结果**|**结果**|
|1|登录|登录提示|使用正确的账号密码登录|成功登录|预期结果|
|2||登录提示|使用正确的账号但错误的密码登录|提示密码错误|预期结果|
|3||登录提示|使用错误的账号登录|提示不存在账户|预期结果|
|4||登录提示|不输入账号，点击登录|提示输入账号|预期结果|
|5||登录提示|输入账号但不输入密码点击登录|提示输入密码|预期结果|
|6||登录入口|已登录账号，查看登录入口|不显示登录入口|预期结果|

5.3测试环境与测试条件

处理器：Inter Core I7-4710MQ四核处理器

内存：4GB

硬盘：1T

操作系统：Windows 10

数据库：MySQL

5.4系统运行情况

`	`全部测试用例都已通过（包括但不限于以上测试用例），且不存在漏洞，实现了论文开始时所作要求。本系统运行稳定，使用流畅，可以满足用户需求。

5.5系统评价

`	`5.5.1系统功能评价

试运行后进行系统评估，可以认为该系统达到预定的目标要求，可以满足用户的需求，也满足了系统开发前所作目标。

`	`5.5.2系统技术评价

系统在经过大量重复测试后运行十分稳定，安全实用，功能模块已经达到预定目标所需。

`	`5.5.3系统经济评价

在规定的时间内实现系统的大部分功能，且满足要求，节省开发成本，有助于提高科学管理水平，符合本人经济情况。

第6章 总结

2021年的今天，计算机技术已经相当成熟。它的发展推动了许多行业改头换面，计算机的出现使社会有了进一步降低人力物力和资源的方法，提高了社会的生产力，转变了社会生产方式。

本文利用Spring Boot框架和MySQL数据库技术，通过分析实现论坛管理系统的业务流程的基础上，并完成了在线论坛管理系统。经调试结果显示，本系统基本可以满足一个在线论坛管理系统的业务需要。系统界面简洁而有美感， 易操作，做出了自己的特点，然而因为时间仓促再加上缺乏系统开发经验和仅依靠少数问卷调查方式，因此本系统还存在不少缺陷、不足，比如：

\1. 数据输入的格式并没有全部检验，所以很难保证数据的准确，可能有一些不符合规则的数据也可以通过检验。

\2. 系统功能还不够完善，无法提供丰富多彩的在线功能，只能实现等一系列功能。

本系统还存在一些漏洞没有解决，在现实应用情境中很难保证完全不出错，但相信通过再次完善，可以调试出真正符合实际的在线论坛管理系统。

参考文献：

[1]Bruce Eckel．《Thinking in Java》(第三版) [M],American：Prentice Hall PTR，2017

[2]霍斯特曼等著，陈昊鹏等译．JAVA核心技术卷II：高级特性[M]. 2019.12

[3](英)格雷恩．Ajax实战——实例详解[M].北京：人民邮电出版社 2019年11月

[4]王占全，苏玲．Eclipse全程指南[M]. 北京：电子工业出版社，2019年3月

[5]李清霞．《java动态网页设计》课程建设与教学模式研究[J].福建电脑，2017,33（06）：92-93+166

[6]李刚．整合STRUTS+HIBERNATE+SPRING应用开发详解[M]．北京：电子工业出版社2017年1月

[7]孙卫琴,李红成．Tomcat与java WEB开发技术讲解.电子工业出版社.2019年六月:1-205

[8]张丽．基于C语言访问的MySQL数据库[J]. 电子技术与软件工程，2018,（22）：165-166

[9]廖琴，文成玉．MySQL数据库高可用性的研究与实现[J]. 科技风，2018,（18）：100

[10]王国辉，王易．java数据库系统开发案例精选[M].北京:人民邮电出版社,2019

[11]高杨，赵立杰．基于java+MySQL的物流管理系统的设计与实现[J].信息系统工程，2018,（11）：141+143

[12]王金龙，张静．基于java+Mysql的高校慕课（MOOC）教学系统设计[J].通讯世界，2017,（20）：276-277

[13]高祖彦．软件工程思想在java程序设计教学中的应用[J].时代教育，2017,（09）：211

[14]霍斯特曼等著，陈昊鹏等译．JAVA核心技术卷II：高级特性[M]. 2019.12

[15]吴秀娟．java在动态网页制作技术比较分析[J].数字技术与应用，2018,（10）：221+223.

致谢

`	`大学生活在这个时候即将划上一个句号，但是对于我的人生道路来说，这仅仅是一个逗号，我将面对的是又一次征程的开始。

`	`回忆过去，许许多多的事情浮现在脑海：刚上大学时欢乐心情和兴奋的场景还历历在目。一切都是那么新鲜，那么富有吸引力。有快乐也有艰辛，有收获也有失落。衷心感谢学院所有支持帮助过我的老师，谢谢你们多年来的关心和爱护。同窗的友情同样难忘，你们与我共同走过了人生中不平凡的道路，给我留下了值得珍藏的美好记忆。

`	`最后，我要特别感谢指导过我的老师。本论文是在他的悉心指导和热情帮助下完成的，老师认真负责的工作态度，严谨的治学精神和精深的理论水平都使我受益匪浅。老师无论在理论上还是在实践中，都给予我很大的帮助，使我专业技能的应用水平得到很大提高，这对于我以后的工作和学习都有益处。值此论文完成之际，特别向老师表示衷心的感谢和崇高的敬意，谢谢他细心而又耐心地辅导，使得我得以顺利的完成毕业设计开发工作，同时也要感谢其他帮助过我的老师和同学，他们在我成长过程中给予了我很大的帮助，在此一并表示感谢。

`	`由于本人水平有限，加上时间紧促，本文一定有不少缺点和不足，恳请各位老师给予帮助和指正。





35
![](/md/blog.027.png)	











