# Version Boundary Reminder

[Version Boundary](../concept-version-boundary/index.html) Reminder 是 Harness 在版本切换后、下一次模型调用前注入的系统级说明，列出变化对象、失效历史、当前事实源和继续前必须重查的内容。

它不复制完整 Schema，以免自身再次过期；具体 system-reminder XML 标签没有魔法，真正权限来自消息层级和注入位置。

来源：§4-5，revision 270。
