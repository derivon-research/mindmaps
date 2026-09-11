# 行为驱动的 Harness 设计

行为驱动的 Harness 设计先说明想得到或修复的模型行为，再选择合适的 Prompt、Tool、[Hook](../concept-hook/index.html)、[Skill](../concept-skill/index.html) 或评审机制来实现。

每个组件都应回答“它让模型做什么或不做什么”；无法回答的组件缺少存在证据，应被移除。

来源：同章 §4.3，revision 297。
