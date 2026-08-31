# 按成本排列三种 Compaction

## 推导

[Microcompact](../concept-microcompact/index.html) 提供高频规则裁剪；[Autocompact](../concept-autocompact/index.html) 承担中等压力并使用 Background Notes；[Fullcompact](../concept-fullcompact/index.html) 最后调用受限摘要 Agent。按额外推理成本和失败风险从低到高排列，得到[成本有序 Compaction 级联](../concept-cost-ordered-compaction-cascade/index.html)。

## 学习成本

权重 4.0：需要比较三层不同触发、载体和失败面。高权重复核：三层均已独立成点；Autocompact 是否调用 LLM 的来源冲突不作为排序的唯一依据。

来源：同章 §2、§6，revision 173。
