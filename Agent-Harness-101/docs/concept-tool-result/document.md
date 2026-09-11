# Tool Result

Tool Result 是 Harness 执行工具后写回消息历史的结构化观察结果，通常通过调用 ID 与原 tool call 对应。它是 ReAct 中 Observe 的协议载体，并成为模型下一轮决策的输入。

Tool Result 可能很大：不可可靠重放的结果可在产生时保存快照并用引用回填；必须先完整消费的稳定读取结果可在变旧后追溯回收。这不会改变它在 Loop 中“向模型反馈行动结果”的角色。

第七章补充：Harness 应把原始响应整理成短、稳定、语义明确的结果契约，并用 tool_call_id 精确绑定；整包日志会污染下一轮推理。

第十章补充服务端 Context Edit：某些旧结果可只从模型可见缓存视图中隐藏，而客户端保留完整消息。调试工具必须区分这两个视图。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§3.1、§6.2 与 §7.1，revision 2846；《工具的真相》§3、§5 与 §7，revision 167；《[Context Offloading](../concept-context-offloading/index.html) 机制》“生命周期”“差异”，revision 145；《Claude Code 的三种上下文压缩与 [Microcompact](../concept-microcompact/index.html) 的秘密》§4-5，revision 173。
