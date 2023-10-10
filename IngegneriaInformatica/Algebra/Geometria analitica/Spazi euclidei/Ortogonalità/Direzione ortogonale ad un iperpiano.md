In $E_{n}(R)$ dato un iperpiano , quindi un sottospazio lineare di dimensione $n-1$ ,è sempre possibile trovare una direzione ortogonale a esso in quanto il complemento ortogonale sarà sempre di dimensione $1$.

### Proposizione
Sia $RC=[O,B]$ un riferimento cartesiano ortonormale di $E_{n}(R)$ e sia $B=(e_{1},\ldots,e_{n})$ una base ortonormale.
Se $S_{n-1}=[P;V_{n-1}]$ di equazione:$$\alpha_{1}x_{1}+\alpha_{2}x_{2}+\alpha_{3}x_{3}+\ldots+\alpha_{n}x_{n}+\alpha_{0}=0$$
con $(\alpha_{1},\ldots,\alpha_{n})\neq(0,\ldots,0)$, allora la classe di parametri direttori $[(\alpha_{1},\ldots,\alpha_{n})]$ individia la direzione ortogonale a $S_{n-1}$.

### DIM
Sappiamo che le componenti dei  vettori di $V_{n-1}$ sono le  soluzioni  dell'equazione $\alpha_{1}x_{1}+\ldots+\alpha_{n}x_{n}+\alpha_{0}=0$ , quindi sia $(l_{1},\ldots,l_{n})$ una sua qualsiasi autosoluzione.
Sia $v=l_{1}e_{1}+\ldots+l_{n}e_{n}$ un qualunque vettore non nullo di $V_{n-1}$.
Sia $w=\alpha_{1}e_{1}+\ldots+\alpha_{n}e_{n}$ , calcoliamo $w \cdot v$:$$(\alpha_{1}e_{1}+\ldots+\alpha_{n}e_{n})\cdot(l_{1}e_{1}+\ldots+l_{n}e_{n})=\alpha_{1}l_{1}+\ldots+\alpha_{n}l_{n}$$
Segue che $\alpha_{1}l_{1}+\ldots+\alpha_{n}l_{n} = 0$ in quanto $(l_{1},\ldots,l_{n})$ risolve l'equazione $\alpha_{1}x_{1}+\ldots+\alpha_{n}x_{n}+\alpha_{0}=0$ .
Pertanto il vettore $w$ appartiene a $V_{n-1}^{\perp}$ , e visto che $dim(V_{n-1}^{\perp})=1$ e che il vettore $w$ è non nullo allora ne costituisce una base.

Argomento principale: [[Spazi euclidei]]
Vedi: [[Equazione cartesiana  di un iperpiano]],[[Ortogonale di un sottospazio lineare]]
#algebra 