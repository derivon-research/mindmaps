# Long-horizon Execution

Long-horizon Execution 是跨很多轮次、较长时间或多个 Agent 持续推进同一目标的执行形态。主要风险分为 Context 战线和调度战线：历史退化或装不下，以及任务偏航、错误宣布完成或交接不清。

Harness 需要把关键状态外置，并用压缩、重启、计划、[Hook](../concept-hook/index.html) 与角色分离等机制维持连续性。

来源：同章 §6，revision 297。
