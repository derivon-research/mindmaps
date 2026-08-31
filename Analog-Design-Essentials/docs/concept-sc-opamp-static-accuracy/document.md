# 开关电容运放静态精度

反馈因子为 `alpha` 时，闭环增益约 `1/alpha`，环路增益为 `alpha*A0`，静态相对误差近似 `epsilonS=1/(alpha*A0)`。因此要求

`A0 > 1/(alpha*epsilonS)`。

源书例中 `alpha=0.2`、`epsilonS=0.05%` 给出最低 `A0=10^4`；考虑开环增益不确定性后采用 3-5 倍裕量，约需 90 dB。

来源：第 17 章 pp. 512-514，图 17.55-17.57。

## 原书图示

![第 17 章 p. 512 的原书电路或分析图](../../assets/book-pages/book-page-0512.jpg)
