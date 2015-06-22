# C-Mini-Compiler 

##<a name = "index"/>目录
* [背景介绍](#背景介绍)
* [项目介绍](#项目介绍)
* [使用说明](#使用说明)
* [模块介绍](#模块介绍)
    * [词法分析器](#词法分析器)
    * [语法分析器](#语法分析器)
    * [语义分析器](#语义分析器)
* [其他](#其他)

<a name = "背景介绍"/>
#背景介绍
　令人吃惊的是，在哪种字节顺序是合适的这个问题上，人们表现得非常情绪化。实际上术语“little endian”（小端）和“big endian”（大端）出自Jonathan Swift的《格利佛游记》一书，其中交战的两个派别无法就应该从哪一端打开一个半熟的鸡蛋达成一致。因此，争论沦为关于社会政治的争论。只要选择了一种规则并且始终如一的坚持，其实对于哪种字节排序的选择都是任意的。

	去年上课学了编译原理,这门课的理论太多了,而且很难,学得是云里雾里.但是很多大神说学了编译原理之后最好能够实际东说做一个编译器,这样能够对能力有很大的提升.于是就下定决心为了写一个编译器来重新学习编译原理,开始找公开课,买书,编译器的开发就这样开始了.
   刚开始买的是龙书,这本书太难了,看得那过程真实痛苦.又到网上找了本<编译原理与实践>,这本书里面有一个实际的小型编译器.我发现实际的编译器开发工作并没有想象中的那么复杂,有些复杂的理论并不是必须的.里面还有一个C-Mini的编译器项目,于是便按照这里面的项目要求来写编译器. 
   当然,我现在实现的这个编译器比书本里面的项目进行了一定的扩展

<a name = "项目介绍"/>
##项目介绍
支持整型, 浮点型, 字符型, 字符串类型关键字有if, else, while, return, void, int, float, const, string

<a name = "使用说明/">
## 使用说明
使用vs2013编译

<a name = "模块介绍"/>
## 模块介绍

<a name = "词法分析器"/>
### 词法分析器
状态转移图

<a name = "语法分析器"/>
### 语法分析器
语法树

<a name = "语义分析器"/>
### 语义分析器
类型检查

<a name = "其他"/>
## 其他
后续工作

