# Workflow 宿主 API

Workflow 宿主 API 是 Runtime 向脚本提供的非 JavaScript 标准能力，例如 agent()、parallel()、pipeline()、workflow()、phase() 和 log()。

脚本上层仍是普通控制流，下层通过这组接口访问可替换的 Agent Runtime 与调度设施。

来源：§2-3，revision 1503。
