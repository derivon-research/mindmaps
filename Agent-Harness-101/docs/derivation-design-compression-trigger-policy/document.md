# 从真实预算与缓存代价设计 Compression 触发策略

## 推导

[Context Window](../concept-context-window/index.html) 给出物理上限；[Context 预留预算](../concept-reserved-context-budget/index.html)保护输出、压缩调用和突发结果；[Prompt 前缀稳定性](../concept-prompt-prefix-stability/index.html)揭示频繁改写的缓存代价；[Context Compression](../concept-context-compression/index.html) 揭示有损操作的失真风险。四项共同约束何时压、压什么和释放多少空间。

## 学习成本

权重 4.0：这是非显然的多目标工程权衡。高权重复核：容量、预留、缓存与信息损失已拆成独立尾点，每项约束不同失败面；具体百分比没有被隐藏成一个新概念。

来源：同章“阈值”，revision 145；产品数字按来源原文保留为经验材料。
