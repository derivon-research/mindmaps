# Prompt Tool 协议

Prompt Tool 协议把工具清单与调用格式写入 [System Prompt](../concept-system-prompt/index.html)，让模型用普通文本提交 Action，由应用解析、执行并以 Observation 回填。

它能工作是因为模型擅长模仿清晰 Few-shot 格式，但协议脆弱且高度依赖 Instruction Following。

来源：§4，revision 167。
