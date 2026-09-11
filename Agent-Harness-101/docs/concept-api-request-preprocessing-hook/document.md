# API 请求预处理 Hook

API 请求预处理 [Hook](../concept-hook/index.html) 在每次模型请求发出前运行，对即将发送的 Context 做确定性检查或变换。它位于 [ReAct Loop](../concept-react-loop/index.html) 的请求边界，而不是窗口告急后才触发的后台事件。

该位置适合低延迟、无额外模型调用的治理；昂贵或不可预测的工作会直接放大每轮延迟。

来源：同章 §3.1、§3.3，revision 173。
