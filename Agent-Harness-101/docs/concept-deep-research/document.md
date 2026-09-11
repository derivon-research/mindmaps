# Deep Research Agent

本章把 Deep Research 的雏形描述为[多轮 ReAct](../concept-multiround-react/index.html) 与 Web Search、Web Fetch 的组合：模型反复发现来源、读取正文、根据新信息调整查询，直到[主动停机](../concept-active-halting/index.html)。

其关键不是预先固定的 DAG，而是每次 tool call 依赖当前观察，轨迹长度事先不可知。进一步加入计划与提醒可改善覆盖度和执行稳定性。

第四章给出另一种具体组织：把 Quick Search、Plan、Parallel Research、Draft、Review Loop 与 Final Validation 写成 [Dynamic Workflow](../concept-dynamic-workflow/index.html)。它不否定研究 Worker 内部的多轮 ReAct，而是把外层阶段编排固定进代码。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§4-5，revision 2846；《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4，revision 927。
