# 分布式

> 从单体走向分布式的所有代价都在这里：一致性、事务、锁、ID、通信。

## 知识地图

### 理论基础

- CAP 定理与 BASE 理论
- 一致性协议：Paxos、Raft、ZAB
- Quorum 机制（W + R > N）

### 分布式事务

- 2PC / 3PC 及其缺陷
- TCC：空回滚、悬挂、幂等三大问题
- Saga、本地消息表、事务消息（RocketMQ）
- 最大努力通知

### 分布式锁

- Redis（setnx + Lua、Redisson 看门狗）、ZooKeeper、etcd 三方对比
- 锁续期、可重入、RedLock 争议

### 分布式 ID

- 雪花算法与时钟回拨
- 号段模式（Leaf）
- UUID 为什么不适合做主键

### 数据分片与路由

- 一致性哈希
- 哈希槽（Redis Cluster）

### RPC

- 序列化协议对比
- Dubbo / gRPC 架构
- 超时、重试与幂等设计

## 面试高频考点

1. 讲讲 Raft 的选举和日志复制
2. TCC 的空回滚和悬挂怎么解决？
3. 分布式锁为什么需要看门狗？Redis 和 ZooKeeper 实现的锁有什么区别？
4. 雪花算法时钟回拨怎么办？
5. 什么场景该用本地消息表而不是 TCC？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
