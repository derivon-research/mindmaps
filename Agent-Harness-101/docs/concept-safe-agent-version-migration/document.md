# 安全 Agent 版本迁移

安全 Agent 版本迁移按风险组合兼容、并行版本、[Version Boundary](../concept-version-boundary/index.html)、Session 隔离、服务端校验和回归评测，而不是依赖一条提醒解决全部问题。

高风险整体迁移通常优先新 Context；需要保留长 Context 且无法改名时，Version Boundary 才承担过渡补丁角色。

来源：§6，revision 270。
