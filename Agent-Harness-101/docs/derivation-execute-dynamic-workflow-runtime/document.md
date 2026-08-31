# 用 Runtime 执行 Dynamic Workflow

[Workflow Script](../concept-workflow-script/index.html) 描述普通 JavaScript 控制流；[Workflow Runtime](../concept-workflow-runtime/index.html) 负责加载、隔离、预算、进度与恢复；[Workflow 宿主 API](../concept-workflow-host-api/index.html) 把 Agent 和调度能力注入脚本。三者共同给出 [Dynamic Workflow](../concept-dynamic-workflow/index.html) 的可执行形态。

权重 3.0：目标读者熟悉脚本，但需要理解代码文件本身不包含完整运行语义。三个尾点分别提供程序、执行环境和能力边界。

来源：§2-4，revision 1503。这是对第四章“生成脚本”构造的平行运行时解释。
