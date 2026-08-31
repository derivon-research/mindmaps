# Feedback Loop

Feedback Loop 把用户反馈、线上失败用例和 [Evals](../concept-evals/index.html) 暴露的退化项回流到 Prompting、Skills、Hooks 等可改进对象。

它负责把诊断信号转成下一轮工程迭代，是自演进闭环中的改动通道，而不是模型推理 Loop 本身。

来源：同章 §2.1「Observability & Evals Layer」，revision 2846。
