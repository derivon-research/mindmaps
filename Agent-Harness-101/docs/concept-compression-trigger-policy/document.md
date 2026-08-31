# Compression 触发策略

Compression 触发策略把当前占用、消息年龄、单条大小、恢复资格、输出预留和突发 [Tool Result](../concept-tool-result/index.html) 风险组合成何时压、压哪些内容、压到什么程度的决策。

原文列出的 75%-92% 产品区间和 85% 建议是 revision 145 的比较与作者经验，不是统一标准。实际阈值必须基于模型限制、工具分布、缓存机制和可接受的信息损失校准。

来源：同章“差异：compression 触发”“阈值”，revision 145。
