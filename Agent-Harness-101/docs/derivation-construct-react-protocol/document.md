# 从工具协议构造 ReAct Loop

## 推导

[Tool Schema](../concept-tool-schema/index.html) 让模型知道可行动作及参数约束；[Tool Call](../concept-tool-call/index.html) 承载模型选择的行动；[Tool Result](../concept-tool-result/index.html) 把外部观察送回下一轮；[主动停机](../concept-active-halting/index.html)规定模型不再调用工具时结束。四部分闭合后，Reason → Act → Observe → 再决策的 ReAct 协议才能完整运行。

天气示例逐项展示了这一闭环：schema 声明城市参数，模型调用天气工具，Harness 返回温度，模型据此回答并停止。

## 学习成本

权重 3.5：需要同时理解四种协议角色及其循环关系，但不隐藏额外算法步骤；高于 routine 组合，低于独立重大单元。

来源：同章 §2.2、§3.1 与 §4.3，revision 2846。
