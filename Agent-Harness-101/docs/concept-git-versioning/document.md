# Git 状态版本化

Git 状态版本化为 Agent 写入的文件提供 diff、提交、分支、回滚与合并。Agent 可以在隔离分支上尝试修改，失败时恢复，验证后再合并。

Git 不替代文件系统存储；它在持久文件之上增加可审计的时间与分支结构。

第五章补充其恢复职责：运行前记录 Commit 或安全 stash，能在 Journal 只复用 Agent 计算、却不回滚磁盘副作用时提供真实状态基线。Git 与 Worktree 保护世界中的修改，Journal 保护已经付过的计算。

来源：《模型之外的全部》§5.1，revision 297；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§6.4，revision 1503。
