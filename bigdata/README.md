# 大数据与实时计算

> 中高级后端 JD 的高频加分项。与 middleware 的消息队列衔接：Kafka 往下游就是这里。

## 知识地图

### 数据仓库

- 分层：ODS / DWD / DWS / ADS，为什么要分层
- 维度建模：星型模型、雪花模型、事实表类型
- 拉链表、缓慢变化维（SCD）

### 批处理（Spark）

- RDD 与 SparkSQL、算子与依赖
- shuffle 机制与调优
- 数据倾斜的定位与解决

### 流处理（Flink）

- 核心模型：Source / Transformation / Sink
- 时间语义：事件时间 / 处理时间，watermark 与乱序
- 状态管理与 checkpoint（exactly-once 的实现）
- 窗口：滚动 / 滑动 / 会话
- 与 Spark Streaming / Storm 的对比

### 数据湖与湖仓一体

- Hudi / Iceberg / Paimon 的定位与取舍
- 湖仓一体解决什么问题

### OLAP 引擎

- ClickHouse / Doris / StarRocks 的选型
- 列存与向量化执行为什么快

### 数据链路与调度

- CDC：Flink CDC / Canal / Debezium
- 调度系统：DolphinScheduler / Airflow
- 离线数仓 vs 实时数仓 vs 流批一体

## 面试高频考点

1. Flink 怎么实现 exactly-once？watermark 解决什么问题？
2. 数仓为什么要分层？分层的代价是什么？
3. 数据倾斜怎么处理？
4. ClickHouse 为什么快？什么场景不适合？
5. 实时数仓和离线数仓的区别？流批一体是什么？

## 目录结构

- `questions/`：面试题
- `articles/`：技术文章
