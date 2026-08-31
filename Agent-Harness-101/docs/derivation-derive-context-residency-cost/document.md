# 从负载持续驻留得到 Context 驻留成本

## 推导

[大体积工具负载](../concept-large-tool-payload/index.html)给出单次占用规模；[Context Window](../concept-context-window/index.html) 的多轮历史语义说明该负载会随后续请求继续驻留。把规模与驻留轮次同时计入，得到 [Context 驻留成本](../concept-context-residency-cost/index.html)，而非只看首次进入时的 token 数。

## 学习成本

权重 2.0：短标准组合，但要从瞬时长度切换到时间累计视角。

来源：《Harness 101：[Context Offloading](../concept-context-offloading/index.html) 机制》“错觉”“生命周期”，revision 145。
