# Compaction 候选池

Compaction 候选池是按工具类型、年龄和恢复风险登记的可治理 [Tool Result](../concept-tool-result/index.html) 集合。来源报告 Claude Code 只纳入 Bash、Read、Grep、Glob、WebFetch、WebSearch、FileEdit、FileWrite，未知 MCP 工具默认排除。

白名单是产品实现策略，不是这些工具天然安全的证明；文件和网页会变化，Bash 输出也可能承载不可再生证据。

来源：同章 §3.2、§5.5，revision 173。
