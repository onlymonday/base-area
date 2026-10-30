# base-area

后端开发人员的技术根据地：沉淀技术面试题与深度技术文章，开源共建，共同提高。

## 这是什么

- **面试题**：一题一文件，包含题目、难度、标签、分层答案与常见追问，复习时可以自测
- **技术文章**：围绕同一知识体系的深度长文，把面试题背后的原理讲透

两者共用一套主题目录，形成「考点 → 原理 → 文章深挖」的学习闭环。

## 目录总览

| 目录 | 内容 |
| ---- | ---- |
| [database](database/) | 数据库：MySQL、Redis、MongoDB、分库分表 |
| [ai](ai/) | AI 工程：LLM 应用、RAG、Agent、Prompt、推理与微调 |
| [system-design](system-design/) | 系统设计题：秒杀、短链、Feed 流等经典场景 |
| [distributed](distributed/) | 分布式：一致性协议、分布式事务/锁/ID、RPC |
| [middleware](middleware/) | 中间件：消息队列、搜索引擎、网关、注册中心 |
| [bigdata](bigdata/) | 大数据与实时计算：Flink、Spark、数仓、数据湖、OLAP |
| [network](network/) | 网络协议：TCP、HTTP/HTTPS、QUIC |
| [os](os/) | 操作系统：进程线程、内存管理、IO 模型 |
| [language](language/) | 语言基础：Java、Go、Python 等 |
| [architecture](architecture/) | 架构设计：微服务、高可用、性能优化 |
| [dsa](dsa/) | 数据结构与算法：高频手撕、刷题路线 |
| [engineering](engineering/) | 工程素养：测试、重构、Code Review、Git、AI 辅助编程 |
| [devops](devops/) | 云原生与运维：Docker、K8s、CI/CD、线上排障 |
| [security](security/) | 安全：Web 攻防、加密、认证鉴权 |
| [career](career/) | 面试软技能与职业发展：简历、项目深挖、谈薪、晋升 |

每个模块的 README 提供该领域的知识地图与面试高频考点，建议从这里开始阅读。

## 如何使用

- **备战面试**：打开目标模块 → 过一遍「面试高频考点」→ 进 `questions/` 自测 → 答不好的追到 `articles/` 深挖
- **系统学习**：按模块 README 的知识地图查漏补缺
- **写作输出**：按贡献规范写下你的理解，教是最好的学

## 如何贡献

欢迎提 PR！请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)，内容请使用对应模板：

- [面试题模板](docs/templates/question-template.md)
- [文章模板](docs/templates/article-template.md)

## 约定

- 内容以中文为主，代码与术语保留英文
- 一题一文件 / 一文一文件，文件名使用中文（可含英文缩写，不用空格）
- 新增内容后请在所在目录的 README 索引表中登记一行

## License

本仓库内容采用 [CC BY-SA 4.0](LICENSE)（署名-相同方式共享 4.0 国际）协议授权：转载或改编需署名，并以相同协议共享。
