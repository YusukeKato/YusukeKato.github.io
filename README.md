# Yusuke Kato Pages

https://YusukeKato.github.io

# About

- 名前：加藤祐介
- 大学：千葉工業大学（工学部）卒業
- 好きなもの：ロボット、ゲーム、小説など

# Links

- [GitHub : YusukeKato](https://github.com/YusukeKato)
- [Twitter : y_kato222](https://twitter.com/y_kato222)
- [YouTube : ykato](https://www.youtube.com/channel/UC4TaLIvjTNPjPys2AZjP3Rw)
- [HatenaBlog : YKpages](https://kato-robotics.hatenablog.com/)
- [Qiita : ykpages](https://qiita.com/ykpages)
- [カクヨム : yusuke_kato](https://kakuyomu.jp/users/yusuke_kato)
- [AtCoder : yusuke_kato](https://atcoder.jp/users/yusuke_kato)
- [競技プログラミングの痕跡](https://github.com/YusukeKato/ProgrammingContest)
- [日記](https://github.com/YusukeKato/YusukeKato.github.io/tree/main/diary)

# Portfolio

## 2022

### 円周率シェル芸

```sh
python -c "
from decimal import Decimal as D
from decimal import *
getcontext().prec=999
a=D(1)
b=D(1)/D(2).sqrt()
t=D(0.25)
p=D(1)
for i in range(999):
 e=(a+b)/D(2);f=(a*b).sqrt();g=t-p*(a-e)**2;h=D(2)*p;a=e;b=f;t=g;p=h
print((a+b)**2/(D(4)*t))" | cowsay | textimg -s
```

![](./Images/2022_0001.png)

## 2016

### チェス

- ターミナル上で遊べるチェス
- C言語

![](./Images/2016_0001.png)

## 2015

### 初めて作成したゲーム

- 青いネズミを操作して迷路から脱出
- C言語とOpenGLで作成

![](./Images/2015_0001.png)

[YouTube](https://youtu.be/X-wTG_04Z1w)
