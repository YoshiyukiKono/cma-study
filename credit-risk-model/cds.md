# Credit Default Swap

## リスク中立確率(risk-neutral probability)を用いたCDS価格の計算

残存期間1年額面100円の割引債

* リスク中立デフォルト確率: 3%
* デフォルト時損失率(LGD rate): 50%
* リスクフリーレート: 0.01

期待キャッシュフローをリクすフリーレートで割り引いた割引現在価値と求める
```
[(0.03 * (100 * 50%)) + ((1 - 0.03) * 0)] / 1 + 0.01
```
