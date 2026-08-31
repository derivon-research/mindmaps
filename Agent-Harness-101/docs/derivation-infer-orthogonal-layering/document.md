# 从五类局部机制推出 Harness 的正交分层

## 推导

[ReAct Loop](../concept-react-loop/index.html) 规定基本运转节拍；[Plan-then-Act](../concept-plan-then-act/index.html) 增加全局覆盖；[Nudge](../concept-nudge/index.html) 处理运行时注意力偏移；[Context Offloading](../concept-context-offloading/index.html) 处理单条大负载；[Skill](../concept-skill/index.html) 处理大量能力的常驻成本。它们各自回应不同失败模式，并能在不改动其他机制语义的情况下调整，因此共同支持“好的 Harness 应按问题正交分层”的章末结论。

## 高权重原子性复核

权重 4.0：这是本章的关键架构桥梁，需要比较五种机制的问题边界并判断独立可替换性。中间概念（每种机制）已全部拆成独立点；剩余步骤就是作者明确给出的综合论证，不再隐藏可复用的中间结论。

来源：同章 §9「结语」，revision 2846。
