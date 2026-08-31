# 动态 Harness 编译

动态 Harness 编译是按任务类型在运行时选择和拼装 Prompt、Tool、[Skill](../concept-skill/index.html)、[Hook](../concept-hook/index.html)、权限与调度策略，而不是只读取一套静态配置。

来源把它列为未来开放方向，尚无行业标准答案；本点因此记录为有明确出处但仍不确定的工程设想。

第四章给出一个具体收敛方向：旗舰模型按任务把流程一次性编译成 [Workflow Script](../concept-workflow-script/index.html)，再由普通模型重复执行。它没有消除更广义动态 Harness 编译的不确定性，但提供了可运行的局部形态。

来源：《模型之外的全部》§7.3，revision 297；《[Loop Engineering](../concept-loop-engineering/index.html)—从 ReAct 到 Orchestration》§2、§4 与 §8，revision 927。
