# 目标状态 Prompt

目标状态 Prompt 描述最终必须满足的状态及修改后验证，例如“确保所有配置包含 timeout”，而不是“再追加一次 timeout”。

它让中断后的重跑更接近幂等收敛，降低动作式指令重复产生副作用的风险。

第十五章将其用于安装契约：先检测已满足的配置和依赖，只补缺项，并禁止无授权覆盖用户现有值。

来源：《复刻 [Dynamic Workflow](../concept-dynamic-workflow/index.html)》§6.3-6.4，revision 1503；《专为 Agent 设计的 Install.md》§2.4，revision 118。
