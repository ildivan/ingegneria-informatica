Sia $(X,d)$ uno spazio metrico e sia $T: X \to X$ una [[Contrazione]].
Se $(X,d)$ è uno [[Spazio metrico completo]] , allora $T$ ammette un solo punto fisso:$$(X,d) \text{ è completo } \implies \exists ! x_{\star} \in X : Tx_{\star} = x_{\star}$$
#### DIM
Definiamo la successione:$$x_{n+1} = Tx_{n} \text{ con } n \ge 0$$
Dimostriamo che è una successione di Cauchy:
Sia $d(x_{m},x_{n})$ con $m > n$ , troviamo per definizione di $T$ che :$$d(x_{m},x_{n}) = d(Tx_{m-1},Tx_{n-1}) \le Kd(x_{m-1},x_{n-1})$$
Continuando in questo modo:$$= Kd(Tx_{m-2},Tx_{n-2}) \le K^{2}d(x_{m-2},x_{m-2}) = \ldots \le K^{n}d(x_{m-n},x_{0})$$
Per la proprietà di disuguaglianza triangolare della funzione distanza otteniamo che:$$\le K^{n}[d(x_{0},x_{1})+ d(x_{1},x_{2})+\ldots+d(x_{m-n-1},x_{m-n})]$$
Per le precedenti disuguaglianze:$$\le K^{n}[d(x_{0},x_{1})+Kd(x_{0},x_{1})+\ldots + K^{m-n}d(x_{0},x_{1})]$$$$= K^{n}d(x_{0},x_{1})(1 + K+K^{2}+\ldots+K^{m-n})$$$$= K^{n}\frac{1-K^{m-n}}{1-K}d(x_{0},x_{1}) \le K^{n}\frac{d(x_{0},x_{1})}{1-K}$$
Dato che per $n \to +\infty$ $K^{n}\frac{d(x_{0},x_{1})}{1-K}$ va a $0$ ed è decrescente, siamo sempre in grado di trovare, dato $\epsilon >0$,  un valore $p \in N$ tale che per ogni $n,m > p$ allora:$$d(x_{n},x_{m})<\epsilon$$ Quindi è dimostrato che la successione è di Cauchy, di conseguenza essa ammette limite:$$\lim_{n \to +\infty} x_{n}= x_{\star}$$
Troviamo il valore di $Tx_{\star}$:$$Tx_{\star} = T \lim_{n \to+\infty}x_{n}= \lim_{n \to +\infty}Tx_{n}=\lim_{n \to +\infty}x_{n+1}= x_{\star}$$
Abbiamo dimostrato l'esistenza del punto fisso di $T$.
Ora dimostriamone l'unicità, supponiamo l'esistenza di due punti fissi:$$x_{\star}= Tx_{\star} \space \space y_{\star}=Ty_{\star} \text{ dove } x_{\star},y_{\star}\in X$$$$d(x_{\star},y_{\star})=d(Tx_{\star},Ty_{\star}) \le Kd(x_{\star},y_{\star})$$$$d(x_{\star},y_{\star}) - Kd(x_{\star},y_{\star}) \le 0$$$$(1-K)d(x_{\star},y_{\star}) \le 0 \implies d(x_{\star},y_{\star}) = 0 \implies x_{\star}=y_{\star}$$

Argomento principale: [[Spazi metrici]]
Vedi: [[Successioni di Cauchy]],[[Funzione distanza]],[[Limite di una successione in spazio metrico]]
#analisi2 