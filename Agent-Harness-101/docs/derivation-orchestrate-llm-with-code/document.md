# 用代码编排 LLM

[代码控制流](../concept-code-control-flow/index.html)负责阶段顺序、并行、循环和分支；[显式 LLM 调用点](../concept-explicit-llm-call-site/index.html)只在需要生成或判断的位置引入模型。两者共同建立“确定性归代码、判断力归模型”的职责边界，从而得到[代码编排 LLM](../concept-code-orchestrated-llm/index.html)。

权重 2.5：目标读者熟悉程序控制流和 LLM 调用，但需要完成一次非显然的职责重划。两个尾点缺一不可：只有代码没有智能调用只是普通 pipeline，只有调用点没有代码骨架仍由模型维持流程。

来源：§3 与 §4.2，revision 927。
