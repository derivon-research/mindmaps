# Heisenberg 测不准原理

若  $\psi\in\mathcal S(\mathbb R)$  且  $\|\psi\|_2=1$  ，则对任意  $x_0,\xi_0$  ，

$$
\left(\int(x-x_0)^2|\psi(x)|^2dx\right)
\left(\int(\xi-\xi_0)^2|\widehat\psi(\xi)|^2d\xi\right)
\ge\frac1{16\pi^2}.
$$

平移和调制把中心化到零。对  $\int|\psi|^2$  分部积分，再用 Cauchy–Schwarz；微分对偶与 Plancherel 把  $\|\psi'\|_2^2$  化成  $4\pi^2\int\xi^2|\widehat\psi|^2$  。等号恰为高斯  $Ae^{-Bx^2}$  。

练习 21–23给出互补表述：非零函数与其 Fourier 变换不能同时紧支撑，质量主要区间的长度乘积至少  $1/(2\pi)$  ，Hermite 算子满足  $L\ge I$  。

第六章练习 6 给出  $\mathbb R^d$  的径向二阶矩版本：若  $\|\psi\|_2=1$  ，则

$$
\left(\int_{\mathbb R^d}|x|^2|\psi(x)|^2dx\right)
\left(\int_{\mathbb R^d}|\xi|^2|\widehat\psi(\xi)|^2d\xi\right)
\ge\frac{d^2}{16\pi^2}.
$$

**来源**：第一卷第 5 章 Theorem 4.1、练习 21–23，书页 158–161、167–169（PDF 175–178、184–186）；第 6 章练习 6，书页 209（PDF 226）。
