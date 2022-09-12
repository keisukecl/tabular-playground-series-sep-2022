![image](https://user-images.githubusercontent.com/98368198/189378838-5c5c2ebf-c03e-4a87-9b89-51bd0c421a89.png)


# tabular-playground-series-sep-2022


# Basics


## Overview

1月のTabular Playgroundで見たKaggleグッズの競合店が、またまた登場です。今回は、本を売っているのです

今月のコンペティションのタスクは少し複雑です。6つの国と4冊の本を予測するだけでなく、激動の2021年の売上を予測するよう求められています。あなたのデータサイエンス・スキルで、平時とはかけ離れた状況下での本の売れ行きを予測することができるでしょうか？

data
この課題では、6カ国にある2つの競合店の4つの商品について、1年分の売上を予測することになります。このデータセットは完全に架空のものですが、週末や祝日の効果、季節性など、現実のデータで見られる多くの効果を含んでいます。あなたには、2021年の書籍の売上を予測するという難しい課題が与えられています。

### train.csv colomn infomaiton
notebook：https://www.kaggle.com/code/vencerlanz09/tps-eda-9-models-explanation

|name|Explanation|
|----|----|
|date|日付。yyyy/mm/ddで記述。2017/1/1～2020/12/31まで|
|countly|国。Belgium・France・Germany・Italy・Poland・Spainの6か国|
|store|書店。KaggleMartとKaggleRamaの2つ|
|product|本の名前。Kaggle Advanced Techniques・Kaggle Getting Started・Kaggle Recipe Book・Kaggle for Kids: One Smart Gooseの4冊|
|num_sold|売れた数|


## Log
### 2022/09/10
- join!
- 日記を作成
- 2017年～2020年のデータを使って2021年1年間の各書店の本の売れた数を推定する。曜日や祝日・天気や季節だけでなくコロナの影響を考慮しないといけない。
- 2021年はワクチン普及のタイミングがキーになる気がする。


### 2022/09/12
- 以下の動画が役立つらしい

Tutorial #1: https://www.youtube.com/watch?v=vV12dGe_Fho

Tutorial #2: https://www.youtube.com/watch?v=z3ZnOW-S550

-nb1ではデータの階層構造を活用方法が、nb2では販売/需要予測への一般的なアプローチが記載
