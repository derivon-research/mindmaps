# Verification Prompt

Verification Prompt 用自然语言 Rubric 描述一次 `agent()` 调用的准出条件。

Worker 每产出一版结果就据此检查；未通过时继续搜索、反思和修正，直到达标才向外层脚本返回。它把局部质量门槛与任务 Prompt 分开表达。

来源：§4.1，revision 927，https://my.feishu.cn/wiki/ToaRw8BAUiAyFFkR3EAc05atnsg
