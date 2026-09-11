# 把 agent() 实现为独立 ReAct Loop

[ReAct Loop](../concept-react-loop/index.html) 提供多轮观察与行动；[Sub-Agent](../concept-sub-agent/index.html) 提供独立执行者；[Context Layer](../concept-context-layer/index.html) 隔离工作集；[Tool Layer](../concept-tool-layer/index.html) 允许读文件、搜索和运行命令。四者联合实现本章的 [agent() 调用](../concept-agent-call/index.html)，而不是一次 Completion。

权重 3.5：这是 Harness 边界的关键解释。高权重复核：Context 与 Tool 已作为独立可复用层拆点，剩余组合是一条完整执行语义。

来源：§3.1，revision 1503。
