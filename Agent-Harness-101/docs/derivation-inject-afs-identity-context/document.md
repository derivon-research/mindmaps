# 从可信客户端与命名空间注入身份

[AFSClient](../concept-afs-client/index.html) 绑定可信 Session；[AFS 路径命名空间](../concept-afs-path-namespace/index.html)区分 User、Session 与 Public 作用域。Service 联合两者解析身份，而不接受 Agent 自报 ID。

权重 3.0：路径选择作用域、会话提供可信身份。来源：同章 §4.4，revision 216。
