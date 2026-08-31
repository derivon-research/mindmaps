# 收敛非确定性以支持重放

[代码控制流](../concept-code-control-flow/index.html)固定每次运行的骨架；[显式 LLM 调用点](../concept-explicit-llm-call-site/index.html)标出剩余非确定性发生的位置。二者结合后，审计者可以重放相同路径，并精确定位两次结果从哪一次模型调用开始分歧。

权重 2.5：需要理解“[确定性重放](../concept-deterministic-replay/index.html)”只约束控制流而非逐字输出。两个尾点共同给出固定部分与可变边界。

来源：§5「Repeatability 与确定性重放」，revision 927。
