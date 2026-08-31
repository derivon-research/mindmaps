# Dynamic Workflow

Dynamic Workflow 是由模型按任务生成、再作为普通代码执行的单个 loop：代码固定骨架，`agent()` 与 `assert()` 等显式调用点嵌入模型智能。

它是 [Loop Engineering](../concept-loop-engineering/index.html) 的一种具体实现，不等同于全部 Loop Engineering。适合阶段清晰、有验收标准、需要稳定交付和重复执行的复杂任务；一次性、边界模糊的探索仍可能更适合对话或 [Skill](../concept-skill/index.html)。

下一章补充了可执行边界：保存文件由 Metadata 与脚本主体组成，真正运行还依赖 [Workflow Runtime](../concept-workflow-runtime/index.html) 注入宿主 API、权限、并发、进度和恢复语义。Dynamic 指编排为当前任务生成的时机，不表示任意 JavaScript 引擎都能直接运行。

来源：《Loop Engineering—从 ReAct 到 Orchestration》§2-5、§7-8，revision 927；《复刻 Dynamic Workflow》§1-4，revision 1503。
