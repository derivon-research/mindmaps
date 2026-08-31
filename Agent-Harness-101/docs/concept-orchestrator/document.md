# Orchestrator

Orchestrator 是掌管总体目标和循环状态的 Agent 角色。它负责派发子任务、等待结果、汇总产出、发起验收，并决定 Ship 还是 Iterate。

它不必亲自完成所有子任务；其核心职责是让多个执行者围绕同一目标和 Memory 协同。

第四章的代码编排形态把 Orchestrator 的阶段顺序、并行、循环和分支固化到 [Workflow Script](../concept-workflow-script/index.html)；运行时 Orchestrator 因而不再独自承担整条流程的 Instruction Following。

来源：《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§3.2 与 §6，revision 1389；《Loop Engineering—从 ReAct 到 Orchestration》§2-5，revision 927。
