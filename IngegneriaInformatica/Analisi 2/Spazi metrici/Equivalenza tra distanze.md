Siano $(X,d_{1})$ e $(X,d_{2})$ spazi metrici, allora $d_{1}$ e $d_{2}$ sono funzioni distanze **equivalenti** se e solo se:$$\exists c,C >0 : \forall x,y\in X \space cd_{1}(x,y)\le d_{2}(x,y)\le Cd_{1}(x,y)$$
#### prop 
Siano $(X,d_{1})$ e $(X,d_{2})$ spazi metrici, allora $d_{1}$ è equivalente a $d_{2}$ se, e solo se, $d_{2}$ è equivalente a $d_{1}$.
##### DIM
$\implies$) Sappiamo che: $$\exists c,C >0 : \forall x,y\in X \space cd_{1}(x,y)\le d_{2}(x,y)\le Cd_{1}(x,y)$$
Prendiamo $cd_{1}(x,y) \le d_{2}(x,y)$ , dividiamo per $c$ :$$\frac{1}{c}d_{2}(x,y) \ge d_{1}(x,y)$$
Prendiamo $d_{2}(x,y) \le Cd_{1}(x,y)$, dividiamo per $C$:$$\frac{1}{C}d_{2}(x,y)\le d_{1}(x,y)$$
Quindi:$$\exists B= \frac{1}{c}>0, b=\frac{1}{C}>0: bd_{2}(x,y) \le d_{1}(x,y)\le Bd_{2}(x,y)$$
Eseguiamo lo stesso procedimento invertendo $d_{1}$ e $d_{2}$ e abbiamo verificato la tesi.

Argomento principale: [[Spazi metrici]]
Vedi: [[Funzione distanza]]
#analisi2