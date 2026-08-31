# 用 Fourier 变换求解实线热方程

对空间变量作变换，微分对偶把  $u_{xx}$  变为  $-4\pi^2\xi^2\widehat u$  ，于是固定  $\xi$  后解 ODE 得
 $\widehat u(\xi,t)=A(\xi)e^{-4\pi^2t\xi^2}$  。初值给  $A=\widehat f$  ，反演并用卷积定理识别为  $f*H_t$  。高斯好核给一致恢复，Plancherel 给均方恢复。

**认知成本：3/5**。把 PDE、频率 ODE、初值、反演和两种收敛串起来。**来源**：第一卷第 5 章 Theorem 2.1，书页 146–147（PDF 163–164）。
