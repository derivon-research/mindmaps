# Session Reset

Session Reset 在连续压缩已造成过多信息损失时结束旧会话，以干净 [Context Window](../concept-context-window/index.html) 重新启动执行。

重启不等于放弃任务：它依赖磁盘上的 handoff 和任务状态恢复目标、进度与下一步。

第六章补充版本迁移用途：高风险整体切换时，新 Context 能直接隔离旧 Tool、Prompt 和模型轨迹，比仅靠 Reminder 更可靠；代价是必须通过外部状态恢复任务。

来源：《模型之外的全部》§6.1，revision 297；《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§6，revision 270。
