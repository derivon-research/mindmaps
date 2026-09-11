# 并行版本隔离

并行版本隔离让新旧 Tool 契约使用不同名称，例如 weather_report 与 weather_report_v2。旧 Context 即使模仿旧调用，也不会误用同名的新参数定义。

它更适合 Tool；Prompt 与模型迁移往往难以只靠改名隔离。

来源：§6，revision 270。
