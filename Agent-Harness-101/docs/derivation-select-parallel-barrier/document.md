# 为跨项决策设置 Parallel Barrier

[跨项决策](../concept-cross-item-decision/index.html)要求全体结果；[Fan-out](../concept-fan-out/index.html) 同时展开独立任务；[Fan-in](../concept-fan-in/index.html) 等齐并收集各分支。三者共同建立 [Parallel Barrier](../concept-parallel-barrier/index.html)，防止在缺少必要结果时过早作出总决策。

权重 2.5：需要识别依赖全体上下文的同步点。三个尾点分别给出需求、展开和汇合。

来源：§3.3.1，revision 1503。
