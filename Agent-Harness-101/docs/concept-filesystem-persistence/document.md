# 文件系统持久状态

文件系统持久状态是把 plan、handoff 摘要、工具输出快照和调试日志写入磁盘，使任务状态跨 [Context Window](../concept-context-window/index.html)、会话重启或 Agent 交接继续存在。

它与“[文件系统间接引用](../concept-filesystem-indirection/index.html)”相关但不等同：间接引用侧重减少单条上下文负载；持久状态侧重跨时间保存任务事实。

第八章补充组织记忆载体：[Semantic File System](../concept-semantic-file-system/index.html) 通过稳定路径、类型、Frontmatter 和 Wikilink 让 Artifact 成为可查询对象，但还需 [Context Graph](../concept-context-graph/index.html)、[Provenance](../concept-provenance/index.html) 与 Policy 才能构成 [Company Brain](../concept-company-brain/index.html)。

来源：《模型之外的全部》§5.1 与 §6.2，revision 297；《Company Brain》§2.1，revision 180。
