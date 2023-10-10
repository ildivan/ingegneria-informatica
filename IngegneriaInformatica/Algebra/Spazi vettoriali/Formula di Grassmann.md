Siano $U$ e $W$ due sottospazi vettoriali di $V(K)$ , allora:$$dim(U+W)=dim(U)+dim(W)-dim(U\cap W)$$
### DIM:
Sia $B_{i}=(v_{1},\ldots,v_{p})$ una base di $U\cap W$ , allora possiamo scrivere le basi di $U$ e $W$ come $B_{U}=(v_{1},\ldots,v_{p},u_{p+1},\ldots,u_{s})$ e $B_{W}=(v_{1},\ldots,v_{p},w_{p+1},\ldots,w_{t})$ 

Creiamo la sequenza $B_{U+W}=(v_{1},\ldots,v_{p},u_{p+1},\ldots,u_{s},w_{p+1},\ldots,w_{t}) = B_{i}\cup(B_{U}\backslash B_{i})\cup(B_{W}\backslash B_{i})$
Se $B_{U+W}$ fosse una base di $U+W$ , allora la tesi sarebbe dimostrata in quanto:$$dim(U+W)=(s-p)+(t-p)+p=s+t-p=dim(U)+dim(W)-dim(U\cap W)$$
Dimostriamo che è una base.

Prima dimostriamo che è una sequenza di generatori:
	Sappiamo che ogni elemento di $U$(rispettivamente $W$) si scrive come combinazione lineare dei  vettori di $B_{U}$ (rispettivamente $B_{W}$) .
	Quindi il generico elemento di $U+W$ si scrive come somma di una c.l. di vettori di $B_{U}$ e di una c.l. di vettori di $B_{W}$ , quindi come combinazione lineare dei vettori di $B_{U+W}$ 

Dobbiamo dimostrare ora che $B_{U+W}$ è una sequenza libera.
Supponiamo allora che:$$\alpha_{1}v_{1}+\ldots+\alpha_{p}v_{p}+\beta_{p+1}u_{p+1}+\ldots+\beta_{s}u_{s}+\gamma_{p+1}w_{p+1}+\ldots+\gamma_{t}w_{t}= \underline{0}$$
Quindi tutti  i coefficienti $\alpha_{i},\beta_{j},\gamma_{k}$  $\forall i=1,\ldots,p$  $\forall j=1,\ldots,s$  $\forall k=1,\ldots,t$ devono essere pari a $0$ 

Consideriamo i tre vettori:$$\begin{matrix} 
v=\alpha_{1}v_{1}+\ldots+\alpha_{p}v_{p} \in U\cap W \\ u=\beta_{p+1}u_{p+1}+\ldots+\beta_{s}u_{s}\in U \\ w= \gamma_{p+1}w_{p+1}+\ldots+\gamma_{t}w_{t}\in W \end{matrix}$$
La nostra ipotesi diventa $v+u+w=\underline{0}$  che trasformiamo in $w=-v-u$ .
Visto che $v\in U\cap W$ e $u\in U$ possiamo affermare  che $w\in U$ , ma sappiamo già che $w\in W$ e quindi $w\in U\cap W$ .
Possiamo ora scrivere $w$ come combinazione lineare dei vettori di $B_{i}$ (visto  che $w\in U\cap W$):$$w=\delta_{1}v_{1}+\ldots+\delta_{p}v_{p}$$
dalla definizione di $w$ :$$\gamma_{p+1}w_{p+1}+\ldots+\gamma_{t}w_{t}=\delta_{1}v_{1}+\ldots+\delta_{p}v_{p}$$
Essendo però che $v_{1},\ldots,v_{p},w_{p+1},\ldots,w_{t}$ sono linearmente indipendenti tutti i coefficienti $\gamma_{i},\delta_{j}$ devono essere $= 0$ 
Ci resta:$$\alpha_{1}v_{1}+\ldots+\alpha_{p}v_{p}+\beta_{p+1}u_{p+1}+\ldots+\beta_{s}u_{s}=\underline{0}$$
Ma $v_{1},\ldots,v_{p},u_{p+1},\ldots,u_{s}$sono linearmente indipendenti e quindi tutti i coefficienti  $\alpha_{i},\beta_j$ sono $=0$ 

$B_{U+ W}$ è base di $U+W$ e la formula di Grassmann è dimostrata . 

Argomento  principale: [[Spazi vettoriali]]
Vedi: [[Dimensione di uno spazio vettoriale]]
#algebra 