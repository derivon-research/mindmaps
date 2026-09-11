# 构造可恢复 Workflow

[幂等 Agent 单元](../concept-idempotent-agent-unit/index.html)缩小安全重跑范围；[Worktree 隔离](../concept-worktree-isolation/index.html)并行写入；[Git 状态版本化](../concept-git-versioning/index.html)保存可恢复基线；[目标状态 Prompt](../concept-desired-state-prompt/index.html) 促进重跑收敛；[读写 Phase 分离](../concept-read-write-phase-separation/index.html)明确副作用边界；[业务幂等键](../concept-business-idempotency-key/index.html)保护外部系统；[确定性验证](../concept-deterministic-verification/index.html)检查真实结果。七项共同把仅能复用计算的 Replay 提升为[可恢复 Workflow](../concept-recoverable-workflow/index.html)。

权重 4.5：这是长任务恢复的主要工程单元。高权重复核：隔离、基线、Prompt 语义、阶段拆分、外部幂等与验证均可独立学习，已全部拆点；每个尾点保护不同失败面，不能互相替代。

来源：§6.4，revision 1503。
