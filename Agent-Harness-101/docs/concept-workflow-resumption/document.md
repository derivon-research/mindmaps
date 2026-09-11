# Workflow 续跑

Workflow 续跑让长任务在中断后从已记录的阶段与中间结果继续，而不是从头重做。

它依赖外置 [Workflow State](../concept-workflow-state/index.html)：只有停点和成果被记录，另一次执行才知道从哪里恢复。

第五章给出更窄的已实现语义：Claude Code 的恢复只在同会话有效，已完成 agent() 返回缓存，未完成调用重跑，新会话从头开始。它不是 VM 快照，也不自动回滚副作用。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§5，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§6，revision 1503。
