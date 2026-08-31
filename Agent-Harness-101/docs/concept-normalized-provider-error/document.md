# Provider 错误归一化

Provider 错误归一化把后端异常映射成稳定 [Tool Result](../concept-tool-result/index.html) 错误码，如 `not_found`、`forbidden`、`is_a_directory`、`unsupported_operation` 与 `internal_error`，并避免泄漏内部敏感细节。

来源：同章 §4.6，revision 216。
