# Ralph Loop

Ralph Loop 用 Stop [Hook](../concept-hook/index.html) 拦截未满足目标的退出尝试，在新的 [Context Window](../concept-context-window/index.html) 中重启同一目标，并从磁盘状态继续。

其核心不是让单个上下文无限延长，而是让任务目标跨多个干净会话持续存在：Context 可以重置，持久状态和完成条件不能丢。

来源：同章 §6.2，revision 297；术语出处按原文为 Geoffrey Huntley (2025)。
