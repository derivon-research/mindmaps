# 结构化 Tools 协议

结构化 Tools 协议把工具清单放入 API tools 字段，把动作表示为 tool_call，把结果表示为带 tool_call_id 的 role: tool 消息。

它把格式责任从普通自然语言和正则解析移到协议层，但没有自动解决描述含糊、参数过宽或结果臃肿等契约质量问题。

来源：§4.3-4.4 与 §5，revision 167。
