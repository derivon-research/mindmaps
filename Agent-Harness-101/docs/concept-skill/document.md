# Skill

Skill 是 Harness 组织和按需加载专门能力的一种文件系统机制。每个 Skill 以文件夹和 `SKILL.md` 为核心，启动时只注册 frontmatter，命中时由模型读取正文。

本章强调 Skill 不需要新增 `invoke_skill` 工具：它复用 ReAct 自主决策、[System Prompt](../concept-system-prompt/index.html) 中的元数据目录和 [Coding Agent](../concept-coding-agent/index.html) 已有的 `read_file`。

边界：Skill 解决能力数量增长造成的常驻上下文与注意力问题，不替代 Tool 的原子执行接口，也不等同于一次向量检索。

第二章补充：`description` 定义触发面，`allowed-tools` 可收紧激活后的工具白名单；完整 `references/`、`assets/`、`scripts/` 仍按需加载。

第四章补充 Skill 与 Workflow 的结构边界：Skill 把执行路径交给模型在运行时理解和即兴选择，因而更灵活，也承担更高的 Instruction Following 负担；它适合探索性、边界模糊的任务，并不被 Workflow 取代。

第五章进一步限定 Failure Mode：问题不在 Skill 本身，而在让自然语言 Skill 包办长业务流程的全部控制逻辑。Skill 适合领域术语、Rubric、工具经验与例外原则；Workflow 固定次序、并发、数据结构和停止条件，二者可以相互调用。

第十三章把 Skill 视为 [Harness Plugin](../concept-harness-plugin/index.html) 的四类扩展面之一：它负责按需加载任务方法，与 [Prompt Fragment](../concept-prompt-fragment/index.html)、Tool、[Hook](../concept-hook/index.html) 协同但不互相替代。

第十五章指出 Install.md 与 SKILL.md 都面向 Agent，但作用域不同：Install.md 是仓库首次安装合同；Skill 是可复用任务能力。两者可采用相似的真实试跑、失败归纳和人工审核循环。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§8，revision 2846；《模型之外的全部》§8.1，revision 297；《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§3 与 §8，revision 927；《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§1 与 §7.3，revision 1503；《Claude.AI 提示词与记忆结构解析》§7，revision 227；《专为 Agent 设计的 Install.md》§2.8、§3.3，revision 118。
