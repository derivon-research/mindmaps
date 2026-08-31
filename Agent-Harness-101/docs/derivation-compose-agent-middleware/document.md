# 三种 Hook 语义组成 Agent Middleware

[Node-Style Hook](../concept-node-style-hook/index.html) 在边界变换状态；[Wrap-Style Hook](../concept-wrap-style-hook/index.html) 控制 Handler 调用；[临时 Request 修改](../concept-transient-request-modification/index.html)影响单次请求而不持久化。三者共同覆盖 [Agent Middleware](../concept-agent-middleware/index.html) 的主要扩展语义。

权重 3.5：三类 [Hook](../concept-hook/index.html) 的状态持久性和控制权不同。来源：同章 §3.2，revision 174。
