# Agent Harness

Agent Harness 是承载 Agent 运行与扩展的一组工程机制，而不是模型本身，也不是一个不可拆解的黑盒中间件。本章给出的最小核心由 [Agent Loop](../concept-agent-loop/index.html)、[Tool Layer](../concept-tool-layer/index.html) 与 [Context Layer](../concept-context-layer/index.html) 构成；完整产品还可增加会话、编排、插件、可观测性和评测层。

边界：这里的 Harness 指模型之外、围绕模型调用组织执行的运行层。不同系统可以有不同外延，但若缺少循环调度、工具能力或上下文装配中的关键部分，就不能覆盖本章讨论的 Harness 本体。

示例：同一个 Harness 骨架接入搜索工具时可形成 [Deep Research Agent](../concept-deep-research/index.html)，接入文件与 Shell 工具时可形成 [Coding Agent](../concept-coding-agent/index.html)。

第二章补充了一份工程清单：指令、工具、运行环境、编排、确定性注入与可观测性都属于“模型权重之外、用户请求之内”的 Harness 范围。

来源：飞书教程《Harness 101：从 [ReAct Loop](../concept-react-loop/index.html) 讲起》，revision 2846，§2.1 与 §9，https://my.feishu.cn/wiki/N94ZwtUv4iVsUtkvWAYchNKWnhb；《Harness 101：模型之外的全部》，revision 297，§2，https://my.feishu.cn/wiki/Y5jYww4MLiL1ulkwTL6cf6Drnbc
