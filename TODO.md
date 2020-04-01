已经完成的任务可以移交到**知识笔记**或者单独建学习文件，并画删除线~~划掉~~



## 技术

### Golang和协程

### 容器技术

#### RPC框架brpc tars gRPC （有道云笔记有记录）

#### docker

#### k8s

### mongodb和redis差别

### bazel和cmake学习

### elasticity search了解

### lua了解

### redis源码



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

Go语言写的HTTP web服务框架。[中文文档](https://github.com/skyhee/gin-doc-cn)



### [RPC框架](https://mp.weixin.qq.com/s?__biz=MzI1MzYzMTI2Ng==&mid=2247484515&idx=1&sn=217dca00b2b580cbd3da7e9c51b409aa&chksm=e9d0ca2edea743380c23e16ca660e47c74cb23980f8c2379519664eee6c4fe542bdafedf4cba&mpshare=1&scene=1&srcid=0314HxrUfN45bHOyQY3j16tr&sharer_sharetime=1584191704049&sharer_shareid=c71e0673fbaa15e3038063afecc3a033#rd)

#### 常见的RPC框架和各自特点

> Dubbo 是阿里巴巴公司开源的一个Java高性能优秀的服务框架，使得应用可通过高性能的 RPC 实现服务的输出和输入功能，可以和 Spring框架无缝集成。 Apache Dubbo |ˈdʌbəʊ| 是一款高性能、轻量级的开源Java RPC框架，它提供了三大核心能力：面向接口的远程方法调用，智能容错和负载均衡，以及服务自动注册和发现 

> Motan是新浪微博开源的一个Java 框架。它诞生的比较晚，起于2013年，2016年5月开源。Motan 在微博平台中已经广泛应用，每天为数百个服务完成近千亿次的调用。

> rpcx是Go语言生态圈的Dubbo， 比Dubbo更轻量实现了Dubbo的许多特性，借助于Go语言优秀的并发特性和简洁语法，可以使用较少的代码实现分布式的RPC服务。

> gRPC是Google开发的高性能、通用的开源RPC框架，其由Google主要面向移动应用开发并基于HTTP/2协议标准而设计，基于ProtoBuf(Protocol Buffers)序列化协议开发，且支持众多开发语言。本身它不是分布式的，所以要实现上面的框架的功能需要进一步的开发。
>
> thrift是Apache的一个跨语言的高性能的服务框架，也得到了广泛的应用，Thrift是Facebook于2007年开发的，它提供多语言的编译功能，通过Thrift的IDL来描述接口函数及数据类型，通过Thrift的编译环境生成各种语言类型的接口文件。

> brpc(baidu-rpc)是百度开发一款远过程调用网络框架。目前该项目已在github上开源，brpc目前被应用于百度公司内部各种核心业务上，其中包括高性能计算和模型训练和各种索引和排序服务，且有超过100万以上个实例是基于brpc工作的。

>  Tars 是将腾讯内部使用的微服务架构 TAF（Total Application Framework）多年的实践成果总结而成的开源项目。 仅支持 C++ 语言，目前在腾讯内部应用也非常广泛。 

其中关于brpc在知乎有个很好的问题，其中有包括大神戈君(brpc主导者)在内的多个回答，可以帮助我们快速了解brpc框架：[如何评价百度开源的 RPC 框架 brpc？](https://www.zhihu.com/question/65370268)

**tars和brpc是非常不错的开源项目，尤其作为C++程序员很推荐阅读。后面一定要写一下gRPC、brpc、tars，先占个坑。**

#### [zookeeper和dubbo的关系](https://segmentfault.com/a/1190000016349824)

 Dubbo的将注册中心进行抽象，是得它可以外接不同的存储媒介给注册中心提供服务，有ZooKeeper，Memcached，Redis等。  在 Dubbo 官方推荐使用 Zookeeper 就担任了注册中心这一角色。

 ![preview](https://segmentfault.com/img/remote/1460000016349828/view) 



 

### 何为中间件？

[基于中间件/构件的开发](https://yq.aliyun.com/articles/62776)

> 中间件（middleware)是基础软件的一大类，属于可复用软件的范畴。顾名思义，中间件处于操作系统和用户的应用软件的中间。中间件在操作系统、网络和数据库之上，应用软件的下层，总的作用是为处于自己上层的应用软件提供运行和开发的环境，帮助用户灵活、高效地开发和集成复杂的应用软件，中间件是一类软件，中间件不仅要实现互联，还要实现应用之间的互操作；中间件是基于分布式处理的软件，最突出的特点是其网络通信功能。

从这个概念来看，我们平时接触到的绝大部分软件，比如zookeeper，hbase，memcached，RPC框架都可以看做中间件。

分类： **远程过程调用（RPC）中间件** 、 **面向消息的中间件**、 **数据访问中间件**  

[在架构设计里，什么叫做“中间件”]( https://www.coderxing.com/what-is-middleware-for-architecture.html )



### 架构师学什么？

 [**什么是RESTful**](https://www.ruanyifeng.com/blog/2011/09/restful.html) 

#### 服务治理

#### 微服务

[浅谈微服务和服务治理](https://blog.csdn.net/suifeng3051/article/details/53992560)

 微服务架构风格是一种将单个应用程序作为一套小型服务开发的方法，每种应用程序都在自己的进程中运行，并与轻量级机制（通常是HTTP资源API）进行通信。 这些服务是围绕业务功能构建的，可以通过全自动部署机制独立部署。 这些服务的集中管理最少，可以用不同的编程语言编写，并使用不同的数据存储技术。 

[微服务架构选型](https://www.infoq.cn/article/micro-service-technology-stack)

 ![微服务架构技术栈选型手册](https://static001.infoq.cn/resource/image/31/d1/311cb272432eea1b08d9fa45a3094ed1.png) 

 ![微服务架构技术栈选型手册](https://static001.infoq.cn/resource/image/7d/a8/7d7baf3c1e15265d1b576ca9b029a8a8.png) 

#### [篇文章快速理解微服务架构](http://dockone.io/article/3687)

#### 过载保护

> 接口限流、服务降级、服务熔断、服务隔离

#### [DevOps](https://www.redhat.com/zh/topics/devops)

“DevOps”一词是由英文 Development（开发）和 Operations （运维）组合而成， DevOps 是指对企业文化、业务自动化和平台设计等方面进行全方位变革，从而实现迅捷、优质的服务交付，提升企业响应能力和价值。只有通过快速迭代的 IT 服务交付，这一切才能实现。DevOps 可以将传统应用和最新的云原生应用与基础架构彼此相连。 

#### SOA 面向服务的架构  service-oriented architecture 

#### 什么是 Tomcat 

#### 什么是nginx

## 读书

[finy推荐书单](http://mp.weixin.qq.com/s?__biz=MzI5NzY0MjgwOQ==&mid=2247484315&idx=1&sn=ea72622e463d89071591766e29030d66&chksm=ecb0bdcddbc734db1c80e4e10be3c75da6df44fe933515dd004cbd308c1febc9b2f364ac6072&mpshare=1&scene=1&srcid=&sharer_sharetime=1584106135409&sharer_shareid=c71e0673fbaa15e3038063afecc3a033#rd)

### 《高性能MySQL》

### 《web性能权威指南》

### 《大型网站技术架构与核心原理案例分析》

### 《 **微服务架构设计模式** 》

