# Tracing、Evals 与 Feedback 构成自演进闭环

## 推导

[Tracing](../concept-tracing/index.html) 产生运行轨迹证据；[Evals](../concept-evals/index.html) 对证据评分并识别短板；[Feedback Loop](../concept-feedback-loop/index.html) 把短板回流到 Prompting、Skills 或 Hooks。改动后的 Harness 再进入下一轮运行，三者因而闭合为可观察、可评测、可改进的 [Self-evolving Harness](../concept-self-evolving-harness/index.html)。

## 学习成本

权重 3.5：需要理解证据、判断与改动三个阶段的方向性，以及它们如何跨运行形成反馈闭环。

来源：同章 §2.1，revision 2846。
