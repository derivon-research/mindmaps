# `assert()` 判断闸门

`assert()` 判断闸门调用 [LLM-as-a-Judge](../concept-llm-as-a-judge/index.html)，把自然语言验收问题转成布尔结果，供脚本决定回炉、分支、报错或交付。

它位于阶段之间，区别于 `agent()` 内部的 [Verification Prompt](../concept-verification-prompt/index.html)：后者约束单次 Worker 准出，前者控制外层 Workflow 流转。

来源：§4-5，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
