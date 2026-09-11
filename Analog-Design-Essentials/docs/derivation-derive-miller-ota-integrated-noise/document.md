# 消去输入跨导得到补偿电容噪声律

把输入白噪声 `proportional kT/g_m1` 乘以 `(pi/2)GBW`，再代入 `GBW=g_m1/(2pi C_c)`，`g_m1` 消去，积分噪声只按 `kT/C_c` 缩放。

来源：第 6 章 pp. 206-208，0648-0651。边权 3：需联合输入噪声、等效噪声带宽和 Miller GBW 完成消元。

## 原书图示

![第 6 章 p. 206 的原书电路或分析图](../../assets/book-pages/book-page-0206.jpg)
