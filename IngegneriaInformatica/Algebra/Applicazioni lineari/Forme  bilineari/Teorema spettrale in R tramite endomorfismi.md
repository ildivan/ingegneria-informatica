### Lemmi preliminari
1) Un endomorfismo $f:V\to V$ è simmetrico se, e solo se la matrice $A$ associata ad $f$ rispetto ad una base ortonormale di $V$ è simmetrica.
2) Gli autovalori di un endomorfismo simmetrico sono tutti reali.

### Enunciato
Sia $V$ uno spazio  vettoriale finitamente generato su $R$ e dotato di prodotto scalare $\langle ,\rangle$ definito positivo, sia $f:V\to V$ un endomorfismo.

Allora $f$ è simmetrico se, e solo se esiste una base ortonormale di $V$ composta da autovettori di $f$.

### Dimostrazione

Assumiamo come ipotesi che $f$ è simmetrico.

Dobbiamo dimostrare che esista una base $B=\{u_{1},\ldots,u_{n}\}$ di $V$ tale che ogni $u_{i}$ sia autovettore di $f$.

Procediamo per induzione su $n$.

##### PASSO ZERO
Per $n=1$ , ogni base di $V$ è formata da un solo vettore non nullo. Scegliamo un vettore qualsiasi $v_{1}$ e sia esso la nostra base.

Essendo $f$ un endomorfismo $f(v_{1})$ si esprime come combinazione lineare dei vettori della base:$$f(v_1)=\lambda v_{1}\implies v_{1}\text{ è un autovettore }$$
Non ci resta che normalizzarlo e abbiamo verificato il passo zero.

##### PASSO INDUTTIVO

Ipotizziamo la tesi vera per $n-1$ e dimostriamo che è vera per $n$ .

Poichè $f$ è simmetrico , è garantita l'esistenza di almeno un autovalore reale $\lambda_{0}$.
Sia $v_{0}$ un autovettore di $\lambda_{0}$ , che supponiamo abbia norma 1. Consideriamo il sottospazio generato da $v_{0}$:$$W=L(v_{0})$$
Costruiamo il complemento ortogonale di $W$ rispetto al prodotto scalare:$$W^{\perp}=\{v\in V : \langle v,v_{0}\rangle = 0\}$$
I due sottospazi sono in somma diretta:$$V=W\oplus W^{\perp}$$
Quindi per la [[Formula di Grassmann]]:$$dim(V)=dim(W)+dim(W^{\perp})$$
$$n = 1+dim(W^{\perp})$$
$$dim(W^{\perp})=n-1$$

Dobbiamo dimostrare che $f$ è un endomorfismo simmetrico su $W^{\perp}$ , in quanto spazio vettoriale di dimensione $n-1$.

Sia $w\in W^{\perp}$.
Essendo $f$ simmetrico su $V$ possiamo dire che:$$\langle v_{0},f(w)\rangle=\langle f(v_{0}),w\rangle$$
$$\langle v_{0},f(w)\rangle = \lambda_{0}\langle v_{0},w\rangle$$
dato che $v_{0}\in W$ e $w\in W^{\perp}$ :$$\lambda_{0}\langle v_{0},w\rangle = 0 \implies\langle v_{0},f(w)\rangle = 0\implies f(w)\in W^\perp$$
quindi $f$ è un endomorfismo simmetrico su $W^{\perp}$.

Per ipotesi induttiva esiste quindi una base $\{u_{1},\ldots,u_{n-1}\}$ ortonormale di $W^{\perp}$ formata da autovettori di $f$ .

Visto che $\langle v_{0},u_{i}\rangle = 0 \space\forall i=1,2,\ldots,n-1$ possiamo completare $v_{0}$ alla base $\{u_{1},\ldots,u_{n-1}\}$ per ottenere una base ortonormale di $V$ formata da autovettori di $f$.

##### VICEVERSA
Ipotizziamo che esista una base ortonormale $B$ di $V$ composta da autovettori di $f$, dimostriamo che $f$ è un endomorfismo simmetrico.

L'esistenza di una base di autovettori implica che $f$ è un endomorfismo diagonalizzabile, e che quindi la matrice $A$ associata ad $f$ rispetto alla base $B$ è una matrice diagonale, i cui elementi sulla diagonale principale sono gli  autovalori di $f$.

Essendo tutti gli autovalori reali e la matrice $A$ è simmetrica rispetto ad una base ortonormale allora anche $f$ lo è.


Argomento principale: [[Forme bilineari]]
Vedi: [[Endomorfismi simmetrici]]
#algebra 