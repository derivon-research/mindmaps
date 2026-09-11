# Workflow Metadata

Workflow Metadata 是脚本开头的静态 meta 字面量，声明名称、描述和可能经历的 Phase。

Runtime 在执行前读取它以生成说明和进度分组；变量引用、函数调用与模板插值不适合放入该静态声明。其角色接近 [Skill](../concept-skill/index.html) Frontmatter，但不参与运行时控制流。

来源：§2 与 §3，revision 1503。
