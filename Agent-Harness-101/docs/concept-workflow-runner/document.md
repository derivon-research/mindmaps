# Workflow Runner

Workflow Runner 是把 [Workflow Script](../concept-workflow-script/index.html) 集成到宿主系统的执行器。它可注入日志写入器、订阅强类型事件、运行脚本并释放资源。

同一个 Runner 可以并发执行多个 Workflow，同时保持每次运行的异步上下文隔离。

来源：§4.5，revision 1503；描述 Deer Workflow 开源实现。
