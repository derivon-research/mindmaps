# 把 Workflow 嵌入宿主应用

[Workflow Runner](../concept-workflow-runner/index.html) 管理运行与订阅生命周期，[JSONL Event Stream](../concept-jsonl-event-stream/index.html) 提供机器可读事件，[全局事件序列](../concept-global-event-sequence/index.html)还原多个并发运行的真实顺序。三者共同支持[可嵌入 Workflow 执行](../concept-embeddable-workflow-execution/index.html)。

权重 2.5：需要协调执行、事件格式和跨并发顺序，但每一项接口都已单独定义。

来源：§4.4-4.5，revision 1503；描述 Deer Workflow 开源实现。
