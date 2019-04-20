# Back Testing

## Profit-and-Loss (PnL) attribution (TODO)

Profit and Loss is the aggregate realized daily returns of the assets, weighted by the optimal portfolio holdings chosen, 
and summed up to get the portfolio's profit and loss.

The PnL attributed to the alpha factors = the factor returns x factor exposures for the alpha factors.  

$$
\mbox{PnL}_{alpha}= f \times b_{alpha}
$$

the PnL attributed to the risk factors = the factor returns x factor exposures of the risk factors.

$$
\mbox{PnL}_{risk} = f \times b_{risk}
$$

--
<img src="https://latex.codecogs.com/gif.latex?X[n]&space;=&space;\sum_{k=0}^{N-1}x[k]\exp({-j\frac{2&space;\pi&space;nk}{N}})"/>

を計算します。  

次に
<img src="https://latex.codecogs.com/gif.latex?\inline&space;X[n]&space;\in&space;\mathbb{C}" />
の絶対値を計算することで  
<img src="https://latex.codecogs.com/gif.latex?\inline&space;x[k]" />
に含まれる周波数
<img src="https://latex.codecogs.com/gif.latex?\inline&space;F_s\frac{n}{N}" />
の振幅を得ることができます。
