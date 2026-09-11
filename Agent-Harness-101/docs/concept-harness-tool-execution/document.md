# Harness Tool 执行

Harness Tool 执行把模型返回的结构化调用意图映射为真实函数，重新校验参数与权限，处理超时、失败、重试和并发，再把裁剪后的结果作为 Tool Message 回填。

模型和 API 都不会自动执行应用函数；这层 glue code 是 [Agent Harness](../concept-agent-harness/index.html) 的职责。

来源：§1-2、§5.4 与 §6，revision 167。
