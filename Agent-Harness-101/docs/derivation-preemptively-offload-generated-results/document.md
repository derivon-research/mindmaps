# 生成时保存不可重放的大结果

## 推导

[Tool Result](../concept-tool-result/index.html) 确定拦截位置；[Offloading 候选资格](../concept-offloading-eligibility/index.html)说明该结果大且有必要外置；[文件系统间接引用](../concept-filesystem-indirection/index.html)提供 Context 中的短替身。Harness 在回填前保存原文并写入引用，就建立[生成时主动卸载](../concept-generation-time-offloading/index.html)。

## 学习成本

权重 3.0：需要同时理解协议边界、候选策略与外部存储替换。

来源：同章“生命周期：机制 A”，revision 145。
