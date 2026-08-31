# 暴露 Workflow 运行进度

[Phase Progress](../concept-phase-progress/index.html) 声明当前阶段，[Structured Logging](../concept-structured-logging/index.html) 记录阶段内事件。两类信号共同建立 [Workflow 可观测性](../concept-workflow-observability/index.html)，让用户看到长任务跑到哪里、正在做什么。

权重 1.5：这是阶段级与事件级信息的直接组合；只具其一仍会丢失另一种粒度。

来源：§4.2 与 §6，revision 927。
