Una matrice $A$ , quadrata e di ordine $n$  è diagonalizzabile se , e solo se è simile a una matrice $D$ tale che $D$ è diagonale, ovvero:$$\exists P\in Mat_{n}(K):P\neq\underline{0} \text{ e }D=P^{-1}AP$$
Equivalentemente , $A$ è diagonalizzabile se, e solo se $K^{n}$ ammette una base $B$ di autovettori di $A$.

### DIM
Siano:
$$D=\begin{pmatrix}\lambda_{1} & 0 & \ldots & 0 \\ 0 & \lambda_{2} & \ldots & 0 \\ \vdots & \vdots & \ddots & \vdots \\ 0 & 0 & \ldots & \lambda_{n}\end{pmatrix}P=\begin{pmatrix}P_{1} & \ldots & P_{n}\end{pmatrix}$$

Dove $P_{1},\ldots,P_{n}$ sono le colonne della matrice $P$, e formano una base di $K^{n}$ in quanto la matrice $P$ è invertibile.
Calcoliamo i prodotti $AP$ e $PD$:$$AP=\begin{pmatrix}AP_{1} & \ldots & AP_{n}\end{pmatrix}$$
$$PD=\begin{pmatrix}\lambda_{1}P_{1} & \ldots & \lambda_{n}P_{n}\end{pmatrix}$$
Notiamo che $PD=AP\implies D=P^{-1}AP$ se e solo se $AP_{i}=\lambda_{i}P_{i}\space\forall i=1,2,\ldots,n$.
Questo è equivalente a dire che le colonne $P_{i}$ di $P$ devono essere autovettori di $A$ rispetto all'autovalore $\lambda_{i}$.
Quindi $P$, che ricordiamo è una base di $K^{n}$ , è formata da autovettori di $A$ e quindi la tesi è confermata.

**NB**: Da questo teorema traiamo due cose importanti:
1) La matrice diagonalizzante ha come colonne autovetttori di $A$.
2) La matrice digonale ha come elementi della diagonale principale gli autovalori di $A$.


### Caso n autovalori distinti
Se $A\in Mat_{n}(K)$ ha $n$ autovalori distinti , allora è diagonalizzabile.

#### DIM
Se $n$ sono gli autovalori allora $n$ sono gli autospazi e sono tutti di dimensione $1$.
Pertanto $K^{n}$ è somma diretta degli $n$ autospazi e una base di $K^{n}$ si ottiene tramite l'unione delle basi degli $n$ autospazi.

## Criterio di diagonalizabilità
Sia $A\in Mat_{n}(K)$ . Siano $\lambda_{1},\ldots,\lambda_{t}\in K$ tutti gli autovalori distinti di $A$ con le loro rispettive molteplicità algebriche $a_{\lambda_{i}}$ e le rispettive molteplicità geometriche $g_{\lambda_{i}}$ .
Allora $K^{n}$ ammette una base di autovettori di $A$ se e solo se tutti gli autovalori di $A$ sono regolari.

## DIM
Supponiamo che esista in $K^{n}$ una base $B$ di autovettori. 
$B$ rappresenta l'unione delle basi degli autospazi relativi agli autovalori di $A$, che sono in somma diretta, quindi:$$K^{n}=V_{\lambda_{1}}\oplus\ldots\oplus V_{\lambda_{t}}$$
Quindi $dim(K^{n})=n=g_{\lambda_{1}}+g_{\lambda_{2}}+\ldots+g_{\lambda_{t}}$ , e di conseguenza anche $a_{\lambda_{1}}+a_{\lambda_{2}}+\ldots+a_{\lambda_{t}}=n$ .

Dimostriamo che $\forall i$ $g_{\lambda_i}=a_{\lambda_{i}}$ .
Se esistesse un autovalore $\lambda_{i}$ non regolare , per il quale quindi $g_{\lambda_{i}}<a_{\lambda_{i}}$ , per avere una somma totale delle molteplicità geometriche di $n$ dovrebbe esistere un altro autovalore $\lambda_{j}$ con $g_{\lambda_{j}}>a_{\lambda_{j}}$ ma ciò è impossibile.

Viceversa, siano $\lambda_{1},\ldots,\lambda_{t}$ tutti e soli autovalori di $A$ e siano tutti regolari. 
Di conseguenza, la somma delle molteplicità algebriche e la somma delle molteplicità geometriche sono entrambe $n$.
Quindi la dimensione della somma dei relativi autospazi è $n$, perchè sono in somma diretta.
Unendo le basi degli autospazi otteniamo una base di $K^{n}$.

Argomento principale: [[Matrici]]
#algebra 