# 差分对随机 CMRR

电阻负载 MOST 差分对的随机 CMRR 近似为

`CMRRr = 2*gm*RB / (2*Delta VT/VOV + Delta RL/RL + Delta K'/K' + Delta(W/L)/(W/L))`。

`RB` 是尾电流源输出电阻。同一组失配项既产生输入失调，也把共模电流不等量地转换成差模输出；提高尾源输出电阻可提高低频 CMRR。源书示例以 `gm*RB=30`、`Delta RL/RL=1%` 得到约 6000，即 75 dB。

来源：第 15 章 pp. 429-430，1517-1519。

## 原书图示

![第 15 章 p. 429 的原书电路或分析图](../../assets/book-pages/book-page-0429.jpg)
