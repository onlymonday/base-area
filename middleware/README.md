# 中间件

> 消息队列是必考项，搜索引擎和网关是加分项。缓存见 database/redis，不在此重复。

## 知识地图

### 消息队列

- 选型：Kafka / RocketMQ / RabbitMQ 的定位与取舍
- 消息不丢：生产端确认、存储端刷盘与副本、消费端手动 ACK
- 消息不重复：消费幂等设计
- 顺序消息：分区有序 vs 全局有序
- 消息积压的应急处理
- 事务消息、延迟消息的实现原理
- Kafka 为什么快（顺序写、零拷贝、批量）

### 搜索引擎（Elasticsearch）

- 倒排索引原理
- 写入流程与段（segment）合并
- 近实时（NRT）搜索
- 深分页问题（from+size / scroll / search_after）

### 网关

- 路由、鉴权、限流、灰度的统一收口
- Spring Cloud Gateway / APISIX

### 注册中心与配置中心

- 服务发现与健康检查
- Nacos / ZooKeeper / Consul 的 CAP 取舍
- 配置热更新机制

### 任务调度

- 分布式调度：分片广播、失败转移、幂等
- xxl-job / PowerJob 的设计思路

## 面试高频考点

1. 如何保证消息不丢、不重、有序？
2. Kafka 为什么这么快？
3. 消息积压了几百万条，怎么处理？
4. ES 深分页为什么慢，怎么解决？
5. Nacos 和 ZooKeeper 做注册中心的区别？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
