# Agent Loop、Tool Layer 与 Context Layer 构成 Harness 核心

## 推导

[Agent Loop](../concept-agent-loop/index.html) 提供反复调用模型与工具的运行节拍；[Tool Layer](../concept-tool-layer/index.html) 提供每轮可执行的外部能力；[Context Layer](../concept-context-layer/index.html) 决定每轮模型看到的提示、历史与记忆。三者分别回答“怎么转”“能做什么”“看见什么”，合在一起覆盖本章对 Harness 最小本体的定义。

其他会话、编排、插件与观测层可以扩展完整产品，但不改变这里的最小核心结论。

## 学习成本

权重 3.0：对目标读者而言，需要把三个独立层映射到一次运行过程，并理解“最小核心”与“完整产品外延”的区别，属于非显然的架构组合。

来源：《Harness 101：从 [ReAct Loop](../concept-react-loop/index.html) 讲起》revision 2846，§2.1。
