---
layout: post
title: HikariCP连接管理原理
categories: [java,mysql,connection pool]
description: HikariCP连接池管理原理
keywords: HikariCP, 连接池
---

### 依赖版本

* HikariCP:4.0.3
* mysql-connector-java:5.1.34

### 核心类

* HikariDataSource
* HikariPool
* ConcurrentBag
* PoolEntry
* ProxyFactory

### 获取连接流程

#### 初始化连接池

#### 通过连接池获取连接

##### 连接判活

##### 关闭连接对象

### 连接对象的生成

### 连接池的扩容和缩容

### 连接的回收

### ConcurrentBag

### 监控配置



