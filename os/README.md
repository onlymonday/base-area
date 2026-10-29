# 操作系统

> IO 和内存是后端面试的常客，epoll 和零拷贝几乎是标配考题。

## 知识地图

### 进程与线程

- 进程 / 线程 / 协程的区别与适用场景
- 上下文切换的代价
- 进程间通信（IPC）：管道、共享内存、信号、socket
- 调度算法与线程模型

### 内存管理

- 虚拟内存、页表与 MMU
- 缺页中断
- malloc 底层（brk / mmap）
- 内存泄漏的排查思路

### IO 模型

- BIO / NIO / AIO
- select / poll / epoll 的区别与 epoll 高效的原因（红黑树 + 就绪链表）
- Reactor / Proactor 模型
- 零拷贝：sendfile、mmap，解决了什么问题
- 直接内存与堆外内存

### 其他

- 中断与系统调用
- 文件系统与磁盘 IO（page cache、fsync）

## 面试高频考点

1. 进程和线程的区别？什么时候用多进程、什么时候用多线程？
2. select / poll / epoll 的区别？epoll 为什么高效？
3. 零拷贝是什么？Kafka 和 Redis 里哪里用到了？
4. 虚拟内存的作用是什么？
5. 线上内存泄漏怎么排查？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
