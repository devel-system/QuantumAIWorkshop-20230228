## 量子・AIハイブリッドの基礎を学習するセミナー

### 初期設定
1. python の環境を用意。（Anaconda でも可）
2. `win.bat` または `./mac.sh` を実行（環境に合わせてください。python のパッケージがダウンロードされます。）

### Part1
量子アニーリングを簡単に使ってみる。

以下の地図で s から g に行くための最短経路を考える。
```
s -> 1 -> g
     ↓
     2
```

Google Colab でも試すことができます。
https://colab.research.google.com/drive/14lPDy6d7z3paacHcERqpI7ETmsmmlP7j?usp=sharing

### Part2
交通最適化問題を量子アニーリングと古典AIを用いて解いてみる。

**古典AI**\
曜日と時刻から回帰分析を用いて混雑度を予測。

**量子アニーリング**\
一定以上混雑している場合は別の経路を提案する。

**背景**\
現在のカーナビシステムでは、基本的に出発地点から目的地点までの最短経路が提案される。この経路は個人にとって最適な経路である。\
しかし、全員が最短経路を選択すると、交通混雑が引き起こされ全体の旅行時間（目的地点までに要する時間）が多くなる可能性がある。

**目的**\
交通混雑を緩和したい。

**課題**\
交通混雑を予想して、混雑が見込まれる場合は経路を変更させる。

Google Colab でも試すことができます。
https://colab.research.google.com/drive/1i8cCGeaL8Sdju1x1Aty6uCMhL20SKFRq?usp=sharing

---
**動作環境**\
Windows, MacOS

**開発**\
DEVEL株式会社、ビネット＆クラリティ合同会社