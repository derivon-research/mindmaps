# 组合安全 Agent 版本迁移

[兼容优先迁移](../concept-compatibility-first-migration/index.html)尽量避免破坏；[并行版本隔离](../concept-side-by-side-versioning/index.html)同名契约；[Version Boundary](../concept-version-boundary/index.html) 为必须保留的长 Context 打补丁；[Session Reset](../concept-session-reset/index.html) 在高风险时隔离新旧轨迹；[迁移校验重试](../concept-migration-validation-retry/index.html)按当前 Schema 拒绝过期调用。五层共同形成[安全 Agent 版本迁移](../concept-safe-agent-version-migration/index.html)。

权重 4.0：这是策略选择的主要综合单元。高权重复核：五个尾点覆盖避免、共存、补丁、隔离和执行校验，彼此不是同义项；实际系统按风险选用，不表示每次迁移都必须全部开启。

来源：§6，revision 270。
