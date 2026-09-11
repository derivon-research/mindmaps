# 编译出 Dynamic Workflow

[Workflow 生成](../concept-workflow-generation/index.html)按当前任务产出一份可修改、可存档的 [Workflow Script](../concept-workflow-script/index.html)；[代码编排 LLM](../concept-code-orchestrated-llm/index.html) 让脚本骨架确定、智能只出现在显式调用点。三者联合构成 [Dynamic Workflow](../concept-dynamic-workflow/index.html)，而不是一条工程师预写死的静态 pipeline。

权重 3.5：需要把生成时与执行时分开，并理解“动态”属于脚本生成、“确定”属于脚本执行。每个尾点承担独立作用，没有隐藏中间构造。

来源：§2-4 与 §8，revision 927。
