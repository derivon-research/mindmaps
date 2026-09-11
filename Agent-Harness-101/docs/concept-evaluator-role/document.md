# Evaluator 角色

Evaluator 角色依据预先约定的完成条件检查 Generator 产出，例如测试、边界、benchmark 或评审 blocker。它与生成者分离，以降低自评者过早宣布胜利的倾向。

第四章把 Evaluator 细化成两层：[Verification Prompt](../concept-verification-prompt/index.html) 控制单个 Worker 的准出，独立 `assert()` 控制阶段回炉与最终交付。两者都可用 [LLM-as-a-Judge](../concept-llm-as-a-judge/index.html)，但作用域不同。

来源：《模型之外的全部》§6.2，revision 297；《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§4-5，revision 927。
