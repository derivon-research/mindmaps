# 从外置 State 恢复 Workflow

[Workflow State](../concept-workflow-state/index.html) 记录当前阶段和已有中间结果；中断后的执行读取这些数据即可回到断点，而不是重跑此前所有阶段，由此得到 [Workflow 续跑](../concept-workflow-resumption/index.html)能力。

权重 1.5：这是持久状态的直接应用，但需要区分外置状态与单次对话上下文。

来源：§5，revision 927。
