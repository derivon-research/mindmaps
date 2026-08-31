# Structured Logging

Structured Logging 用 `log()` 一类调用输出任务启动、子任务状态、审稿轮次与完成信息。

它补充比阶段标记更细的运行证据，使后台长任务不再只呈现一个无反馈黑箱。

开源实现补充：log() 既可写入 TUI 进度视图，也可通过 [JSONL Event Stream](../concept-jsonl-event-stream/index.html) 或 Runner 订阅交给无人值守宿主消费。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4.2 与 §6，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§3-4，revision 1503。
