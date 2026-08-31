# 近期 Tool Result 保护

近期 [Tool Result](../concept-tool-result/index.html) 保护是在裁剪旧结果时始终保留最近 N 条或最近一轮观察，因为它们最可能仍被当前推理直接使用。

N 是策略参数而非语义常数；应结合工具批量大小和任务局部性校准。

来源：同章 §4.3、§5.4，revision 173。
