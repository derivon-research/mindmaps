# 多轮 ReAct 接入代码工具得到 Coding Agent

## 推导

[多轮 ReAct](../concept-multiround-react/index.html) 允许后一步依据前一步结果行动；[Coding Agent 工具集](../concept-coding-toolset/index.html)提供读源码、写修改与运行测试的动作。二者组合后，模型可执行“测试失败 → 读文件定位 → 写入修复 → 重跑验证”的代码变更闭环。

这说明 Agent 形态主要由工具选择塑造，而 Loop 骨架可保持通用。

## 学习成本

权重 2.0：是短标准组合，但读者需把研究型轨迹迁移到代码状态与验证反馈。

来源：同章 §6，revision 2846。
