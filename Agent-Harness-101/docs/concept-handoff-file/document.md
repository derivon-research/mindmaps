# Handoff 文件

Handoff 文件是在会话或 Agent 交接前写入磁盘的结构化摘要，记录目标、已完成工作、当前状态、未决问题和下一步。

它把连续性从易失的 [Context Window](../concept-context-window/index.html) 转移到可持久读取的任务制品，为 [Session Reset](../concept-session-reset/index.html) 和 [Sub-Agent](../concept-sub-agent/index.html) 交接提供恢复入口。

第三章的增长案例用 `next_steps` 文件实现跨周期交接：[Orchestrator](../concept-orchestrator/index.html) 每轮先读未完成事项，汇总后再写回下一轮入口。

来源：《模型之外的全部》§5.1、§6.1-6.2，revision 297；《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§6，revision 1389。
