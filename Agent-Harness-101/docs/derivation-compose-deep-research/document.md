# 多轮 ReAct 加搜索与抓取得到 Deep Research 雏形

## 推导

[多轮 ReAct](../concept-multiround-react/index.html) 提供运行时调整路径的控制骨架；Web Search 发现候选来源；Web Fetch 读取选定页面。模型可 Search → Fetch → 根据正文形成新查询 → 再 Search/Fetch，直到信息足够并[主动停机](../concept-active-halting/index.html)。这正是本章给出的 Deep Research 雏形。

三个前提缺一不可：没有多轮就不能依据新信息转向；没有 Search 难以发现来源；没有 Fetch 只能停留在摘要。

## 学习成本

权重 2.5：这是短而完整的工具组合，需要理解交错轨迹但无需新算法。

来源：同章 §4，revision 2846。
