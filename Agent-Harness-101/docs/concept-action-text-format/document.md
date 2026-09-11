# Action 文本格式

Action 文本格式是在没有结构化 Tools API 时，由 [System Prompt](../concept-system-prompt/index.html) 约定 Thought、Action、Action Input、Observation 与 Final Answer 等普通文本标记。

模型通过格式模仿输出半结构化调用单，少一个冒号或近似 JSON 都可能破坏解析。

来源：§4-4.2，revision 167。
