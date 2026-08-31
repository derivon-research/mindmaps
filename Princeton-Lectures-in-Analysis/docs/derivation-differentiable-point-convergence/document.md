# 差商与 Riemann–Lebesgue 证明可微点收敛

利用 $S_N(f)=f*D_N$ 与 $\int D_N=2\pi$ ，把误差写成

$$\frac1{2\pi}\int F(t)\,tD_N(t)\,dt,$$

其中 $F(t)=[f(\theta_0-t)-f(\theta_0)]/t$ 。一点可微性使 $F$ 在原点附近有界且整体可积； $tD_N(t)$ 可拆成可积振幅乘 $\sin Nt$ 、 $\cos Nt$ 。Riemann–Lebesgue 引理使两项趋零。

**认知成本：3.5/5**。关键是构造差商并消除 Dirichlet 核在零点的奇性。**来源**：Theorem 2.1，书页 81–82（PDF 98–99）。
