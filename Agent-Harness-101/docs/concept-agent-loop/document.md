# Agent Loop

Agent Loop 是 Harness 的运行核心。它反复调用 LLM、检查模型是否发出工具调用、执行工具并把结果加入消息历史，直到模型输出不再包含工具调用或达到外部安全上限。

Loop 本身不替模型判断“信息是否足够”或“下一步该查什么”；这些决策由模型在每轮生成时完成。Harness 负责协议搬运、生命周期控制和可插入的 Hooks。

来源：同章 §2.1-2.2「Harness 的本体」「Agent Loop 的本体」，revision 2846。
