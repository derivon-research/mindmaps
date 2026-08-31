# Worker 角色

Worker 角色领取一个具体子任务并产出结果。在深度研究 Workflow 中，每个并行 `agent()` 调用负责一个子课题，自行搜索、整理并按局部准出标准交付。

Worker 与 Planner、Evaluator 的职责可分别定义和复用，不应合并成一个笼统“多 Agent”点。

来源：§4-5，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
