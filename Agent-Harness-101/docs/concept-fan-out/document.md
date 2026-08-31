# Fan-out

Fan-out 是 [Orchestrator](../concept-orchestrator/index.html) 将互不依赖的子任务同时派给多个 Agent 执行。它通过并行缩短总耗时，前提是任务边界清楚且不会互相踩写。

来源：飞书教程《Harness 101：从零认识 [Loop Engineering](../concept-loop-engineering/index.html)》，revision 1389，§3.2 与 §5-6，https://my.feishu.cn/wiki/SzR6wH3cXi87PPk01NbcaI1EnAc
