# Web Fetch 工具

Web Fetch 工具读取一个已知 URL 的页面或资源正文，供模型提取和分析。它不负责发现候选页面。

在 Deep Research 中，模型可先 Search，再从候选结果中选择一两个 URL Fetch；读完正文后又可形成下一次 Search 的关键词。

Managed Agent 来源要求完整 URL 和提取 Prompt，并报告缓存、PDF 与 URL 来源限制；这些是产品约束，不是普遍定义。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§4，revision 2846；《Claude Code Agent 里的常用工具一览》§3，revision 310。
