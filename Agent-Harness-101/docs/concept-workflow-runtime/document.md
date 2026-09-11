# Workflow Runtime

Workflow Runtime 负责加载并执行 [Workflow Script](../concept-workflow-script/index.html)，注入 Agent、调度、预算、进度和恢复能力，并实施权限、并发与隔离约定。

普通 Node.js 即使能运行数组和 JSON 代码，也不知道 agent()、pipeline() 或恢复语义；因此脚本必须运行在实现相应宿主约定的 Runtime 上。

来源：§2-4，revision 1503。
