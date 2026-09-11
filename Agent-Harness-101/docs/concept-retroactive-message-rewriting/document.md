# 追溯式消息改写

追溯式消息改写是 Harness 在后续时刻修改已经进入 `messages` 的旧参数或旧结果，用短引用替换冗余原文。它是运行时对历史表示的变换，不是 Agent 主动调用的新工具。

改写必须保留 [Tool Call](../concept-tool-call/index.html)/[Tool Result](../concept-tool-result/index.html) 的绑定、动作审计线索和恢复地址；若只剩不可验证的摘要，就已经从无损回收变成有损压缩。

来源：同章“生命周期”“差异”，revision 145。
