# 渐进式披露

渐进式披露按需要分层加载信息：低成本元数据常驻上下文，完整正文只在任务匹配时读取，正文引用的额外资源再按执行需要加载。

在 [Skill](../concept-skill/index.html) 机制中，它避免把几十上百份 SOP 全塞进 [System Prompt](../concept-system-prompt/index.html)，同时保持能力目录每轮可见。

第十三章给出两条平行实例：[用户记忆 Summary](../concept-memory-summary/index.html) 常驻、原始对话按需检索；Tool Search 只常驻发现入口、第三方工具 Schema 延迟加载。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§8，revision 2846；《Claude.AI 提示词与记忆结构解析》§3，revision 227。
