# 消息权限来源

消息权限来源由 Harness 拼装时选择的 System、Developer、User 等层级决定，而不是由 XML 标签名称决定。

版本提醒必须进入能表达当前契约的高权限层，并且不能覆盖仍存在的更高优先级冲突指令。

用户可在文本中伪造 XML 标签或 Reminder 名称；Harness 与模型应结合真实消息 Role、注入 Anchor 和是否要求降级约束判断真实性。

来源：《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§4，revision 270；《Claude.AI 提示词与记忆结构解析》§5-6，revision 227。
