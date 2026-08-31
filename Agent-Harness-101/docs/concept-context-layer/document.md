# Context Layer

Context Layer 负责在每次 LLM 调用前装配和治理上下文，决定模型这一轮实际看到什么。它可包含 Prompting、长轨迹压缩、短期记忆与长期记忆。

该层也承载运行时上下文补丁和 token 预算治理；[Context Offloading](../concept-context-offloading/index.html) 与 Compression 分别从单条负载和整段历史两个层次缓解窗口压力。

来源：同章 §2.1、§7，revision 2846。
