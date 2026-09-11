# Tool Call ID 绑定

[Tool Call](../concept-tool-call/index.html) ID 绑定用唯一 id 把每个结构化 tool_call 与对应 role: tool 结果精确关联，尤其支持同一 Assistant Turn 中存在多个调用。

它取代纯文本 Observation 靠位置或字符串约定匹配结果的脆弱方式。

来源：§4.3 与 §5.2，revision 167。
