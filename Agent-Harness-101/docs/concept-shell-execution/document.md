# Shell 执行

Shell 执行让 Agent 通过一个通用工具组合现有 CLI：用 `grep` 搜索、`jq` 解析 JSON、`curl` 请求 HTTP、语言工具运行测试。

它扩大能力覆盖并允许“现场组合工具”，但也扩大命令、文件和网络风险面，因此需要 [Sandbox](../concept-sandbox/index.html) 与权限策略约束。

第十二章补充：Bash 应受权限、超时和非交互约束。来源对工作目录是否跨独立调用持久存在内部冲突，实际 Runtime 必须验证。

来源：《模型之外的全部》§5.2，revision 297；《Claude Code Agent 里的常用工具一览》§9，revision 310。
