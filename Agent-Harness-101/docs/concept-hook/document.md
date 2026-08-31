# Hook

Hook 是插入 [Agent Loop](../concept-agent-loop/index.html) 生命周期节点的扩展点，例如 model 调用前后、tool 调用前后或整个 agent 执行前后。它允许 Harness 在不改动基本循环的情况下加入权限审批、记忆、技能、TODO 维护或 tracing。

边界：Hook 是扩展机制；某个具体 Hook 执行的业务逻辑应另行定义。LangGraph 的 Middleware 与本章所说 Hook 处于相近角色。

第二章进一步区分 `PreToolUse`、`PostToolUse`、`Stop` 与 `SessionStart` 等事件，并把 Hook 定位为将“应该记得”升级为确定性执行的纪律层。

第十三章把 Hook 视为 [Harness Plugin](../concept-harness-plugin/index.html) 的生命周期扩展面，可与 [Prompt Fragment](../concept-prompt-fragment/index.html)、Tool 和 [Skill](../concept-skill/index.html) 聚合成完整 Feature。

第十四章补充 Middleware 调用语义：[Node-Style Hook](../concept-node-style-hook/index.html) 在边界变换状态，[Wrap-Style Hook](../concept-wrap-style-hook/index.html) 控制 Handler 调用次数，[临时 Request 修改](../concept-transient-request-modification/index.html)只影响当前请求；多层通常按洋葱顺序执行。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§2.1-2.2、§5.4，revision 2846；《模型之外的全部》§5.5、§8.2，revision 297；《Claude.AI 提示词与记忆结构解析》§7，revision 227；《从 for 循环到自治系统的进化之路》§3，revision 174。
