# 组装 Journaled Replay

[Agent Result Journal](../concept-agent-result-journal/index.html) 保存已完成调用，[输入匹配的结果缓存](../concept-input-matched-result-cache/index.html)让相同 prompt 与 options 直接复用；[同会话恢复](../concept-same-session-resume/index.html)限定有效范围，[未完成 Agent 重跑](../concept-unfinished-agent-reexecution/index.html)定义中断点行为。四项共同形成章节所称 [Journaled Replay](../concept-journaled-replay/index.html)。

权重 4.0：恢复表象容易被误认成 VM 快照，需要同时掌握记录、匹配、会话边界和未完成调用行为。高权重复核：实现观察与官方行为已在各尾点分开标注。

来源：§6.1-6.2，revision 1503。
