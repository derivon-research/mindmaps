# Plan-then-Act

Plan-then-Act 在多轮执行前先写出计划，再按计划逐项行动并更新状态。它为纯 ReAct 的局部、战术式决策增加全局覆盖视角。

本章的最小实现没有更换 Loop：只增加 `write_todos` 工具和一段要求先计划、后执行、动态调整的 [System Prompt](../concept-system-prompt/index.html) 指令。

边界：计划不是固定不可变的工作流；新发现可以触发 TODO 的增删和修订。

第二章补充了磁盘化 plan：计划可以成为 Agent 与自己之间的持久合同，使“下一步做什么”在长程任务中不只依赖当前 Context 推断。

第三章把 Plan 放进 Discovery → Plan → Execute → Verify 的周期；Plan 应把独立模块拆开，以便并行执行并减少冲突。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§5，revision 2846；《模型之外的全部》§6.2，revision 297；《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§3、§5，revision 1389。
