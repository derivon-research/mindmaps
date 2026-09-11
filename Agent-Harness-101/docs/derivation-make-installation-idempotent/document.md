# 目标状态与现有配置保护建立 Idempotent Installation

Desired-State Prompt 要求趋向最终状态；Read-Before-Write 获取当前配置；[Install Operating Rules](../concept-install-operating-rules/index.html) 禁止无授权覆盖。三者共同建立 [Idempotent Installation](../concept-idempotent-installation/index.html)。

权重 3.0：重跑必须根据真实状态收敛而非重复动作。来源：同章 §2.4、§3.2，revision 118。
