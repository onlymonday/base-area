# 云原生与运维

> 后端的"底盘"能力。线上事故排查能力是面试和晋升的硬通货。

## 知识地图

### Docker

- 镜像分层与 Dockerfile 优化
- 容器网络模式
- 容器与虚拟机的区别（namespace / cgroup）

### Kubernetes

- 架构组件与控制平面
- Pod / Deployment / StatefulSet / DaemonSet
- Service 与 Ingress 的实现原理
- 调度机制与资源限制（request / limit）
- 探针（liveness / readiness / startup）

### CI/CD 与发布

- 流水线设计
- 发布策略：滚动、蓝绿、灰度 / 金丝雀
- 回滚方案设计

### 可观测性

- 三大支柱：日志、指标、链路追踪（OpenTelemetry）
- 告警设计与降噪

### Linux 排障套路

- CPU 飙高：top → 线程 → 栈（结合语言工具链）
- 内存问题：OOM、内存泄漏定位
- 磁盘：空间与 IO 瓶颈
- 网络：连接数、TIME_WAIT、丢包排查

## 面试高频考点

1. 容器和虚拟机的区别？
2. K8s 里 Service 的 ClusterIP 是怎么实现的？
3. 线上 CPU 飙高怎么排查？
4. 灰度发布怎么做？出问题怎么快速回滚？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
