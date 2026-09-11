# 用 Prompt 模拟 Tool 协议

[System Prompt](../concept-system-prompt/index.html) 声明工具清单和行为规则，[Action 文本格式](../concept-action-text-format/index.html)规定模型如何提交调用，[Tool 输出解析器](../concept-tool-output-parser/index.html)把普通文本还原成可执行动作。三者共同构成早期 [Prompt Tool 协议](../concept-prompt-tool-protocol/index.html)。

权重 3.0：需要规则、格式和解析三方配合；只有 Prompt 示例没有 Harness parser 不能执行真实能力。

来源：§4，revision 167。
