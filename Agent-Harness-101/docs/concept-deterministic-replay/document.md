# 确定性重放

确定性重放固定 Workflow 的代码骨架，并把非确定性收敛到[显式 LLM 调用点](../concept-explicit-llm-call-site/index.html)，使审计者能定位两次运行从哪次调用开始分歧。

这里的“确定性”指控制流可复现，不承诺 LLM 输出逐字相同。

边界：本点描述控制流可复现；第五章的 [Journaled Replay](../concept-journaled-replay/index.html) 是另一件事，它通过输入匹配复用已完成 Agent 返回值来续接执行，不应混同为 VM 状态快照。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§5，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§6，revision 1503。
