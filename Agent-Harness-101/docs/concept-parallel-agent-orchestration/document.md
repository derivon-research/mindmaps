# 并行 Agent 编排

并行 Agent 编排是由 [Orchestrator](../concept-orchestrator/index.html) 通过 [Fan-out](../concept-fan-out/index.html) 分发独立子任务，再通过 [Fan-in](../concept-fan-in/index.html) 汇总结果的调度结构。

它与“[同轮多工具调用](../concept-same-turn-tool-batch/index.html)”不同：这里并行的是拥有独立上下文与职责的 Agent，而不是同一 assistant turn 中的原子工具调用。

第四章的深度研究脚本把 Planner 产出的子课题逐一交给 Worker，再由 `Promise.all` 汇合；视频生成示例也让画面与配音并行，证明该结构不局限于文本研究。

来源：《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§3.2、§5.1 与 §6，revision 1389；《Loop Engineering—从 ReAct 到 Orchestration》§4 与 §7，revision 927。
