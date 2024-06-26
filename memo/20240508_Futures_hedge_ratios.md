## Futures hedge ratios: a review
[Sheng-Syan Chen, Cheng-few Lee, Keshab Shrestha 2003](http://dx.doi.org/10.1016/S1062-9769(02)00191-6)

### 要点
- 現物ポジションを先物でヘッジする場合のヘッジ比率についてのレビュー
- 現物、先物の価格過程があるモデルに従うとした場合に、主にリスクと期待リターンを使用した目的関数を定義して最適なヘッジ比率を計算する
    - 最小分散、期待効用最大化など
- 価格がマルチンゲールで正規分布に従う場合、どのアプローチでも最適ヘッジ比率は同じ
- 価格にドリフトがあったり、リターン分布が正規分布でなかったり、非定常な場合（つまり普通は）アプローチによって最適ヘッジ比率が異なる。

### 感想
- 参考文献のサマリーと問題の定式化がappendixによくまとまっている
- 現実的には実データをフィットする過程をどうすべきか検証の上、どの意味でヘッジしたいのか理解しておく必要がある。
    - とはいえ、モデル選択よりもフィットに使用する過去データの範囲等のほうがよほど影響が大きいようにも思える。
    - 実データを用いて要比較

