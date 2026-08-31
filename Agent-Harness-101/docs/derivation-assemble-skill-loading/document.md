# ReAct 与分层文件内容构成 Skill 加载机制

## 推导

[Skill 元数据目录](../concept-skill-metadata-catalog/index.html)让可用能力每轮可见；[Skill 正文](../concept-skill-body/index.html)把完整 SOP 保存在磁盘；[渐进式披露](../concept-progressive-disclosure/index.html)规定目录常驻、正文按需、附加资源再按需；[ReAct Loop](../concept-react-loop/index.html) 让模型在推理中识别意图并调用普通 `read_file`。四者合起来，无需新增 [Skill](../concept-skill/index.html) 专用工具即可实现能力发现与加载。

每个前提均有独立贡献：没有目录会漏触发，没有正文无具体流程，没有披露层次会重新挤满上下文，没有 ReAct 决策则只剩被动检索。

## 学习成本

权重 3.5：包含一次非显然的抽象复用，即用文件系统和既有工具实现新能力组织机制，但论证仍是单个完整构造。

来源：同章 §8.1-8.5，revision 2846。
