# 用成本级联细化多级 Compaction

## 推导

[成本有序 Compaction 级联](../concept-cost-ordered-compaction-cascade/index.html)提供 Claude Code 特定的三层实例；[Compression 触发策略](../concept-compression-trigger-policy/index.html)提供一般预算条件；Compaction Circuit Breaker限制昂贵层失败重试。三者共同细化为可运行的[多级 Compaction](../concept-multi-level-compaction/index.html) 路线。

## 学习成本

权重 3.5：把一般分层原则、产品实例和失败控制联合起来。

来源：同章 §2、§6，revision 173；这是指向既有一般概念的平行推导。
