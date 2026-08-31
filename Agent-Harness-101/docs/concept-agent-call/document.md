# `agent()` 调用

`agent()` 是 [Workflow Script](../concept-workflow-script/index.html) 中创建子 Agent、委派一段智能任务的调用。第一个参数 `taskPrompt` 描述工作，第二个可选参数 `verificationPrompt` 描述准出标准。

这是 DeerFlow 3.0 的计划 API 形式，本文用它说明调用语义，不把具体签名当作稳定规范。

第五章修正接口理解：agent() 不是一次 Prompt Completion，而是一个拥有独立 Context、Tool 能力和[多轮 ReAct](../concept-multiround-react/index.html) 的临时 [Sub-Agent](../concept-sub-agent/index.html)。具体 options、[Structured Output](../concept-structured-output/index.html) 与返回 null 的行为以 Runtime 版本为准。

来源：《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4.1 与 §8，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§3.1-3.2，revision 1503。
