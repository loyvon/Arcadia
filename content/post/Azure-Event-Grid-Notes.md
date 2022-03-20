---
title: "Azure Event Grid学习笔记"
date: 2022-03-13T02:37:52+08:00
Description: ""
Tags: ["Event driven"]
Categories: ["Cloud Computing"]
DisableComments: false
---

# 关于

事件驱动(Event-driven)是一个在云计算领域越来越广泛应用的模式。我们可以设计不同的trigger，然后当这些trigger对应的条件满足时，trigger一个特定的事件。Event grid是专门为这类场景而设计的，也就是为了让开发者访问云基础架构产生的事件以及其他的自定义的事件。

这项技术之外，有哪些技术也在做类似的事情呢？

AWS的SNS就是一个类似的技术。和SNS不一样的地方在于，SNS会将消息发送给每一个subscriber，Event grid则让cusumer可以选择过滤过的topic。

# 典型架构

![架构](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/media/serverless-application-architectures-using-event-grid.png)

# 参考
https://thenewstack.io/closer-look-azure-event-grid/