# 显式 LLM 调用点

显式 LLM 调用点是 [Workflow Script](../concept-workflow-script/index.html) 中明确把搜索、规划、写作、改写或判断交给模型的位置。

来源示例只用两类调用：`agent()` 负责生成性工作，`assert()` 负责判断。调用点之外的流程控制由代码承担，因此非确定性的位置可以被定位和审计。

来源：§3、§4.2 与 §5，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
