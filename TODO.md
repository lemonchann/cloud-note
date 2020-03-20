已经完成的任务可以移交到**知识笔记**或者单独建学习文件，并画删除线~~划掉~~



## 技术

### Golang和协程

### 容器技术

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

> Dubbo 是阿里巴巴公司开源的一个Java高性能优秀的服务框架，使得应用可通过高性能的 RPC 实现服务的输出和输入功能，可以和 Spring框架无缝集成。

> Motan是新浪微博开源的一个Java 框架。它诞生的比较晚，起于2013年，2016年5月开源。Motan 在微博平台中已经广泛应用，每天为数百个服务完成近千亿次的调用。

> rpcx是Go语言生态圈的Dubbo， 比Dubbo更轻量实现了Dubbo的许多特性，借助于Go语言优秀的并发特性和简洁语法，可以使用较少的代码实现分布式的RPC服务。

> gRPC是Google开发的高性能、通用的开源RPC框架，其由Google主要面向移动应用开发并基于HTTP/2协议标准而设计，基于ProtoBuf(Protocol Buffers)序列化协议开发，且支持众多开发语言。本身它不是分布式的，所以要实现上面的框架的功能需要进一步的开发。
>
> thrift是Apache的一个跨语言的高性能的服务框架，也得到了广泛的应用，Thrift是Facebook于2007年开发的，它提供多语言的编译功能，通过Thrift的IDL来描述接口函数及数据类型，通过Thrift的编译环境生成各种语言类型的接口文件。

> brpc(baidu-rpc)是百度开发一款远过程调用网络框架。目前该项目已在github上开源，brpc目前被应用于百度公司内部各种核心业务上，其中包括高性能计算和模型训练和各种索引和排序服务，且有超过100万以上个实例是基于brpc工作的。

> Tars 是腾讯根据内部多年使用微服务架构的实践，总结而成的开源项目，仅支持 C++ 语言，目前在腾讯内部应用也非常广泛。

其中关于brpc在知乎有个很好的问题，其中有包括大神戈君(brpc主导者)在内的多个回答，可以帮助我们快速了解brpc框架：[如何评价百度开源的 RPC 框架 brpc？](https://www.zhihu.com/question/65370268)

**tars和brpc是非常不错的开源项目，尤其作为C++程序员很推荐阅读。后面一定要写一下gRPC、brpc、tars，先占个坑。**

### 何为中间件？

[基于中间件/构件的开发](https://yq.aliyun.com/articles/62776)

> 中间件（middleware)是基础软件的一大类，属于可复用软件的范畴。顾名思义，中间件处于操作系统和用户的应用软件的中间。中间件在操作系统、网络和数据库之上，应用软件的下层，总的作用是为处于自己上层的应用软件提供运行和开发的环境，帮助用户灵活、高效地开发和集成复杂的应用软件，中间件是一类软件，中间件不仅要实现互联，还要实现应用之间的互操作；中间件是基于分布式处理的软件，最突出的特点是其网络通信功能。

从这个概念来看，我们平时接触到的绝大部分软件，比如zookeeper，hbase，memcached，RPC框架都可以看做中间件。

分类： **远程过程调用（RPC）中间件** 、 **面向消息的中间件**、 **数据访问中间件**  

[在架构设计里，什么叫做“中间件”]( https://www.coderxing.com/what-is-middleware-for-architecture.html )



### 架构师学什么？



## 读书

### 《高性能MySQL》

### 《大型网站技术架构与核心原理案例分析》

