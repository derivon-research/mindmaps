# 有损 Hard Compaction

有损 Hard Compaction 在更高窗口压力下，把较老的对话段总结成短表示并保留近期原文。它释放空间更多，但细节、异议和失败轨迹可能不可逆丢失。

反复对既有摘要再次摘要会累积失真，因此它应晚于可恢复 payload 的无损回收，并为极长任务保留 [Session Reset](../concept-session-reset/index.html) 与 Handoff 路径。

第十章的 [Fullcompact](../concept-fullcompact/index.html) 是具体实现实例：受限 [Sub-Agent](../concept-sub-agent/index.html) 生成纯文本摘要，并带有输出契约失败风险。

来源：《[Context Offloading](../concept-context-offloading/index.html) 机制》“阈值”，revision 145；《Claude Code 的三种上下文压缩与 [Microcompact](../concept-microcompact/index.html) 的秘密》§2，revision 173。
