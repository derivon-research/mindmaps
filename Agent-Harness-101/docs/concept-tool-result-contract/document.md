# Tool Result 契约

[Tool Result](../concept-tool-result/index.html) 契约规定 Harness 回填给模型的结果格式、稳定字段、错误表达和裁剪策略。

即使 Tools API 不强制声明返回 Schema，结果仍是契约的一半；短小稳定的 JSON 比模糊文本或整包数据库日志更利于下一轮推理。

AFS 示例把 Provider 异常归一为 `not_found`、`forbidden`、`is_a_directory`、`unsupported_operation` 和 `internal_error`，说明后端异常不应直接泄漏成不稳定文本。

来源：《工具的真相》§3、§5.4 与 §7，revision 167；《写给 Agent 的虚拟文件系统》§4.6，revision 216。
