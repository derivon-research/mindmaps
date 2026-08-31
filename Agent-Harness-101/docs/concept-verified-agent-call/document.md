# 自验证 `agent()` 调用

自验证 `agent()` 调用把 Worker 的多轮重试内化在一次调用内部：外层脚本只看到任务委派与合格结果，不需要编写 `for (retry...)` 样板循环。

其保证取决于 [Verification Prompt](../concept-verification-prompt/index.html) 与裁判模型的质量，并不把非[确定性验证](../concept-deterministic-verification/index.html)变成数学证明。

来源：§4.1 与 §5，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
