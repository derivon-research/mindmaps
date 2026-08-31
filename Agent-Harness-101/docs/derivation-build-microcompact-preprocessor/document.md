# 构造 Microcompact 请求前预处理器

## 推导

[API 请求预处理 Hook](../concept-api-request-preprocessing-hook/index.html) 确定每轮执行位置；[Zero-LLM Compaction](../concept-zero-llm-compaction/index.html) 保证热路径没有额外模型调用；[Compaction 候选池](../concept-compaction-candidate-pool/index.html)限定可处理结果；[近期 Tool Result 保护](../concept-recent-tool-result-protection/index.html)保留局部工作集。四者共同构成来源所述 [Microcompact](../concept-microcompact/index.html)。

## 学习成本

权重 4.0：需要把时机、成本、资格与局部性组合成一套常驻机制。高权重复核：四个尾点各自可独立配置并保护不同失败面，已全部拆分。

来源：同章 §3，revision 173。
