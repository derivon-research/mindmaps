# 指令、Hook 与 Evaluator 形成分层防线

[System Prompt](../concept-system-prompt/index.html)/AGENTS.md 明示规则，让模型知道禁区；[Hook](../concept-hook/index.html) 在执行路径机械拦截；Evaluator 以验收标准阻止违规产出被接受。三层分别覆盖认知、执行和交付，因此同一错误复发需要同时穿透三道防线。

权重 2.5：这是短而完整的纵深防御组合，三个前提均有独立贡献。

来源：同章 §4.2 的 commented-out tests 示例，revision 297。
