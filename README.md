## 学习SpringBoot并集成各大框架所记

## 项目构建
```
git clone https://github.com/liaozihong/SpringBoot-Learning.git 
cd SpringBoot-Learning
gradle clean build -x test
```
## 项目介绍

### SpringBoot-ActiveMq
集成ActiveMq，实现点到点发送、广播订阅功能，简单的小实例，未用到Springboot封装的ActiveTemplate，后续打算在写一个利用SpringBoot的ActiveTemplate在写一个demo。  

### SpringBoot-Dubbo-Provider
集成Dubbo的服务提供者，依赖zookeeper。  

### SpringBoot-Dubbo-Consumer
集成Dubbo的服务消费者。

### SpringBoot-Elasticsearch
集成Elasticsearch实现增删改查、分页例子。  
[SpringBoot集成Elasticsearch实现增删改查](https://blog.csdn.net/qq_39211866/article/details/84980416)

### SpringBoot-Elasticsearch-Query
集成Elasticsearch实现中文、拼音分词，以及繁简体过滤，实现可以使用中文、拼音、繁体搜索，并且提供众多搜索类型，如：高亮、聚合。并且提供查看分词结果接口。  
[SpringBoot集成Elasticsearch 进阶，实现 中文、拼音、繁简体转换 搜索](https://blog.csdn.net/qq_39211866/article/details/85178707)

### SpringBoot-Email
集成Email发送各种类型的邮件。  
[SpringBoot 集成 E-mail发送各种类型的邮件
](https://blog.csdn.net/qq_39211866/article/details/84843977)

### SpringBoot-FastDFS
连接FastDFS分布式文件系统，上传文件远程服务器。(包含FastDFS文件系统的搭建)  

### SpringBoot-Jpa-Thymeleaf
集成Jpa 做Crud，并使用Thymeleaf模板显示数据，提供了前后端分离的思路。  
[SpringBoot 集成 Thymeleaf 实现增删改查，实现前后端分离做法
](https://blog.csdn.net/qq_39211866/article/details/84452874)

### Spring-Memcached
集成memcached，内置了一个通用的操作管理类，可快速操作缓存。  
[https://blog.csdn.net/qq_39211866/article/details/84312170](https://blog.csdn.net/qq_39211866/article/details/84312170)   

### SpringBoot-Mongodb 
集成较火的nosql:Mongodb,使用泛型设计了一个通用的crud管理了。写起crud来方便快捷。  

### SpringBoot-Mybatis
集成Mybatis，并使用druid做连接池，配置了druid的监控功能。  

### Spring-Mybatis-Multisource
集成Mybatis，并配置了双数据源，也可直接扩展多数据源。  
[SpringBoot集成Mybatis实现多数据源
](https://blog.csdn.net/qq_39211866/article/details/84843885)

### SpringBoot-Nsq
集成nsq队列，演示了一个生产者与消费者的实例。  

### SpringBoot-RabbitMq
集成RabbitMq，配置了延时队列，死信队列，并且提供了重试机制的设计思想，可做参考。  

### SpringBoot-RateLimiter
集成Guava，利用RateLimiter API，实现限流功能。并且设计了有一个限流注解，能快速对服务进行限流配置。  
[基于Guava的RateLimiter设计常用接口限流功能
](https://blog.csdn.net/qq_39211866/article/details/84312116)

### SpringBoot-Redis-Distributed-Lock
使用Redis+Lua实现分布式锁，附带测试实例。  
[SpringBoot 集成 Redis 实现分布式锁
](https://blog.csdn.net/qq_39211866/article/details/84843861)

### SpringBoot-Redis-Distributed-RedLock
使用Redis官方推荐的Redisson实现分布式锁。   
[SpringBoot 集成Redisson实现分布式锁
](https://blog.csdn.net/qq_39211866/article/details/84843849)

### SpringBoot-WebSocket
集成WebSocket打造一个聊天室。  
[SpringBoot集成WebSocket 打造聊天室
](https://blog.csdn.net/qq_39211866/article/details/84843923)  

### SpringBoot-Zookeeper-Distributed-Lock
使用Zookeeper实现分布式锁。  
[Zookeeper分布式锁](https://blog.csdn.net/qq_39211866/article/details/84844005)

### SpringBoot-Shiro
使用Shiro实现  
```
添加用户注册，用户注销，当前用户显示;  
添加动态验证码验证，记住密码功能;
添加用户权限获取添加Redis缓存管理器，避免每次验证都查询数据库;
添加用户登录错误次数记录，到达特定次数将暂时停用改账号，避免暴力破解，基于redis;
添加单点登录，限定同一时间只能在一处登录，并踢出前一个登录;
添加异步单点登录，同上一条相似;
添加当前在线人数显示，可自己造轮子，做在线人数踢出功能，思路已给出。
```

### SpringBoot-Utils
各项目的依赖模块，存放一些工具类
