# 从驻留成本得到累积 Context 面积

## 推导

[Context 驻留成本](../concept-context-residency-cost/index.html)说明每段内容会跨轮重复占用；[Long-horizon Execution](../concept-long-horizon-execution/index.html) 提供足够长的调用时间轴。沿时间轴累计每轮驻留量，就得到用于比较常驻与按需加载策略的[累积 Context 面积](../concept-cumulative-context-area/index.html)。

## 学习成本

权重 2.5：需要把离散 Agent 调用抽象成面积模型，并理解它不是 API 计费字段。

来源：同章“错觉”“结语”，revision 145。
