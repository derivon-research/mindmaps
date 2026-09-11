# Tool 输出解析器

Tool 输出解析器从普通 Assistant Text 中提取 Action 与 Action Input，校验近似 JSON，并在失败时触发错误 Observation 或重试。

它是早期 [Prompt Tool 协议](../concept-prompt-tool-protocol/index.html)的 Harness 组件；不同项目常重复实现正则、分隔符和容错规则。

来源：§4.1-4.3，revision 167。
