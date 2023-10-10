
Siano $U$ e $W$ due sottospazi di $V(K)$ , si dice somma di $U$ e $W$ :$$S= U+W=\{ u+w | u\in U,w\in W \}$$
#### NB:
La somma di due sottospazi vettoriali è anch'essa un sottospazio vettoriale.

## Somma diretta
Siano $U$ e $W$ due sottospazi di $V(K)$,il sottospazio somma di $U$ e $W$ è diretta e si scrive $S=U \oplus W$ se e solo se ogni elemento di $S$ si scrive univocamente come somma tra un elemento di $U$ e un elemento di $W$

Ovvero, la somma è diretta se , e solo se:$$U\cap W = \{\underline{0}\}$$
E quindi la [[Formula di Grassmann]] diventa:$$dim(U+W)=dim(U)+dim(W)$$
### DIM
Dimostriamo che in $S=U\oplus W$ i vettori  sono rappresentati univocamente, ovvero:$$u_{1}+w_{1}=u_{2}+w_{2}\iff u_{1}=u_{2}\space\land w_{1}=w_{2}$$
La tesi indica che $u_{1}-u_{2}=w_{2}-w_{1}$ e questo significa che  $u_{1}-u_{2}$ e $w_{2}-w_{1}$ per essere uguali devono appartenere a $U\cap W$ che per ipotesi sappiamo essere $U\cap W=\{\underline{0}\}$ 
Quindi abbiamo che :$$\begin{matrix}u_{1}-u_{2}= 0\implies & u_1=u_2 \\ w_2-w_{1}=0\implies & w_1=w_{2}\end{matrix}$$

### Sottospazi supplementari
Dato lo spazio vettoriale $V(K)$ e i due sottospazi $U$ e $W$ si dice che $U$ e $W$ sono supplementari se, e solo se:
$$V=U\oplus W$$ Questo vuol dire che ogni vettore di $V$ si scrive univocamente come somma di un vettore di $U$ e di un vettore di $W$.

Ogni sottospazio di dimensione **finita** ha un supplementare.

## Somme multiple di sottospazi
Sia $V(K)$ e siano $V_{1}\ldots V_{k}$ sottospazi di $V$ . 
Indichiamo con $V_{1}+\ldots+V_{k}$ il sottospazio somma:$$V_{1}+\ldots+V_{k}=\{ v_{1}+\ldots+v_{k}|v_{1}\in V_{1},\ldots,v_{k}\in V_{k} \}$$
Quindi ogni elemento del vettore somma si scrive come somma di elementi di ogni sottospazio. Se la rappresentazione è univoca si usa il simbolo $\oplus$ di somma diretta.

Argomento principale: [[Spazi vettoriali]]
#algebra 