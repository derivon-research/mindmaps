# Runtime 无关的 Agent 边界

Runtime 无关的 Agent 边界把 agent() 定义为“派一个拥有独立 Context 与 Tool Loop 的执行者并返回最终结果”，而不暴露其内部 Harness 实现。

只要替代执行器满足独立 Context、工具使用、权限控制和结束返回约定，背后可以是 Claude Agent SDK、Codex 或企业自建 [ReAct Loop](../concept-react-loop/index.html)。

来源：§2.2 与 §3.1，revision 1503。
