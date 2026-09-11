# 定义可移植 Runtime 边界

[Workflow 宿主 API](../concept-workflow-host-api/index.html) 固定脚本依赖的函数表面；[Runtime 无关的 Agent 边界](../concept-runtime-agnostic-agent-boundary/index.html)固定 agent() 需要提供的独立 Context、Tool Loop、权限与返回语义。两者共同使编排能迁移到等价实现，得到 [Runtime 可移植性](../concept-runtime-portability/index.html)。

权重 3.0：接口名与执行语义都必须兼容，只具其一不足以移植。

来源：§2.2、§3.1 与结语，revision 1503。
