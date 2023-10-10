Sia $V$ uno spazio vettoriale finitamente generato su $C$ e sia $\langle , \rangle$ un prodotto hermitiano definito positivo su $V$ .
Sia $f: V\to V$ un endomorfismo , allora $f$ è hermitiano se, e solo se esiste una base ortonormale di $V$ composta da tutti autovettori di $V$.

### DIM
Supponiamo che $f$ sia un endomorfismo hermitiano, prendiamo $n\ge 1$ come dimensione di $V$.
Dobbiamo  dimostrare che  esiste  una  sequenza $B=(v_{1},\ldots,v_{n})$ ortonormale tale  che i vettori $u_{i}$  sono   autovettori di $f$.

Procediamo per  induzione su $n$.

**PASSO ZERO**

Prendiamo $n=1$ , ogni base di $V$ allora è formata da un solo vettore non nullo.
Scegliamo $(v_{1})$ come base.
Essendo $f(v_{1})\in V$ , allora esiste un coefficiente $\lambda_{1}$ tale che $f(v_{1})= \lambda_{1}v_{1}$.
Ovviamente, $v_{1}$ è quindi autovettore di $f$, non ci resta che normalizzare $v_{1}$ e per $n=1$ abbiamo finito.

**PASSO INDUTTIVO**
Supponiamo ora la tesi per $n-1$ e dimostriamo per $n$.

Per ipotesi $f$ è hermitiano e quindi ammette almeno un autovalore $\lambda_{0}$ reale, sia $v_{0}$ un autovettore di $\lambda_{0}$.
Supponiamo che $v_{0}$ abbia norma 1.

Sia $W$ il sottospazio generato da $v_{0}$.
Sia $W^\perp$ il complemento ortogonale di $W$ definito quindi come:$$W^{\perp}=\{ v \in V : \langle v,v_{0}\rangle = 0 \}$$
Ricordiamo che $W$ e $W^\perp$ sono in somma diretta:$$V = W\oplus W^{\perp}$$
Per la [[Formula di Grassmann]] :$$dim(V)= dim(W)+dim(W^{\perp})$$
$$dim(W^{\perp})=dim(V)-dim(W)$$
Essendo $dim(W)$ palesemente 1 , ne segue che:
$$dim(W^{\perp})= n-1$$

La restrizione $t: W^{\perp}\to W^{\perp}$ di $f$ a $W^{\perp}$ è un endomorfismo hermitiano su $W^{\perp}$ (spazio vettoriale di $dim(W^{\perp})=n-1$), in quanto $f$ lo è su tutto $V$ .
Per ipotesi induttiva esiste quindi una base $B^{\perp}=(u_{1},\ldots,u_{n-1})$ ortonormale e composta da autovettori di $t$.

Chiaramente essendo $W$ e $W^{\perp}$ in somma diretta basta completare $v_{0}$ a $B^{\perp}$  per ottenere una base ortonormale di $V$ composta da autovettori.

#### VICEVERSA
Se assumiamo per ipotesi che esista una base $B$ ortonormale di $V$ formata da autovettori di $f$ , allora $f$ è un endomorfismo diagonalizzabile.
In quanto tale la matrice $A$ rappresentativa  di $f$ rispetto  a $B$ è una matrice diagonale che ha sulla diagonale principale gli autovalori di $f$ , che sono tutti  reali.
Da ciò segue che $A$ è hermitiana e che quindi $f$ è hermitiano.

Argomento principale: [[Forma sesquilineare]]
Vedi: [[Endomorfismo hermitiano]],[[Endomorfismi diagonalizzabili]]
#algebra 