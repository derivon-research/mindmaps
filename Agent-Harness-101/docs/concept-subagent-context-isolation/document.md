# Sub-Agent Context Isolation

[Sub-Agent](../concept-sub-agent/index.html) Context Isolation 让 Worker 在独立 Context 中执行多轮工具调用，只向主 Agent 返回压缩结果，避免中间轨迹占满主线程窗口。

压缩结果可能丢失证据，主 Agent 仍需可追溯 Artifact 或验证接口。

来源：同章 §2.1，revision 174。
