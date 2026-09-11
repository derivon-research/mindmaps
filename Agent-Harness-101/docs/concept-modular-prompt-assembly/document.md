# 模块化 Prompt 装配

模块化 Prompt 装配从多个独立 Fragment 渲染最终 [System Prompt](../concept-system-prompt/index.html)，使不同 Owner、更新周期、实验和租户数据可以局部变化。

装配系统必须定义顺序、冲突、转义与来源权限；XML 标签本身不能阻止注入。

来源：同章 §1、§6，revision 227。
