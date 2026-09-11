# 破坏性契约变更

破坏性契约变更使旧调用或输出不再满足当前定义，例如同名 weather_report 的必填参数由 location 替换为 city_code，或响应格式由 Markdown 改为 JSON。

能避免时应优先保持兼容；无法避免且又保留长 Context 时才需要额外迁移措施。

来源：§1、§3 与 §6，revision 270。
