# AFS User Namespace

`/mnt/user/` 表示按用户隔离的长期空间，可容纳私有 Skills、Memory 和 Workspaces。Agent 不直接提供可信 `user_id`，Service 从会话身份解析后注入。

来源：同章 §3.1、§4.4，revision 216。
