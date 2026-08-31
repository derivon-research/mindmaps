# AFS-Sandbox 分层

AFS-[Sandbox](../concept-sandbox/index.html) 分层把资源访问交给 AFS，再按任务需要叠加 WASM/Isolate、MicroVM 或 Container 执行层；上层通过同一 Mount Tree 访问数据。

来源：同章 §5，revision 216。
