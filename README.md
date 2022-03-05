# 中科大计算机复试详解

+ [一. 介绍](#一-介绍)
+ [二. 机试部分](#二-机试部分)
	+ [1.1 机试介绍](#11-机试介绍)
	+ [1.2 历年机试题详解](#12-历年机试题详解)
	+ [1.3 如何准备机试](#13-如何准备机试)
+ [三. 笔试部分](#三-笔试部分)
	+ [3.1 笔试介绍](#31-笔试介绍)
	+ [3.2 如何准备笔试](#32-如何准备笔试)
+ [四. 面试部分](#四-面试部分)
	+ [4.1 面试介绍](#41-面试介绍)
	+ [4.2 如何准备面试](#42-如何准备面试)
+ [五. 后记](#五-后记)
+ [六. 帮助](#六-帮助)

## 一. 介绍

中国科学技术大学计算机专业考研复试主要包含三个方面：机试、笔试和面试，接下来会从这三个方向进行介绍。

本仓库中包含4个文件夹，文件夹的内容如下所示：

```
├── 机试历年真题  # 2006～2021年的我的机试代码
├── 笔试历年真题  # 可以搜集到的历年笔试真题
├── 面试经验      # 上岸学长学姐的面试经验总结
```

**注**：本文只包含对于**中科大计算机**中**考研复试**内容的介绍，不包含考研初试。

## 二. 机试部分

### 1.1 机试介绍

科大的机试部分一般是在复试时到科大的机房中上机考试，学校会在考试时给你上机的电脑中发送一个文件夹，文件夹中有题目描述，完成所有题目后将所有代码压缩打包后上交。代码要求用`C/C++`编写，上机环境的可以是`CodeBlocks`、`Dev C++`或`Visual Studio`。

但是由于疫情原因，在2020年和2021年复试采用了线上的方式，所以形式就改为了复试网络平台中（zoom或腾讯会议）中将题目发给你，在摄像头面前手写所有代码，完成后将代码拍照并且转为pdf文件上交。

机试的风格类似OJ，但是题目描述一般比较简短（不会像有的oj那样让你做阅读理解的），题目数量因年而异，一般是四道题，难度一般不会太简单（2020年和2021年由于采用了线上所以比较白给）。

### 1.2 历年机试题详解

笔者在备考的过程中完成了历年所有的机试题目，并且编写了机试详解，包含试题、代码和解析，文章链接如下所示，其中所有的代码都用`C++`编写。

文章存储在`github pages`上，没有`科学上网`的同学可能访问比较慢，请耐心等待。

+ [2006年机试题详解](https://zdszero.github.io/posts/ustc-test-2006/)
+ [2007年机试题详解](https://zdszero.github.io/posts/ustc-test-2007/)
+ [2008年机试题详解](https://zdszero.github.io/posts/ustc-test-2008/)
+ [2009年机试题详解](https://zdszero.github.io/posts/ustc-test-2009/)
+ [2010年机试题详解](https://zdszero.github.io/posts/ustc-test-2010/)
+ [2011年机试题详解](https://zdszero.github.io/posts/ustc-test-2011/)
+ [2012年机试题详解](https://zdszero.github.io/posts/ustc-test-2012/)
+ [2013年机试题详解](https://zdszero.github.io/posts/ustc-test-2013/)
+ [2014年机试题详解](https://zdszero.github.io/posts/ustc-test-2014/)
+ [2015年机试题详解](https://zdszero.github.io/posts/ustc-test-2015/)
+ [2016年机试题详解](https://zdszero.github.io/posts/ustc-test-2016/)
+ [2017年机试题详解](https://zdszero.github.io/posts/ustc-test-2017/)
+ [2018年机试题详解](https://zdszero.github.io/posts/ustc-test-2018/)
+ [2019年机试题详解](https://zdszero.github.io/posts/ustc-test-2019/)
+ [2020年机试题详解](https://zdszero.github.io/posts/ustc-test-2020/)
+ [2021年机试题详解](https://zdszero.github.io/posts/ustc-test-2021/)

### 1.3 如何准备机试

如果你看完上述所有的机试详解，你就会发现有些年份题目并不简单，但仔细观察也会发现如下特点：
+ 试题会考察数据结构书中所提到的经典算法。
+ 试题会考察常见的算法思想。
+ 试题常常会有文件I/O的部分，并且有时会涉及比较麻烦的输入输出处理。

所以你需要熟练掌握`数据结构`书中的以下的**算法原理**和**代码实现**：
+ 队列和栈相关
  + 前缀、中缀、后缀表达式求值
  + 中缀转前缀、中缀转后缀
+ 树相关
  + 根据前序、中序、后序遍历序列中的两个构建二叉树
  + 根据完整的遍历序列（包含空结点）构建二叉树
  + 哈夫曼树的构建，如何得到哈夫曼编码
+ 图相关
  + 深度优先遍历、广度优先遍历
  + 最小生成树的算法
  + 最短路径
  + 拓朴排序
+ 搜索和排序相关
  + 快速排序

同时学习以下**算法思想**：
+ 熟练掌握典型的`回溯`算法，历年试题有考察到如八皇后、子集划分等算法。
+ 了解基本的`动态规划`思想，历年试题有考察到如最长递增子序列、最大连续子序列等算法。

并且熟悉`C/C++`中的**I/O用法**，能够：
+ 根据根据给定的文件构建二叉树、图的数据结构
+ 按照指定的要求将结果输出到文件或控制台

## 三. 笔试部分

### 3.1 笔试介绍

`科计`的笔试一直是复试中难度最大的点之一，也是众多考生放弃报考科大计算机的重要原因。其中包含对以下四门课的考察：计算机体系结构、编译原理、数据库、离散数学。从初试408的四门专业课，到复试笔试中难度更大的四门，科计考生在整个考研过程中几乎将整个大学的专业课全部以更高的难度重考了一遍，可以说是**太扎实了！**

但是2020年和2021年由于疫情原因采取线上复试，笔试直接取消，复试难度直线下降。

### 3.2 如何准备笔试

首先你需要确定你报考的当年是否有笔试，如果没有的话就不需要大废工夫准备了，关于复试具体安排请参考当年的[招生简章](https://yz.ustc.edu.cn/zsjz_index/index.htm)。

笔试部分的参考书籍如下所示，建议在考完研的寒假认真阅读书籍并完成历年笔试真题（如果要考笔试的话寒假千万不要摸鱼，不然寒假过后准备时间肯定不够），如果还有空的话可以参考网上的答案完成参考书籍的课后习题。建议优先掌握离散数学、数据库、计算机体系结构的知识，相比编译原理更为简单，编译原理如果没空的话只阅读词法分析和语法分析章节即可，可以覆盖笔试考察的大部分内容。

```
1）方世昌，离散数学(第三版)，西安电子科技大学出版，2009年版。
2）陈意云、张昱，编译原理（第2版），高等教育出版社，2008年版（或2003年版）。
3）陈火旺、刘春林、谭庆平、赵克佳、刘越，程序设计语言编译原理（第3版），国防工业出版社，2006年版。
4）王珊，萨师煊，数据库系统概论(第五版)，高等教育出版社，2014年版。
5）张晨曦、王志英、沈立、刘侬编著，计算机系统结构教程，清华大学出版社2009年版。
```

除此之外，在学习编译原理时笔者强烈建议阅读[Compiler Construction](https://book.douban.com/subject/2709089/)这本书，示例丰富、将复杂的概念写得简单易懂，便于初学者理解。

最后，在复习的过程中不要只看书，不做题，看书的同时一定要完成章节内的相关习题以及真题中的相关试题。

## 四. 面试部分

### 4.1 面试介绍

面试的流程一般是这样：
+ 英文自我介绍
+ 用英文解释常见的计算机专业词汇
+ 老师向你提问（专业问题）

### 4.2 如何准备面试

英语介绍怎么写这里就不多讲了，网上一找一大堆，就是注意不要用太华丽的辞藻，能逻辑清晰地介绍自己就可以。

关于计算机专业词汇的英文，掌握常用的即可，包含一般的计算机方向以及课程内的一些词汇。比如笔者在面试时被问答如下几个问题：编译器-`compiler`，分布式计算-`distributed computation`，物联网-`Internet of things`。

专业面试的范畴就比较广了，一般老师会先问你擅长哪些科目，然后会提问你擅长科目的一些问题。具体会问哪种风格问题可以参考项目目录`面试经验`中的经验总结，其中有各式各样的问题，面试问题前些年考过的之后也往往会考，可以选择一些科目认真准备一下。

还有一个有技巧的点是你可以引着老师问特定方向的问题，比如老师问你最喜欢什么科目，笔者当时的回答是最`喜欢编译原理，并且我毕业设计也是做得相关内容`，这时候老师就很有可能问你毕业设计中的内容，就可以趁机多讲一讲毕业设计的内容。总体的面试时间不会太长，一般是15~20分钟，多准备一些话题和老师闲扯一下，老师问的`干货问题`也就会少很多了，大家可以把握一下。

## 五. 后记

[为什么报考科大](./why-ustc.md)

## 六. 帮助

如果这个项目对你有帮助的话，请给它一个**star**，并且将它推荐给你周围报考科大计算机的人！
