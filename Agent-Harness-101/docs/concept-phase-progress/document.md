# Phase Progress

Phase Progress 用 `phase()` 一类调用声明当前阶段及其说明，让用户知道长任务处于规划、研究、起草、审改还是终验。

它提供阶段级可见性，不参与业务控制流。

开源实现补充：phase() 可把后续 [agent() 调用](../concept-agent-call/index.html)归入进度组；切换阶段和 Workflow 结束时，Runtime 负责收束阶段生命周期。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4.2 与 §6，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§3-4，revision 1503。
