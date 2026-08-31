# Tool Call

Tool Call 是模型在 assistant turn 中发出的结构化行动请求，包含工具名、调用 ID 与输入参数。它是 ReAct 中 Act 的协议载体。

一个 assistant turn 可以包含零个、一个或多个 tool call。零个通常表示模型选择输出终态；多个可由 Harness 并行执行。

第七章强调 Tool Call 只是结构化“调用意图单”，不是已经发生的函数执行。模型依据 Context 中的 Tool Definition 与信息缺口填单，Harness 才验单并执行。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§3.1-3.2，revision 2846；《工具的真相》§5-6，revision 167。
