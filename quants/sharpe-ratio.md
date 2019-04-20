
# Sharpe Ratio

Generally, a Sharpe Ratio of near 1.0 or higher is an acceptable single alpha for this universe.

```
daily_annualization_factor = np.sqrt(252)
(daily_annualization_factor * ls_factor_returns.mean() / ls_factor_returns.std()).round(2)
```
