# Tool Layer

Tool Layer 是 Agent 在每一步 Loop 中可调用的能力集合。它既可包含文件、搜索、Shell 等内置原子工具，也可包含通过 MCP 接入的第三方工具和业务定制工具。

工具层决定 Agent 能采取哪些外部行动；工具可以替换和插拔，而 [Agent Loop](../concept-agent-loop/index.html) 的控制骨架可以保持不变。

第七章收紧边界：模型看见的是 Tool Definition，不看函数实现；能力本体位于应用、服务、数据库或本地进程中，Tool Layer 只有经 Harness 执行才会作用于外部世界。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§2.1 与 §6，revision 2846；《工具的真相》§1-2 与 §5，revision 167。
