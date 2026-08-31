# 回收可恢复占用得到无损 Soft Compaction

## 推导

[可回收 Context 占用](../concept-recoverable-context-occupancy/index.html)标出有外部真值的旧内容；[追溯式消息改写](../concept-retroactive-message-rewriting/index.html)把这些内容换成引用。只改变驻留表示、不销毁原始信息，就得到[无损 Soft Compaction](../concept-lossless-soft-compaction/index.html)。

## 学习成本

权重 2.0：直接构造；仍需注意行为上多了一次按需读取。

来源：同章“阈值：多级阈值设计”，revision 145。
