Sia $(X,d)$ uno spazio metrico e sia $x: N \to X$ una successione
Il limite di $x_{n}$ per $n$ che tende a $+\infty$ è **unico.**

#### DIM
Siano $l,L\in X$ tali che:$$\lim_{n \to +\infty}x_{n}=l,\lim_{n \to +\infty}x_{n}=L$$
Dimostriamo che $l=L$, 
per definizione di limite abbiamo:$$\forall \epsilon> 0 \space\exists \nu'\in N : \forall n > \nu \space d(x_{n},l)<\epsilon$$$$\forall \epsilon> 0 \space\exists \nu''\in N : \forall n > \nu \space d(x_{n},L)<\epsilon$$
Per proprietà della funzione distanza:$$d(l,L)\le d(l,x_{n}) + d(L,x_{n}) < 2\epsilon \space \space \forall \epsilon>0 \space\forall n > \max\{\nu', \nu''\}$$
Quindi:$$d(l,L) = 0 \implies l=L$$
La tesi è verificata.

Argomento principale: [[Successioni in spazi metrici]]
Vedi: [[Teorema di unicità del limite]]
#analisi2 