# Compaction Circuit Breaker

Compaction Circuit Breaker 在昂贵摘要连续失败达到上限后停止自动重试，防止 Session 陷入消耗 API 调用的失败循环。

来源报告 [Fullcompact](../concept-fullcompact/index.html) 连续失败三次会熔断；三次是产品参数，不是概念定义。

来源：同章 §2，revision 173。
