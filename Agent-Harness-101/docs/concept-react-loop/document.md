# ReAct Loop

ReAct Loop 将 Reasoning 与 Acting 交织：模型根据当前消息决定行动，发出 tool call；Harness 执行工具并返回 tool result；模型观察结果后再决定继续行动或给出终态。

最小天气示例：模型收到“北京今天冷吗”，调用天气工具，观察温度与天气结果，再生成回答。Harness 不替模型选择搜索方向，只检查协议并搬运消息。

来源：同章前言、§2.2 与 §3.1；论文出处按原文为 Yao et al. (2022), *ReAct: Synergizing Reasoning and Acting in Language Models*；revision 2846。