---
title: Article title
keywords: keyword1, keyword2
desc: description for this article
date: 2022-09-01
---


# Spring

## Bean生命周期

```
Bean 实例化 → 
属性注入 → 
BeanPostProcessor 前置处理 → 
初始化方法（@PostConstruct → InitializingBean → init-method） → 
BeanPostProcessor 后置处理 → 
Bean 就绪 → 
容器关闭 → 
销毁方法（@PreDestroy → DisposableBean → destroy-method）
```

## 作用域对生命周期的影响

Singleton：容器启动时创建（若为懒加载则首次使用时创建），容器关闭时销毁。

Prototype‌：每次请求时创建，销毁由客户端代码或垃圾回收控制（Spring 不管理原型 Bean 的销毁）。

Request：每次 HTTP 请求创建，请求结束销毁。

Session：用户会话期间存在，会话超时或注销时销毁。



# Redis

## Redis数据结构

[Redis 的数据结构总结-腾讯云开发者社区-腾讯云](https://cloud.tencent.com/developer/article/1915694)



# MySQL

## 聚簇索引和非聚簇索引

## 索引失效问题

## 三大日志



# Java

## 垃圾回收算法

### 标记-清理法

### 复制算法

### 标记整理法



## 垃圾回收器

