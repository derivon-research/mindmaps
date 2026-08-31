# 跨会话记忆

跨会话记忆让新会话恢复过去任务的规则、事实和进度。静态规则可通过启动时注入的 `AGENTS.md`/`CLAUDE.md` 保存；任务状态和事实可存入文件、Markdown 树、KV 或向量库。

边界：[Context Window](../concept-context-window/index.html) 是单次调用/会话内工作集，不是持久记忆本身。

第三章进一步把外置 Memory 解释为循环间的“接力棒”：无论下一轮由哪个 Agent 执行，都从同一结构化状态恢复进度和失败教训。

第四章区分了更具体的 [Workflow State](../concept-workflow-state/index.html)：运行变量和外部存储让 loop 能停下、被另一进程读取并从断点续跑。它是跨会话记忆在单条 Workflow 执行中的具体状态形态。

第八章把范围提升到组织尺度：记忆不只保存任务进度，还必须记录来源、责任、时效、权限、[决策理由](../concept-decision-rationale/index.html)与行动边界，才能影响未来工作。

来源：《模型之外的全部》§5.1、§5.4，revision 297；《从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》§3.1，revision 1389；《Loop Engineering—从 ReAct 到 Orchestration》§5，revision 927；《[Company Brain](../concept-company-brain/index.html)》§1-3，revision 180。
