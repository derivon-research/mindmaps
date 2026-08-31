# 写前读取与精确匹配建立局部编辑安全性

[写前读取](../concept-read-before-write/index.html)取得真实状态；[精确匹配编辑](../concept-exact-match-edit/index.html)把该片段作为前置条件。两者减少全文件重生成和错误位置替换。

权重 3.0：Old String 兼具乐观并发前置条件。来源：同章 §6-8，revision 310。
