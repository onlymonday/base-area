# 语言基础

> 按语言建子目录（`java/`、`go/`、`python/` 等），子目录内同样分 `questions/` 与 `articles/`。

## 知识地图

### Java（java/）

- 基础：== 与 equals、hashCode 约定、String 不可变、深浅拷贝
- 集合：ArrayList / LinkedList、HashMap 原理（hash、扩容、树化）、ConcurrentHashMap
- 并发：JMM 与 happens-before、volatile、synchronized 锁升级、AQS、线程池参数与执行流程、ThreadLocal 内存泄漏
- JVM：内存区域、对象创建与布局、GC 算法与收集器（CMS / G1 / ZGC）、类加载与双亲委派、OOM 排查

### Go（go/）

- goroutine 与 GMP 调度模型
- channel 的底层实现与使用陷阱
- slice / map 底层结构、扩容
- GC（三色标记）、defer / panic / recover

### Python（python/）

- GIL 与多线程的真实并行度
- 装饰器、生成器、上下文管理器

## 面试高频考点

1. HashMap 的 put 流程和扩容机制？为什么线程不安全？
2. 线程池的核心参数？任务提交流程？
3. synchronized 和 ReentrantLock 的区别？
4. GMP 调度模型？
5. channel 在什么情况下会死锁？

## 目录结构

- `java/`、`go/`、`python/`……每语言一个子目录
- 子目录内：`questions/` 面试题，`articles/` 技术文章
