# TODO 状态

TODO 状态是由 `write_todos` 工具写入 Agent state 的任务清单。每项可记录内容、状态与优先级，并在执行中增删、改写或标记完成。

相比仅在 prompt 中输出一段计划文本，工具化 TODO 会形成真实的 tool call/tool result 往返并留在上下文中，使计划成为可持续维护的执行状态。

Install.md 的 Markdown TODO 可作为初始任务模板，但只有 Agent 把它同步到持久或工具化状态后，才真正支持中断恢复与并发更新。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§5.1-5.2，revision 2846；《专为 Agent 设计的 Install.md》§2.6，revision 118。
