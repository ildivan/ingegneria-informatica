Sia $A\in Mat_{n,n}(K)$ una matrice quadrata a coefficienti in $K$ .

### Autovalore 
Si dice che $\lambda$ è autovalore di $A$ se:$$\exists v\neq \overline{0}\in K^{n}: Av = \lambda v$$
### Autovettore
Stando alla precedente definizione, $v$ è detto autovettore relativo all'autovalore $\lambda$.

**nb:** se $v$ è autovettore rispetto a $\lambda$ , anche $\alpha v \space\forall \alpha \in K$ sarà autovettore rispetto a $\lambda$.

### Autospazio
L'insieme dei vettori $v\in K^{n}$ tali che sono autovettori di $\lambda$ si dice autospazio relativo all'autovalore $\lambda$:$$V_\lambda=\{ v\in K^{n}: v\neq \overline{0} \land Av=\lambda v\}$$
**nb:** Ogni autospazio è anche un sottospazio vettoriale di $K^{n}$ 

**NB:** Autospazi riferiti ad autovalori distinti sono in somma diretta.


## Polinomio caratteristico

Prendiamo la definizione di autovalore:$$Av=\lambda v$$
$$Av-\lambda v = 0$$
$$(A-\lambda)v=0$$
$$(A-\lambda Id_{n})v=0$$
Osserviamo che è la forma matriciale di un sistema lineare omogeneo.

Sappiamo che un sistema lineare omogeneo ammette soluzione diversa da quella banale solamente se il determinante della matrice incompleta è uguale a 0, quindi:$$det(A-\lambda Id_{n})=0$$
L'espressione $det(A-\lambda Id_{n})$ equivale ad un polinomio con $\lambda$ come variabile , che chiamiamo **polinomio caratteristico** associato alla matrice $A$.

Trovando gli zeri del polinomio caratteristico  si calcolano gli autovalori.

#### Calcolo di un autospazio
Per trovare un autospazio è sufficiente trovare una sua base, quindi consideriamo nuovamente il sistema omogeneo:$$(A-\lambda_{i} Id_{n})v=0$$
dove $\lambda_{i}$ è un autovalore di $A$ in particolare.
Dobbiamo trovare una base dell'insieme delle soluzioni del sistema omogeneo.



Argomento principale: [[Matrici]]
Vedi: [[Algebra/Sistemi lineari/Sistemi Lineari]],[[Trovare la base dell'insieme delle soluzioni di un sistema omogeneo]]
#algebra 