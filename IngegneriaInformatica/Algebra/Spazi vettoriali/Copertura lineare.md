Sia $V(K)$ uno spazio vettoriale e sia $X \subseteq V(K)$ , si dice copertura lineare (o span) di $X$ l'insieme:$$L(X) = \{\sum\limits_{i=1}^{n}\alpha_{i}x_{i} | x_{i}\in X, \alpha_{i}\in K,n\in N\}$$
$L(X)$ è l'insieme di tutte le combinazioni lineari di un numero finito di elementi di $X$.

#### TEO:
$L(X)$ è il più piccolo sottospazio di $V(K)$ che contiene $X$ .
##### DIM:
Sia $W \le V(K)$ e $X\subseteq W$ ,
allora ogni combinazione lineare di elementi di $X$ in numero finito deve essere contenuta in $W$:$$L(X)\subseteq W$$
Dimostriamo che $L(X)$ è uno spazio vettoriale.
Siano $v_{1},v_{2}$ elementi di $L(X)$:$$\begin{matrix} \overline{v_{1}} = \sum\limits_{i=1}^{n}\alpha_{i}\overline{x_{i}} \\ \overline{v_{2}}=\sum\limits_{j=1}^{m}\alpha_{j}\overline{x_{j}} \end{matrix}$$
Usiamo le condizioni di chiusura:$$\beta\overline{v_{1}}+\mu\overline{v_{2}} = \beta\sum\limits_{i=1}^{n}\alpha_{i}\overline{x_{i}} + \mu\sum\limits_{j=1}^{m}\alpha_{j}\overline{x_{j}} = \sum\limits_{i=1}^{n}\beta\alpha_{i}\overline{x_{i}} + \sum\limits_{j=1}^{m}\mu\alpha_{j}\overline{x_{j}}$$
Come si può notare è combinazione lineare di massimo $m+n$ vettori di $X$ , quindi è ancora elemento di $L(X)$ , e quindi:$$L(X)<V(K)$$
L'insieme vuoto $\emptyset$ ha copertura lineare $L(\emptyset)=\{\underline{0}\}$  

Argomento principale: [[Spazi vettoriali]]
Vedi: [[Sottospazi vettoriali]],[[Combinazione Lineare]]
#algebra