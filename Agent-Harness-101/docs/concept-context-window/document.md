# Context Window

Context Window 是一次模型调用可接收的 token 容量边界。[System Prompt](../concept-system-prompt/index.html)、对话历史、tool call 与 tool result 都会占用这个预算；长程 Agent 任务会让历史在多轮中持续累积。

接近上限时，模型可能漏看前文、前后矛盾或直接报错。Offloading 优先减少单条大负载的常驻成本，Compression 则在整段历史临近上限时兜底。

第九章补充预算边界：理论窗口还要扣除 System Prompt、工具定义、当前输出、压缩调用输入和突发 [Tool Result](../concept-tool-result/index.html) 的预留。Harness 应以内层 [Soft Context Limit](../concept-soft-context-limit/index.html) 管理历史，不能把理论上限全部视为工作记忆。

第六章补充：长 Context 不只带来容量压力，历史中成功的 [Tool Call](../concept-tool-call/index.html) 和回答还会成为隐式行为样本；版本切换后，这些具体轨迹可能与当前契约竞争。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§7，revision 2846；《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§1-2，revision 270；《Harness 101：[Context Offloading](../concept-context-offloading/index.html) 机制》“阈值”，revision 145。
