# System Prompt

System Prompt 定义 Agent 的身份、行为边界、输出格式、工作方式与可见能力，是 Context Engineering 的核心输入之一。AGENTS.md、SOUL.md、IDENTITY.md 等文件最终都可被静态或动态装配进 System Prompt。

本章强调 XML 的块状边界便于 Harness 按开关动态拼装提示片段，但 XML 只是工程表达形式，不等同于 System Prompt 本身。

第六章进一步强调 XML 标签本身没有权限魔法：[Version Boundary Reminder](../concept-version-boundary-reminder/index.html) 是否权威，取决于 Harness 把它放在 System/Developer 等正确消息层和正确时序，而不是标签名。

第十三章把块状结构进一步解释为 [Prompt Fragment](../concept-prompt-fragment/index.html) 装配接口：可寻址、可替换、可按租户渲染。该章的具体 Claude 标签清单来自模型自述与作者观察，不是官方 Schema。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§2.1 与 §5.1，revision 2846；《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§4，revision 270；《Claude.AI 提示词与记忆结构解析》§1-2、§6，revision 227。
