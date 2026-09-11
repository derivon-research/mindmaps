# Planner 角色

Planner 角色把目标拆成可执行计划、依赖和阶段，并在动手前明确工作范围。它负责“做哪些事情”，不负责替 Generator 完成全部实现。

深度研究 Workflow 中，Planner 读取 Quick Search 后生成可并行的子课题及其 `title`、`goal`、`searchHint`，为 [Fan-out](../concept-fan-out/index.html) 提供可执行分解。

来源：《模型之外的全部》§6.2，revision 297；《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4-5，revision 927。
