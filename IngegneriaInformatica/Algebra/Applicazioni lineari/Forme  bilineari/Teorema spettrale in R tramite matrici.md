Ogni matrice simmetrica $A\in Mat_{n,n}(R)$ è ortogonalmente diagonalizzabile, ovvero esiste una matrice $P$ ortogonale tale che $P^{-1}AP$ è diagonale.

### DIM
Sia $A$ una matrice simmetrica di grado $n$ a coefficienti  reali, consideriamo l'applicazione:
$L_{A}:R^{n}\to R^{n}$
$L_{A}(x)=Ax$

$L_{A}$ è un endomorfismo simmetrico rispetto al prodotto scalare canonico, dunque per il [[Teorema spettrale in R tramite endomorfismi]] esiste una base ortonormale di $R^{n}$ formata da autovettori di  $L_{A}$.
Sia essa: $B=\{u_{1},\ldots,u_{n}\}$

Inoltre, l'esistenza di una base di autovettori ci assicura  che $L_{A}$ è diagonalizzabile.
Di conseguenza $A$ che è la matrice rappresentativa di $L_{A}$ sarà una matrice diagonalizzabile, e la matrice diagonalizzante $P$ è composta dai vettori di $B$ come colonne.

Quindi ora sappiamo che $P^{-1}AP$ è diagonale, dimostriamo ora che $P$ è ortogonale, ossia che:$$P^{T}P=Id_{n}= PP^{T}$$
L'elemento nella posizione $(i,j)$ della matrice $P^{T}P$ è dato dalla $i$-esima riga di $P^{T}$ o equivalentemente $u_{i}$, e dalla $j$-esima colonna di $P$ o equivalentemente $u_{j}$.
$$P^{T}P_{ij}=(u_{i})^{T}u_{j}=u_{i}\cdot u_{j}$$
Essendo $B$ una base ortonormale, allora:$$u_{i}\cdot u_{j}=\begin{cases}0 \text{ se }i\neq j  \\
1 \text{ se }i=j\end{cases}\implies P^{T}P = Id_{n}$$
Quindi possiamo affermare che $P$ è una matrice invertibile con inversa $P^{-1}=P^{T}$ , per cui $PP^{T}=Id_{n}$

Abbiamo dimostrato che $P$ è ortogonale.


Argomento principale: [[Forme bilineari]]
Vedi: [[Endomorfismi simmetrici]]
#algebra 