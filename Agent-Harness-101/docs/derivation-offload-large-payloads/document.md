# 大负载通过文件间接引用实现 Context Offloading

## 推导

[大体积工具负载](../concept-large-tool-payload/index.html)若原样进入消息历史会持续占用窗口。[文件系统间接引用](../concept-filesystem-indirection/index.html)允许 Harness 在负载产生时把原文写到磁盘，只在消息中保留路径，并让 Agent 在需要时无损读回。把阈值检测与这一位置替换应用到负载，即得到 [Context Offloading](../concept-context-offloading/index.html)。

第九章将这条早期推导限定为“[生成时主动卸载](../concept-generation-time-offloading/index.html)”路线；已进入 Context 的历史返回还可通过独立的追溯回收路线支持同一目标。恢复是否无损取决于引用是否固定到当时内容。

## 学习成本

权重 3.0：需要跨越“消息历史”与“外部存储”两个抽象层，并理解它与有损摘要的差异。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§7.1-7.2，revision 2846；《Harness 101：Context Offloading 机制》“生命周期”，revision 145。
