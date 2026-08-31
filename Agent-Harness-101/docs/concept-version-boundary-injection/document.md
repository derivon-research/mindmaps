# Version Boundary 注入时机

[Version Boundary](../concept-version-boundary/index.html) 注入时机紧贴版本切换、位于最新 User Prompt 之前，并早于下一次模型调用，使旧轨迹先出现、边界随后重新定性、当前请求最后到达。

版本未变时不应反复注入同一提醒。

来源：§4，revision 270。
