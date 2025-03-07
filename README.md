# Whale Market - Winter Code -Melvin Test

**From Jiacai Cui**

**Email: 201220014@smail.nju.edu.cn**



## 1 Introduction

![pic01](img/pic01.png)

详细内容见：https://cui-jiacai.gitbook.io/whale-market/

![pic19](img/pic19.png)



## 2 Tutorial

### 2.1 功能要求总览

- 用户功能：
    - 登陆、注册、注销
    - 买家功能
        - 查看、搜索商品
        - 购买商品
    - 卖家功能
        - 商品的发布、下架
        - 查看已发布商品
        - 修改商品信息
    - 查看历史订单（只能查看自己的订单）
    - 个人信息查看、修改
- 管理员功能
    - 登陆、注销
    - 查看、搜索、下架商品
    - 查看所有订单
    - 查看、删除用户
- 系统功能
    - 程序结束后再次打开程序，原本的数据不能丢失

### 2.2 具体功能示例

> 以下部分取自2021春南大程设实验课程ppt，可做基本功能的参照使用。

#### 2.2.1 管理员功能简介

![pic02](img/pic02.png)

![pic03](img/pic03.png)

![pic04](img/pic04.png)

![pic05](img/pic05.png)

![pic06](img/pic06.png)

#### 2.2.2 用户功能简介

![pic07](img/pic07.png)

![pic08](img/pic08.png)

![pic09](img/pic09.png)

![pic10](img/pic10.png)

![pic11](img/pic11.png)

![pic12](img/pic12.png)

#### 2.2.3 数据存储示例

![pic13](img/pic13.png)

![pic14](img/pic14.png)

![pic15](img/pic15.png)

![pic16](img/pic16.png)

### 2.3 其他要求

![pic17](img/pic17.png)

### 2.4 阶段划分

| 阶段            | 任务                                                         |
| --------------- | ------------------------------------------------------------ |
| Phase1(为期7天) | 设计项目，用ppt形式展示项目整体的思路和实现上的想法，并初步实现部分功能 |
| Phase2(为期7天) | 完成基本功能的实现，保证功能无错误以及程序具有一定的鲁棒性和用户友好的界面 |
| Phase3(为期7天) | 自行设计拓展功能，可以参考某宝的功能（比如与商家留言沟通，商品打分，GUI界面等等），为自己的软件设计一个用户手册。 |
| Phase4(选做)    | 阅读参考代码，学习多模块项目的设计，以及一些代码设计上的巧妙之处。 |

> 为了使代码具有教学意义，我写本项目的时候覆盖到了宏定义、文件包含、函数指针、文件读写、模块通信等许多在程设基础课上一带而过的内容，还是值得一看的。



## 3 Reference

参考代码仓库地址：https://github.com/201220014/WhaleMarket

框架代码仓库地址：https://github.com/201220014/WhaleMarket-Framework

### 3.1 关于参考代码的效果

这是参考代码在命令行运行的效果：

![pic18](img/pic18.png)



### 3.2 对于参考代码的要求

在前2个阶段尽量别看，**自己动手，从0开始**。

到最后一个阶段的时候，可以比较一下参考实现和自己的实现之间有何区别，又有何优劣之处，以及思考一下为什么我会这样设计，大抵是会有所启发的。
