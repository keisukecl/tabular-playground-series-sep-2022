![image](https://user-images.githubusercontent.com/98368198/189378838-5c5c2ebf-c03e-4a87-9b89-51bd0c421a89.png)


# tabular-playground-series-sep-2022


# Basics


## Overview

1月のTabular Playgroundで見たKaggleグッズの競合店が、またまた登場です。今回は、本を売っているのです

今月のコンペティションのタスクは少し複雑です。6つの国と4冊の本を予測するだけでなく、激動の2021年の売上を予測するよう求められています。あなたのデータサイエンス・スキルで、平時とはかけ離れた状況下での本の売れ行きを予測することができるでしょうか？

data(deepL)
この課題では、6カ国にある2つの競合店の4つの商品について、1年分の売上を予測することになります。このデータセットは完全に架空のものですが、週末や祝日の効果、季節性など、現実のデータで見られる多くの効果を含んでいます。あなたには、2021年の書籍の売上を予測するという難しい課題が与えられています。

### train.csv colomn infomaiton


|name|Explanation|
|----|----|
|date|日付。yyyy/mm/ddで記述|
|countly|国。Belgium・France・Germany・Italy・Poland・Spainの6か国|
|store|書店。KaggleMartとKaggleRamaの2つ|
|product|本の名前。Kaggle Advanced Techniques・Kaggle Getting Started・Kaggle Recipe Book・Kaggle for Kids: One Smart Gooseの4冊|
|num_sold|売れた数|
