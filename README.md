# Yusuke Kato Pages

https://YusukeKato.github.io

# About

- 名前：加藤祐介
- 大学：千葉工業大学（工学部）卒業
- 好きなもの：ロボット、ゲーム、小説など
- 趣味：小説執筆、競技プログラミングなど

# Links

- [GitHub : YusukeKato](https://github.com/YusukeKato)
- [Twitter : y_kato222](https://twitter.com/y_kato222)
- [YouTube : ykato](https://www.youtube.com/channel/UC4TaLIvjTNPjPys2AZjP3Rw)
- [HatenaBlog : YKpages](https://kato-robotics.hatenablog.com/)
- [Qiita : ykpages](https://qiita.com/ykpages)
- [カクヨム : yusuke_kato](https://kakuyomu.jp/users/yusuke_kato)
- [AtCoder : yusuke_kato](https://atcoder.jp/users/yusuke_kato)
- [競技プログラミングの痕跡](https://github.com/YusukeKato/ProgrammingContest)
- [日記](https://yusukekato.github.io/Diary/)

# Portfolio

## 2022

### 円周率シェル芸

- [シェル芸のトップページ](https://b.ueda.tech/?page=01434)
- [ツイートのリンク](https://twitter.com/y_kato222/status/1598610852621750272)

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

### 四角回転シェル芸

- [シェル芸のトップページ](https://b.ueda.tech/?page=01434)
- [ツイートのリンク](https://twitter.com/y_kato222/status/1598470274797948928)

```sh
convert -size 283x283 xc:#FF0000 b.png; for i in {0..8}; do convert -size 200x200 xc:#FF0000 -rotate -$((i*10)) i$i.png; convert b.png i$i.png -gravity northeast -composite o$i.png; done; convert -layers optimize -loop 0 -delay 10 /o*.png /images/a.gif
```

![](./Images/2022_0001.gif)

## 2021

### 小説執筆

- [作品](https://kakuyomu.jp/works/16817139555084509589)

## 2020

### ROBOMECH2020

- ポスター発表
- 加藤祐介, 上田隆一: ARツールを用いたオドメトリのキャリブレーションシステムにおけるマーカのズレ量の計測法, ROBOMECH, A1-L03, 2020.
- [上田先生のツイート](https://twitter.com/ryuichiueda/status/1265821330210844672?s=20&t=R7OWe-eFsEOo5R7ZXSyC4A)

## 2019

### ROBOMECH2019

- ポスター発表
- 加藤祐介, 上田隆一: ARツールを用いたオドメトリのキャリブレーションシステム, ROBOMECH, 1A1-Q04, 2019.

### ARを用いたロボットのキャリブレーション

- ロボットの移動経路を計測してモータの出力を調整
- Unity, ROS
- [動画](https://youtu.be/QYnU6PeEx8s)
- [GitHub(ROS)](https://github.com/YusukeKato/raspimouse_odometory_tuning_ros)
- [GitHub(Unity)](https://github.com/YusukeKato/raspimouse_odometry_tuning_unity)

![](./Images/2019_0004.gif)

### 押印ロボット

- 四人で開発（私は画像作成担当）
- ROS, Twitter API
- [詳細情報](https://kuwamai.github.io/2019/12/15/hanko_robot.html)

![](./Images/2019_0001.jpg)

### ゲーム『オシャレなロケット』

- 開発途中のゲーム
- Unity(C#)

![](./Images/2019_0002.png)

![](./Images/2019_0003.png)

## 2018

### ROBOMECH2018

- ポスター発表
- 加藤祐介, 上田隆一, 中川友紀子: 拡張現実を用いたロボットの距離センサ検査システム, ROBOMECH, 2P2-l13, 2018.

### ARを用いた距離センサの検査

- センサ値を可視化して検査を効率化
- Unity, ROS
- [動画](https://youtu.be/CPMrsBE1d30)

![](./Images/2018_0001.png)

### テレプレゼンスロボット

- ロボットの目線で操縦
- Unity, ROS
- [動画](https://youtu.be/46ishQiM4o0)

![](./Images/2018_0002.png)

## 2017

## 2016

### 木製ライントレーサー

- 三人で開発（私はソフトウェア担当）
- C言語、Arduino

![](./Images/2016_0003.jpg)

![](./Images/2016_0004.jpg)

### ロボットハンド

- 設計と加工の授業にて製作
- Inventorと加工機
- チェスの駒を把持

![](./Images/2016_0002.jpg)

### チェス

- ターミナル上で遊べるチェス
- C言語
- [GitHub : ソースコード](https://github.com/YusukeKato/chess_robot)

![](./Images/2016_0001.png)

## 2015

### 初めて作成したゲーム

- 青いネズミを操作して迷路から脱出
- C言語とOpenGLで作成
- [YouTube : 動画](https://youtu.be/X-wTG_04Z1w)

![](./Images/2015_0001.png)
