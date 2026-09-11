# Fourier 反演公式

若 $f\in\mathcal S(\mathbb R)$ ，则

$$f(x)=\int_{-\infty}^{\infty}\widehat f(\xi)e^{2\pi ix\xi}\,d\xi.$$

先把乘法公式用于 $f$ 与伸缩高斯：一侧由好核趋于 $f(0)$ ，另一侧由高斯因子趋于 $1$ 得 $f(0)=\int\widehat f$ 。再平移 $f$ 得一般 $x$ 。

若 $f$ 与 $\widehat f$ 都适度衰减，同一结论仍成立。练习 1 还给出平行路线：在越来越长的区间展开 Fourier 级数，并让 Riemann 和趋于 Fourier 积分。

第二卷第 4 章对适度衰减全纯条带类 $\mathcal F$ 给出独立复分析证明：把正负频率半轴化为实轴上下的 Cauchy 线积分，再以矩形留数合并。

**来源**：第一卷第 5 章 Theorem 1.9、§1.7、练习 1，书页 141–144、161–162（PDF 158–161、178–179）；第二卷第 4 章 Theorem 2.2，书页 115–118（PDF 物理页 460–463）。
