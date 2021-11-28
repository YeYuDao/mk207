# mk207
Java并发编程高阶技术-高性能并发框架源码解析与实战
Java并发编程高阶技术-高性能并发框架源码解析与实战
[![下载地址](https://img.mukewang.com/szimg/5fce02c3092ca28f05400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程介绍 

#### 什么是Disruptor？它一个高性能的异步处理框架，号称“单线程每秒可处理600W个订单”的神器，本课程目标：彻底精通一个如此优秀的开源框架，面试秒杀面试官。本章会带领小伙伴们先了解课程大纲与重点，然后模拟千万，亿级数据进行压力测试。让大家感性认知到Disruptor的强大。...
1-1 课前必读（不看会错过一个亿）

1-2 课程导学 (13:02)

1-3 并发编程框架Disruptor与BlockingQueue压力测试性能对比 (15:42)


### 第2章 并发编程框架核心讲解

#### 本章带大家学习并发编程框架的基本使用与API，并介绍其内部各种组件的原理和运行机制。从而为后面的深入学习打下坚实的基础。如果对Disruptor还不够了解，这里为你送上一篇文章：https://www.imooc.com/article/74619?tdsourcetag=s_pcqq_aiomsg ...
2-1 本章导航 (02:22)

2-2 并发编程框架-QuickStart-基础元素工厂类 (11:30)

2-3 并发编程框架-QuickStart-消费端事件处理器 (02:44)

2-4 并发编程框架-QuickStart-构建Disruptor实例 (14:30)

2-5 并发编程框架-QuickStart-生产者组件投递数据 (22:03)

2-6 并发编程框架Disruptor-核心机制-生产消费模型 (04:26)

2-7 并发编程框架Disruptor-仍芝麻与捡芝麻小故事 (09:42)

2-8 并发编程框架Disruptor-核心-RingBuffer (04:32)

2-9 并发编程框架Disruptor-核心-Sequence、Sequencer、SequenceBarrier (07:07)

2-10 并发编程框架Disruptor-核心-WaitStrategy消费者等待策略 (13:01)

2-11 并发编程框架Disruptor-核心-EventProcessor，WorkProcessor等 (04:47)

2-12 并发编程框架Disruptor-核心概念整体图解 (06:01)

2-13 本章小结 (05:00)


### 第3章 并发编程框架高级特性讲解

#### 本章首先带大家分析互联网大厂核心链路的难点和复杂业务逻辑，以及中台服务等概念，然后带大家掌握并发编程框架disruptor的高级特性，包括串并行化操作，菱形操作，多边形操作与底层代码深度解析，多生产者多消费者模型实战应用等。让大家有更加深入的理解。 ...
3-1 本章导航 (01:37)

3-2 互联网大厂核心链路方案详解-1 (17:25)

3-3 互联网大厂核心链路方案详解-2 (16:55)

3-4 串、并行操作实战应用-1 (27:20)

3-5 串、并行操作实战应用-2 (18:54)

3-6 菱形操作 (09:22)

3-7 多边形操作与底层代码深度解析 (20:46)

3-8 多生产者多消费者实战应用-1 (18:56)

3-9 多生产者多消费者实战应用-2 (19:45)

3-10 多生产者多消费者实战应用-3 (12:15)

3-11 多生产者多消费者实战应用-4 (13:58)

3-12 本章小结 (02:43)


### 第4章 并发编程深入学习与面试精讲

#### 本章会为大家讲解并发编程核心技术点，面试考点，分析AQS架构，并对底层代码深度讲解与剖析，让小伙伴们掌握并发编程核心，从容应对实际工作与面试，同时也是为了下一章无锁并行计算框架源码分析做好铺垫。
4-1 本章导航 (02:37)

4-2 并发编程面试-并发类容器核心 (12:57)

4-3 并发编程面试-Volatile与内存分析 (09:57)

4-4 并发编程面试-Atomic系列类与UnSafe (09:21)

4-5 并发编程面试-J.U.C常用工具类 (06:34)

4-6 并发编程面试-AQS各种锁 (13:18)

4-7 并发编程面试-线程池最佳使用指南 (21:19)

4-8 并发编程面试-AQS架构核心 (06:07)

4-9 并发编程面试-ReentrantLock底层原理分析 (02:18)

4-10 并发编程面试-ReentrantLock底层源码深度解析-1 (16:26)

4-11 并发编程面试-ReentrantLock底层源码深度解析-2 (12:21)

4-12 并发编程面试-CountDownLatch底层原理分析 (02:03)

4-13 本章小结 (01:27)


### 第5章 并发编程框架底层源码深度分析

#### 本章是课程的重难点，通过本章的学习大家会深度掌握并发编程框架架构，学习其性能爆表的优化手段与底层源码&机制，包括内存预加载，消除伪共享，算法核心与各种等待策略分析，最后为大家分享框架内核EventProcessor底层机制，让小伙伴们真正精通一个优秀的开源框架。...
5-1 本章导航 (02:15)

5-2 并发编程框架Disruptor-整体架构UML类图分析 (10:59)

5-3 并发编程框架Disruptor-为何它的底层性能如此牛掰 (01:58)

5-4 并发编程框架Disruptor-数据结构设计原理与底层源码深度分析 (14:56)

5-5 并发编程框架Disruptor-单线程写核心架构思想 (04:40)

5-6 并发编程框架Disruptor-系统级别内存屏障实现 (04:09)

5-7 并发编程框架Disruptor-填充缓存行消除伪共享机制来提升性能 (10:36)

5-8 并发编程框架Disruptor-序号栅栏机制底层代码深度分析-1 (15:53)

5-9 并发编程框架Disruptor-序号栅栏机制底层代码深度分析-2 (10:20)

5-10 并发编程框架Disruptor-序号栅栏机制底层代码深度分析-3 (22:11)

5-11 WaitStrategy等待策略底层源码深度分析 (17:58)

5-12 EventProcessor核心架构设计与底层源码深度分析 (16:22)

5-13 本章小结 (06:57)


### 第6章 Netty整合并发编程框架Disruptor实战百万长链接服务构建 

#### 并发编程框架与netty整合实战，实现承载百万级别长链接应用，并手把手一步步接触netty框架的最佳使用与TCP网络通信内部机制，封装并发编程框架disruptor基础组件，嵌入到netty中，进行最佳实战应用。
6-1 本章导航 (03:31)

6-2 Disruptor与Netty整合实现百万长链接接入_环境构建 (13:41)

6-3 Disruptor与Netty整合-服务端代码最佳实现-1 (16:12)

6-4 Disruptor与Netty整合-服务端代码最佳实现-2 (13:28)

6-5 Disruptor与Netty整合-服务端代码最佳实现-3 (10:22)

6-6 Disruptor与Netty整合-客户端代码最佳实现-1 (14:05)

6-7 Disruptor与Netty整合-客户端代码最佳实现-2 (13:02)

6-8 Disruptor与Netty整合-客户端代码最佳实现-3 (12:09)

6-9 Netty的高性能之道核心问题分析-异步化处理业务 (06:40)

6-10 Disruptor核心池化封装实现-1 (07:39)

6-11 Disruptor核心池化封装实现-2 (14:03)

6-12 Disruptor核心池化封装实现-3 (18:35)

6-13 高性能服务端与客户端落地实现承载百万级连接接入-1 (13:59)

6-14 高性能服务端与客户端落地实现承载百万级连接接入-2 (11:17)


### 第7章 分布式统一ID生成服务架构设计

#### 本章将对分布式统一ID生成服务的架构设计进行讲解，大家可以了解各种ID生成规则，在高并发下zookeeper与redis分布式锁的问题与弊端，主流ID生成方案，ntp时间回调问题。最后会进行分布式统一ID生成服务架构设计思路详解
7-1 统一ID生成策略_简单生成策略 (05:22)

7-2 统一ID生成策略_业务规则策略 (11:02)

7-3 统一ID生成策略_Zookeeper和Redis的方案在高并发下暴露的问题 (08:51)

7-4 业界主流的分布式高并发ID生成规则方案 (07:00)

7-5 高并发下分布式ID生成策略经典NTP问题解读 (07:24)

7-6 分布式统一ID生成服务系统架构设计讲解 (05:50)

7-7 本章小结 (01:47)


### 第8章 课程总结

#### 本章带大家回顾课程知识重点，最后祝小伙伴们都能获取高薪offer。我在课程问答区等着与大家进一步交流。有问题欢迎大家到课程问答区提问。
8-1 课程总结与回顾 (04:48)


[下载地址](https://51xueit.vip "下载地址")
