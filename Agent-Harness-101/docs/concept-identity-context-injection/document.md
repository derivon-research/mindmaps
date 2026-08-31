# 身份上下文注入

身份上下文注入由 Service 根据可信会话和目标命名空间决定传给 Provider 的 `user_id`、`session_id` 或无身份上下文，防止 Agent 自报租户身份。Provider 仍须做最终授权。

来源：同章 §4.4-4.5，revision 216。
