# 并行工具执行

并行工具执行是 Harness 同时运行一批互不依赖的 tool call，并在全部完成后把结果一起回传模型。它利用[同轮多工具调用](../concept-same-turn-tool-batch/index.html)协议减少独立 I/O 的串行等待。

边界：只有彼此不依赖的调用才能并行；后一步参数依赖前一步结果时仍需跨轮串行。

第七章再次区分表达与执行：模型在同一 Assistant Turn 输出多个独立 tool_call，真正的 Promise、线程池或队列并发发生在 Harness；实现不应只读取 response.tool_calls[0]。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§3.2，revision 2846；《工具的真相》§6.2，revision 167。
