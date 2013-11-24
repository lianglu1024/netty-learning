Netty源码导读
====

Netty是Java世界知名的网络应用框架。本系列文章是Netty的源码导读。

## 为什么要读Netty源码？

我认为，一般研究Netty源码出于两个原因：

1. 日常工作中使用到Netty，想要进一步了解；
2. 对Java网络编程感兴趣，想知道如何构建一个高性能网络应用。

另外，Netty的代码组织比较优秀，从中可以学到代码结构组织的方法。

## 这些文章讲什么？

本系列文章的介绍点包括：Netty的设计思想，网络编程的领域知识，以及Netty代码结构的骨干，可能也会包括一些具体场景的应用以及一些特性的分析。

==========

## Netty的架构

### [1.概述](https://github.com/code4craft/netty-learning/blob/master/ch1-overview.md)
### [2.Netty中的buffer](https://github.com/code4craft/netty-learning/blob/master/ch2-buffer.md)
### [3.层层分析Netty中的Channel(上)](https://github.com/code4craft/netty-learning/blob/master/ch3-pipeline.md)
### [4.层层分析Netty中的Channel(下)](https://github.com/code4craft/netty-learning/blob/master/ch4-channel-nio.md) *未完成*
### [5.分门别类讲讲Handler](https://github.com/code4craft/netty-learning/blob/master/ch5-handler.md) *未完成*

## Netty中的特性与细节

### [1.理解Netty中的异步](https://github.com/code4craft/netty-learning/blob/master/detail/ch1-async-in-netty.md) *未完成*

## Netty实战

### [1.构建一个socks proxy](https://github.com/code4craft/netty-learning/blob/master/socks-proxy-by-netty.md)

## 协议：

相关代码遵循Apache V2协议。

文档遵循CC-BYNC协议。

## 贡献：

你可以fork分支，修改后并提交pull request。pull request接受后，我会将你提升为项目commiter。