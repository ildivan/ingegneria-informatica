Sia $f: R^{n}\to R^{m}$ e sia $f$ lineare.
Allora valgono:
1) $f$ è continua su $R^{n}$ 
2) $f$ è di lipschitz
3) $f$ è differenziabile in $R^{n}$ 
#### DIM
Per linearità di $f$ definiamo:$$M \in R^{m \times n} \space \forall x \in R^{n} \space f(x)=Mx$$
Vale $\forall x_{1},x_{2}\in R^{n}$:$$||f(x_{2})-f(x_{1})|| = ||Mx_{2}-Mx_{1}|| = ||M(x_{2}-x_{1})||\le||M|| \space||x_{2}-x_{1}||$$
Dove $||M||$ è la norma operatoriale di $M$ , e rappresenta la costante di Lipschitzianità di $f$, quindi abbiamo dimostrato il punto 2.
Sappiamo che una funzione di lipschitz è anche continua, quindi anche il punto 1 è dimostrato.

Ora dimostriamo la differenziabilità:$$f(x_{0}+h)-f(x_{0}) = M(x_{0}+h)-Mx_{0}= Mh + 0= Mh + o(h)$$
Quindi:$$Df(x_{0})=M=f$$
**NB** : Non c'è scritto $Df(x_{0}) = f(x_{0})$ ma $Df(x_{0})=f$ 

Argomento principale: [[Derivata completa e differenziabilità]]
Vedi: [[Funzioni di Lipschitz]],[[Applicazioni lineari]],[[Applicazioni lineari definite da una matrice]],[[Continuità di funzioni in spazi metrici]],[[Norma operatoriale]]
#analisi2 