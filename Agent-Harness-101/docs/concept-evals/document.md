# Evals

Evals 是面向 Agent/Harness 行为的离线基准、评分与回归测试，用数据判断一次 Prompt、[Skill](../concept-skill/index.html)、[Hook](../concept-hook/index.html) 或其他机制改动是否改善或退化。

Evals 把 trajectory 或失败用例转成可比较信号，但评测结果本身不会自动修复 Harness。

第六章把单次 [Version Boundary](../concept-version-boundary/index.html) A/B 与系统证据分开：应跨模型、多轮次和不同 Breaking Change 重复采样，记录成功率，而不是把一次截图当作普遍结论。

来源：《从 [ReAct Loop](../concept-react-loop/index.html) 讲起》§2.1，revision 2846；《[Agent Version Drifting](../concept-agent-version-drifting/index.html)》§2-3 与 §6，revision 270。
