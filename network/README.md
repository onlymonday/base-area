# 网络协议

> 面试必问，且区分度极高——背结论和懂原理的人两分钟就能看出来。

## 知识地图

### TCP

- 三次握手 / 四次挥手：为什么是这个次数、半连接队列与 SYN Flood
- TIME_WAIT 与 CLOSE_WAIT 过多的排查
- 重传：超时重传、快速重传、SACK
- 滑动窗口与流量控制
- 拥塞控制：慢启动、拥塞避免、快速重传、快速恢复
- 粘包 / 拆包问题
- TCP keepalive 与心跳

### UDP 与 QUIC

- UDP 的定位与使用场景
- QUIC：0-RTT、多路复用、基于 UDP 的原因

### HTTP

- HTTP/1.1 → HTTP/2 → HTTP/3 的演进（队头阻塞的解决）
- HTTPS / TLS 握手流程、证书校验
- 常见状态码、Cookie / Session / Token

### 网络层与基础设施

- IP、DNS 解析全流程
- CDN 原理
- 从输入 URL 到页面展示的全链路（经典串讲题）

## 面试高频考点

1. 为什么是三次握手、四次挥手？
2. TIME_WAIT 过多怎么排查和解决？
3. HTTPS 握手过程？如何防止中间人攻击？
4. HTTP/2 多路复用解决了什么问题？HTTP/3 又解决了什么？
5. TCP 粘包怎么处理？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
