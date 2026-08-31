# 配置优先诊断

配置优先诊断是在 Agent 失败时，先检查 Tool description、[System Prompt](../concept-system-prompt/index.html) 冲突、[Hook](../concept-hook/index.html) 拒绝、权限、上下文和编排，再把剩余问题归因于模型能力。

它不是断言所有失败都由配置造成，而是一种可行动的排查顺序：Harness 问题能由工程师立即观测和修复，模型权重通常不能。

来源：同章 §3「错觉」，revision 297。
