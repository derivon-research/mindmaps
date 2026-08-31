# 按损失等级组合多级 Compaction

## 推导

[Compression 触发策略](../concept-compression-trigger-policy/index.html)提供递增压力条件；[无损 Soft Compaction](../concept-lossless-soft-compaction/index.html) 先回收可恢复 payload；[有损 Hard Compaction](../concept-lossy-hard-compaction/index.html) 在更高压力下总结老历史。按损失从低到高排列三者，就得到[多级 Compaction](../concept-multi-level-compaction/index.html)。

## 学习成本

权重 3.0：需要把阈值从单点开关改造成分层状态响应。

来源：同章“阈值：多级阈值设计”，revision 145。
