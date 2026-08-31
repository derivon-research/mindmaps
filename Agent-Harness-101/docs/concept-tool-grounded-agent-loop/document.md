# Tool Grounded Agent Loop

Tool Grounded [Agent Loop](../concept-agent-loop/index.html) 让模型在每轮依据外部执行结果改变下一步行动：一次调用补一个事实，并行调用补一组独立事实，多轮调用则让后续查询依赖先前观察。

Harness 保持机械循环，模型负责基于观察选择下一步。

来源：§5-6 与 §8.2，revision 167。
