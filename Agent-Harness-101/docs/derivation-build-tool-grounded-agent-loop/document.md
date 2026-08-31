# 构造 Tool Grounded Agent Loop

[Tool Call 往返](../concept-tool-call-round-trip/index.html)把外部事实放回 Context，[ReAct Loop](../concept-react-loop/index.html) 让模型基于 Observation 决定继续调用或最终回答。两者共同构成 [Tool Grounded Agent Loop](../concept-tool-grounded-agent-loop/index.html)。

权重 2.0：这是 Tool 往返在多轮循环中的直接应用，区分一次事实补全与观察驱动的后续行动。

来源：§5-6，revision 167。
