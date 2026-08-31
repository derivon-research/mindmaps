# Agent Version Drifting

Agent Version Drifting 指运行时已经切换到新 Tool、Prompt 或模型契约，长 Context 却仍保留旧版本产生的回答与 [Tool Call](../concept-tool-call/index.html)，导致下一轮继续模仿过期行为。

它不是模型内部保存旧版本，也不是传统缓存未刷新，而是新旧信号同时进入当前推理。Version Shifting 是来源给出的同义叫法。

来源：§1-2 与 §6，revision 270。
