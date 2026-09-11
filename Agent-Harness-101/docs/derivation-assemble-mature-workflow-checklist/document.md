# 组装成熟 Workflow 检查表

[Workflow Trigger](../concept-workflow-trigger/index.html) 检查启动入口；Planner 检查任务分解；[Workflow State](../concept-workflow-state/index.html) 检查外置进度；Worker 检查执行单元；Evaluator 检查质量闸门；[Workflow 循环](../concept-workflow-loop/index.html)与[条件分支](../concept-conditional-branch/index.html)检查非线性控制流；[Workflow 续跑](../concept-workflow-resumption/index.html)检查长任务中断恢复；[Workflow 可重复性](../concept-workflow-repeatability/index.html)检查审计与比较。逐项掌握这些维度，形成[成熟 Workflow 检查表](../concept-mature-workflow-checklist/index.html)。

权重 4.0：这是本章八部件解剖的主要综合单元。高权重复核：`Loop / Branch` 已拆成两个独立点，`Stop / Resume` 没有保留成协调点，而以外置 State 到续跑的独立构造表达；头点只表示完整检查表，不声称所有 Workflow 必须同时实现每一项。

来源：§5，revision 927。
