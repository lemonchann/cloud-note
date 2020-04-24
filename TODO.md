已经完成的任务可以移交到**知识笔记**或者单独建学习文件，并画删除线~~划掉~~



## 技术

### Golang和协程

1. https://tour.go-zh.org/ go语言之旅 官方入门教程。边打边学。强力推荐
2. https://books.studygolang.com/gopl-zh/ go语言圣经。
3. https://chai2010.gitbooks.io/advanced-go-programming-book/content/ go语言高级编程 。针对特定领域感兴趣的看。
4. https://gfw.go101.org/article/101.html go语言101.一些语法底层实现。

---



1.入门
go语言圣经 http://shouce.jb51.net/gopl-zh/index.html
学习基本语法和go语言的一些特性，C-like的语言相信一两天就可以入门，看的过程中有不太理解的地方记录下来就行。

2.练习
go by example https://gobyexample.com/
强烈推荐看的过程中自己也写一遍，想象这些例子都使用了哪些golang的特性，例子也不多但都实用。

3.实战
《go语言实战》看看项目中怎样使用golang

4.高并发
《go高并发编程》 介绍go的高并发原理，教你怎样一步一步写出高性能的并发程序

5.网络编程
《go web编程》比较繁琐，但会比较详细地介绍golang的网络编程实现，包括一些原生库设计和实现的原理。

---



 使用示例：https://gobyexample.com/
书籍PDF：https://github.com/KeKe-Li/book#golang
Go 开发者路线图：https://github.com/Quorafind/golang-developer-roadmap-cn
Go 高分优秀中文项目：https://github.com/kon9chunkit/GitHub-Chinese-Top-Charts#Go
在学习过程中收藏的，供参考~ 

---



### 容器技术

#### RPC框架brpc tars gRPC （有道云笔记有记录）

#### docker

#### redis安装使用  桌面客户端redisclient-win32.x86.2.0

#### k8s

### 数据结构

#### 跳表

#### 红黑树

### mongodb和redis差别

### bazel和cmake学习

### elasticity search了解

### lua了解

### redis源码

### linux内存管理

### slab是什么？

### Python的库学习去哪查资料？官网？

### leetCode刷算法是按类别刷，还是剑指offer挨个刷？

### 消息队列

#### MQTT

 **MQTT**[[1\]](https://zh.wikipedia.org/wiki/MQTT#cite_note-1)**消息队列遥测传输**(Message Queuing Telemetry Transport)是[ISO 标准](https://zh.wikipedia.org/wiki/国际标准化组织)(ISO/IEC PRF 20922)[[2\]](https://zh.wikipedia.org/wiki/MQTT#cite_note-ISO-2)下基于[发布 (Publish)/订阅 (Subscribe)](https://zh.wikipedia.org/wiki/发布/订阅) 范式的消息协议，可视为“资料传递的桥梁”[[3\]](https://zh.wikipedia.org/wiki/MQTT#cite_note-3)它工作在 [TCP/IP协议族](https://zh.wikipedia.org/wiki/TCP/IP协议族)上，是为硬件性能低下的远程设备以及网络状况糟糕的情况下而设计的[发布/订阅](https://zh.wikipedia.org/wiki/发布/订阅)型消息协议  

#### kafka

 **Kafka**是由[Apache软件基金会](https://zh.wikipedia.org/wiki/Apache软件基金会)开发的一个[开源](https://zh.wikipedia.org/wiki/开源)[流处理](https://zh.wikipedia.org/wiki/流处理)平台，由[Scala](https://zh.wikipedia.org/wiki/Scala)和[Java](https://zh.wikipedia.org/wiki/Java)编写。该项目的目标是为处理实时数据提供一个统一、高吞吐、低延迟的平台。其持久化层本质上是一个“**按照分布式事务日志架构的大规模发布/订阅消息队列** .

 Jay Kreps似乎已经将它以作家[弗朗茨·卡夫卡](https://zh.wikipedia.org/wiki/弗朗茨·卡夫卡)命名。Kreps选择将该系统以一个作家命名是因为，它是“一个用于优化写作的系统”，而且他很喜欢卡夫卡的作品。

### web后台框架

####  [OpenResty](https://openresty.org/cn/)  

 OpenResty® 是一个基于 [Nginx](https://openresty.org/cn/nginx.html) 与 Lua 的高性能 Web 平台，其内部集成了大量精良的 Lua 库、第三方模块以及大多数的依赖项。用于方便地搭建能够处理超高并发、扩展性极高的动态 Web 应用、Web 服务和动态网关。 

[Gin](https://github.com/gin-gonic/gin)

Go语言写的 HTTP web服务框架。[中文文档](https://github.com/skyhee/gin-doc-cn)

#### zookeeper

####  Consul  



 

### 何为中间件？

[基于中间件/构件的开发](https://yq.aliyun.com/articles/62776)

> 中间件（middleware)是基础软件的一大类，属于可复用软件的范畴。顾名思义，中间件处于操作系统和用户的应用软件的中间。中间件在操作系统、网络和数据库之上，应用软件的下层，总的作用是为处于自己上层的应用软件提供运行和开发的环境，帮助用户灵活、高效地开发和集成复杂的应用软件，中间件是一类软件，中间件不仅要实现互联，还要实现应用之间的互操作；中间件是基于分布式处理的软件，最突出的特点是其网络通信功能。

从这个概念来看，我们平时接触到的绝大部分软件，比如zookeeper，hbase，memcached，RPC框架都可以看做中间件。

分类： **远程过程调用（RPC）中间件** 、 **面向消息的中间件**、 **数据访问中间件**  

[在架构设计里，什么叫做“中间件”]( https://www.coderxing.com/what-is-middleware-for-architecture.html )

### 线程池c++开源实现？

### 架构师学什么？

 [**什么是RESTful**](https://www.ruanyifeng.com/blog/2011/09/restful.html) 

#### 服务治理

#### 微服务

[浅谈微服务和服务治理](https://blog.csdn.net/suifeng3051/article/details/53992560)

 微服务架构风格是一种将单个应用程序作为一套小型服务开发的方法，每种应用程序都在自己的进程中运行，并与轻量级机制（通常是HTTP资源API）进行通信。 这些服务是围绕业务功能构建的，可以通过全自动部署机制独立部署。 这些服务的集中管理最少，可以用不同的编程语言编写，并使用不同的数据存储技术。 

[微服务架构选型](https://www.infoq.cn/article/micro-service-technology-stack)

 ![微服务架构技术栈选型手册](https://static001.infoq.cn/resource/image/31/d1/311cb272432eea1b08d9fa45a3094ed1.png) 

 ![微服务架构技术栈选型手册](https://static001.infoq.cn/resource/image/7d/a8/7d7baf3c1e15265d1b576ca9b029a8a8.png) 

#### [一篇文章快速理解微服务架构](http://dockone.io/article/3687)

#### 服务容错

[雪崩](https://www.cnblogs.com/li-peng/p/10997140.html)、超时、接口限流、服务降级、服务熔断、服务隔离

#### [DevOps](https://www.redhat.com/zh/topics/devops)

“DevOps”一词是由英文 Development（开发）和 Operations （运维）组合而成， DevOps 是指对企业文化、业务自动化和平台设计等方面进行全方位变革，从而实现迅捷、优质的服务交付，提升企业响应能力和价值。只有通过快速迭代的 IT 服务交付，这一切才能实现。DevOps 可以将传统应用和最新的云原生应用与基础架构彼此相连。 

#### SOA 面向服务的架构  service-oriented architecture 

#### 什么是 Tomcat 

#### 什么是nginx

#### 什么是netty

#### 什么是WebSocket

#### 什么是k8s



 https://jimmysong.io/kubernetes-handbook/   Kubernetes Handbook——Kubernetes中文指南/云原生应用架构实践手册

[Kubernetes](https://kubernetes.io/)是Google基于[Borg](https://research.google.com/pubs/pub43438.html)开源的容器编排调度引擎，作为[CNCF](https://cncf.io/)（Cloud Native Computing Foundation）最重要的组件之一，它的目标不仅仅是一个编排系统，而是提供一个规范，可以让你来描述集群的架构，定义服务的最终状态，Kubernetes可以帮你将系统自动地达到和维持在这个状态。**Kubernetes作为云原生应用的基石**，相当于一个云操作系统，其重要性不言而喻。

云原生技术有利于各组织在公有云、私有云和混合云等新型动态环境中，构建和运行可弹性扩展的应用。云原生的代表技术包括**容器**、**服务网格**、**微服务**、**不可变基础设施**和**声明式API**。这些技术能够构建容错性好、易于管理和便于观察的松耦合系统。结合可靠的自动化手段，云原生技术使工程师能够轻松地对系统作出频繁和可预测的重大变更。——CNCF（云原生计算基金会）。



## 读书

[finy推荐书单](http://mp.weixin.qq.com/s?__biz=MzI5NzY0MjgwOQ==&mid=2247484315&idx=1&sn=ea72622e463d89071591766e29030d66&chksm=ecb0bdcddbc734db1c80e4e10be3c75da6df44fe933515dd004cbd308c1febc9b2f364ac6072&mpshare=1&scene=1&srcid=&sharer_sharetime=1584106135409&sharer_shareid=c71e0673fbaa15e3038063afecc3a033#rd)

### 《高性能MySQL》

### 《web性能权威指南》

### 《大型网站技术架构与核心原理案例分析》

### 《 **微服务架构设计模式** 》

### 《 深入理解LINUX内核 》

