Ogni matrice hermitiana $A\in Mat_{n,n}(C)$ è diagonalizzabile mediante una [[Matrice unitaria]] $U$ tale che $U^{-1}AU$ è una matrice diagonale.

## DIM
Sia $A\in Mat_{n,n}(C)$ una matrice hermitiana, sia l'applicazione lineare associata ad $A$:
$L_{A}: C^{n}\to C^{n}$
$L_{A}(x)= Ax$ 

$L_{A}$ è quindi un endomorfismo hermitiano rispetto al prodotto hermitiano canonico, quindi per il [[Teorema spettrale in C tramite endomorfismi]] esiste una base ortonormale di $C^{n}$ formata da autovettori  di $L_{A}$.
Sia tale base $B=\{ u_{1},\ldots,u_{n}\}$.

L'esistenza di $B$ ci indica che $L_A$ è un endomorfismo diagonalizzabile, e quindi lo è anche la matrice associata $A$ .

Inoltre la matrice $U$ che ha come colonne i vettori di $B$, è la matrice diagonalizzante di $A$ , ovvero la matrice $U^{-1}AU$ è diagonale.

Ci rimane da dimostrare che $U$ è una matrice unitaria,
ovvero che:$$U(\overline{U})^{T}=Id_{n}=(\overline{U})^{T}U$$
Per le regole del prodotto riga per colonna l'elemento in posizione $(i,j)$ del prodotto $(\overline{U})^{T}U$ è la $i$-esima riga di $(\overline{U})^{T}$ per la $j$-esima colonna di $U$.

La $j$-esima colonna di $U$ è $u_{j}$ mentre la $i$-esima riga di $(\overline{U})^{T}$ è $\overline{u_{i}}$ .
Quindi l'elemento in posizione $(i,j)$ del prodotto $(\overline{U})^{T}U$ è:$$\overline{u_{i}}^{T}\cdot u_{j}=\langle u_{j},u_{i}\rangle_{h}$$
Per ortonormalità di $B$:
$$\langle u_{j},u_{i}\rangle_{h}=\begin{cases} 0 \text{ se } i\neq j  \\
1 \text{ se } i=j\end{cases}\implies (\overline{U})^{T}U = Id_{n}$$

Ciò dimostra che $U$ è una matrice invertibile con inversa $(\overline{U})^T$:$$(\overline{U})^{T}U = Id_{n}\implies U^{-1}=(\overline{U})^{T}\implies U(\overline{U})^{T}=Id_{n}$$
e quindi $U$ è una matrice unitaria.


Argomento principale: [[Forma sesquilineare]]
Vedi: [[Endomorfismi diagonalizzabili]]
#algebra 