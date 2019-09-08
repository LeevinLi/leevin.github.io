---
title: 大话设计模式读书笔记-简单工厂模式
date: 2019-09-08 08:27:04
categories:
- 大话设计模式
tags:
- 大话设计模式
---

## 简单工厂模式

+ 概述  
属于创建式模式，它提供了创建对象的一种方式，封住内部的业务，对外围只提供创建操作的对象工厂。

+ 面向对象的优点  
运用面向对象的编程思想，通过封装，继承，多态可降低程序的耦合性，提高程序的可维护，可复用，可扩展性，使得程序更加灵活。


+ UML结构图  
![UML图](/images/uml-simple-factory.png)

+ 实例程序  
计算器加减乘除四种计算方式，通过OperationFactory来创建计算方式。