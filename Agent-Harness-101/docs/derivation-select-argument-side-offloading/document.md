# 从审计与恢复条件选择参数侧 Offloading

## 推导

[Tool Call](../concept-tool-call/index.html) 确定参数所在的协议位置；[Tool 参数审计轨迹](../concept-tool-argument-audit-trace/index.html)要求保留动作、路径和小参数；[Offloading 候选资格](../concept-offloading-eligibility/index.html)只允许替换已有可靠副本的大数据字段。三项联合得到[参数侧 Offloading](../concept-argument-side-offloading/index.html)，而不是删除整个调用记录。

## 学习成本

权重 3.0：需要逐字段区分数据冗余与审计证据。

来源：同章“差异：args 维度”，revision 145。
