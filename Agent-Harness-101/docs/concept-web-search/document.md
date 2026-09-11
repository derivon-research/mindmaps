# Web Search 工具

Web Search 工具按查询词发现候选页面、来源或近期信息。它适用于尚不知道精确 URL 的探索阶段，返回结果通常包含标题、链接与摘要。

边界：已知要读取的具体 URL 时应使用 Web Fetch；Search 负责发现，Fetch 负责取回正文。

Managed Agent 来源将其用于当前信息发现；具体结果条数和查询语法属于产品版本行为。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§4，revision 2846；《Claude Code Agent 里的常用工具一览》§2，revision 310。
