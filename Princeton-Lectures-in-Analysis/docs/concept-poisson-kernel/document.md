# Poisson 核

对 $0\le r<1$ ，Poisson 核定义为

$$P_r(\theta)=\sum_{n\in\mathbb Z}r^{|n|}e^{in\theta}=\frac{1-r^2}{1-2r\cos\theta+r^2}.$$

级数绝对且一致收敛。 $P_r$ 非负、积分归一，并在 $r\uparrow1$ 时把质量集中到 $\theta=0$ ，因此构成连续参数的好核。

第五章把它与上半平面 Poisson 核

$$P_y^{\mathbb H}(x)=\frac{1}{\pi}\frac{y}{x^2+y^2}$$

联系起来。Poisson 求和与参数 $r=e^{-2\pi y}$ 给出周期化公式

$$P_r(2\pi x)=\sum_{k\in\mathbb Z}P_y^{\mathbb H}(x+k).$$

所以圆盘核也可理解为上半平面核沿整数格点的周期化。

第二卷还以半圆留数计算 $\int_{\mathbb R}(1+x^2)^{-1}dx=\pi$，缩放后给出上半平面 Poisson 核积分为 $1$ 的另一证明。

**来源**：第一卷第 2 章 Example 5、Lemma 5.5，书页 37–38、55–56（PDF 54–55、72–73）；第一卷第 5 章 Theorem 3.5，书页 157–158（PDF 174–175）；第二卷第 3 章 Example 1，书页 78–79（PDF 物理页 423–424）。
