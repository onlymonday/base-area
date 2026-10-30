# AI 工程

> 传统后端 + AI 应用是当前最明显的技能溢价方向。本模块关注工程落地，不卷论文。

## 知识地图

### LLM 应用开发

- Transformer 基础结构、注意力机制（面试会问，但不用会推导）：[注意力机制的工程直觉](questions/注意力机制的工程直觉.md)
- Token、上下文窗口、温度等核心参数：[token 与上下文窗口](questions/token与上下文窗口.md)
- Function Calling / 结构化输出：[Function Calling 与结构化输出](questions/FunctionCalling与结构化输出.md)
- 效果评估：如何量化一个 LLM 应用的好坏：[用 LLM 当裁判可靠吗](questions/LLMasJudge可靠吗.md)、[Prompt 怎么做版本管理和评测](questions/Prompt的版本管理与评测.md)
- 幻觉是什么、工程上怎么缓解：[幻觉的工程缓解](questions/幻觉的工程缓解.md)
- 成本控制：[LLM 应用的成本怎么控制](questions/LLM应用成本怎么控.md)

### RAG（检索增强生成）

- 文档加载与切分（chunking 策略）：[切分策略怎么影响召回](questions/切分策略怎么影响召回.md)
- Embedding 与向量检索、混合检索（BM25 + 向量）：[向量检索为什么快](questions/向量检索为什么快.md)、[为什么常用混合检索](questions/混合检索为什么必要.md)
- 重排（rerank）与引用溯源：见文章 [RAG 全链路每一环丢多少分](articles/RAG全链路每一环丢多少分.md)
- 效果评估与常见优化手段：[RAG 效果差从哪些环节排查](questions/RAG效果差怎么排查.md)

### Agent

- 工具调用与规划（ReAct 等）：[Agent 和普通工作流的区别](questions/Agent和普通工作流的区别.md)
- 记忆管理：短期上下文与长期记忆：[Agent 的记忆是怎么分层的](questions/Agent记忆怎么分层.md)
- 多 Agent 协作：[什么时候需要多 Agent](questions/多Agent什么时候需要.md)
- MCP 等协议与工具生态：[MCP 解决了什么问题](questions/MCP解决什么问题.md)

### Prompt 工程

- Few-shot、思维链（CoT）：[Few-shot 和 CoT 什么时候用](questions/FewShot和CoT什么时候用.md)
- 结构化输出约束：[Function Calling 与结构化输出](questions/FunctionCalling与结构化输出.md)
- Prompt 的版本管理与评测：[Prompt 怎么做版本管理和评测](questions/Prompt的版本管理与评测.md)

### 模型推理与微调

- 推理优化（KV Cache、量化、批处理、vLLM 等）：[KV Cache 为什么省算力](questions/KVCache为什么省算力.md)、[推理优化的主要手段](questions/LLM推理优化的主要手段.md)，原理深读 [LLM 推理为什么贵](articles/LLM推理为什么贵.md)、[KV Cache 与推理优化原理](articles/KVCache与推理优化原理.md)
- 微调路径（SFT、LoRA）：[RAG 和微调怎么选](questions/RAG和微调怎么选.md)，决策框架深读 [RAG 还是微调：决策框架与常见误判](articles/RAG还是微调决策框架与常见误判.md)

## 面试高频考点

1. [RAG 和微调怎么选？](questions/RAG和微调怎么选.md)
2. [RAG 效果差，从哪些环节排查优化？](questions/RAG效果差怎么排查.md)
3. [Agent 和普通工作流的区别是什么？](questions/Agent和普通工作流的区别.md)
4. [大模型幻觉是什么，工程上如何缓解？](questions/幻觉的工程缓解.md)
5. [向量数据库怎么选型？为什么向量检索快？](questions/向量检索为什么快.md)
6. [如何控制 LLM 应用的成本？](questions/LLM应用成本怎么控.md)

## 场景设计题

「怎么设计一个 AI 系统」类的场景题在 [AI 场景题地图](../system-design/questions/ai/README.md)（system-design 模块）：28 道攻略级推演——容量估算、架构塌陷演进、决策论证、追问应答。两个题库互为表里：本模块答「是什么、为什么、怎么选」，那边答「怎么设计、怎么权衡」。

## 目录结构

- `questions/`：知识型面试题（一题一文件，索引见 [questions/README.md](questions/README.md)）
- `articles/`：技术文章（索引见 [articles/README.md](articles/README.md)）
