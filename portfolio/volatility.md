# Histolical Volatility - HV

標本標準偏差

不偏推定値を得るためにT-1で除す。

https://physnotes.jp/stat/unb_est/

* nで割る分散(母集団の分散σ^2 population varianceや標本の分散s^2 sample variance)という定義と 
* n - 1 で割る分散(不偏分散u^2 - unbiased dispersion)という定義の両方が存在

* 母集団が対象ならばσ^2を用いて, 標本が対象で標本の数nが小さいならばu^2を用いるべきで,
 が大きいならばu^2とs^2の違いは僅かであるからどちらでも大きな違いが生じない
 

```
HV = √{(1/(T-1)) * Σ(R_t - R_bar)^2}
```

年率換算HV = √250 * HV

```
R_bar(日次リターンの算術平均) = (1/T)Σ(R)
```
