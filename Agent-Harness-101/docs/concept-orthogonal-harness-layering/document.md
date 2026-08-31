# Harness 的正交分层

Harness 的正交分层是把不同问题交给可独立替换的局部机制：ReAct 管运转节拍，[Plan-then-Act](../concept-plan-then-act/index.html) 管全局覆盖，[Nudge](../concept-nudge/index.html) 管运行时提醒，Offloading 管单条数据外置，[Skill](../concept-skill/index.html) 管能力按需加载。

这些机制叠加但不应彼此绑死。调整 Offloading 阈值不应破坏 Skill 加载；更换 Nudge 触发规则不应改变 ReAct 的基本协议。独立观察点、配置和版本边界让 Harness 可以持续演进。

来源：同章 §9「结语」，revision 2846。
