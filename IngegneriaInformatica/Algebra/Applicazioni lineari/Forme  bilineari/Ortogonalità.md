Sullo spazio vettoriale $V(K)$ si dice che due vettori, per esempio $v$ e $w$ sono ortogonali se il prodotto scalare tra i due vettori è nullo:$$v \perp w \iff \langle v,w\rangle=0 $$
## Complemento ortogonale
Sia $V(K)$ uno spazio vettoriale che ammette  prodottto scalare, e sia $A$ un suo sottoinsieme non vuoto. 
Si dice complemento ortogonale l'insieme di vettori di $V$ che sono ortogonali a **tutti** i vettori di $A$.
$$A^{\perp} =\{ v\in V | \langle v,w\rangle= 0, \forall w\in A \}$$
nb: $A^{\perp}$ è sottospazio di $V$

### Teorema di Caratterizzazione del complemento ortogonale 
Sia $V(K)$ uno spazio vettoriale che ammette prodotto scalare , $S$ un sottospazio di $V$ e sia $B=(s_{1},\ldots,s_{n})$ una base di $S$ .
Un vettore $v\in V$ appartiene al complemento ortogonale di $S$ se, e solo se è ortogonale ad ogni vettore della base di $S$.
$$v\in S^{\perp}\iff \langle v,s_{i}\rangle=0 \space\forall s_{i}\in B$$

#### DIM
Chiaramente se $v\in S^{\perp}$ allora è ortogonale a tutti i vettori di $S$ , compresi i vettori  della base $B$.

Dimostriamo ora che se $\langle v,s_{i}\rangle=0$ per ogni $s_{i}$ , allora $v$ è ortogonale a tutti i vettori di $S$ .
Sia $s\in S$ un vettore generico e lo scriviamo come  combinazione lineare dei vettori della  sua base:$$s=\alpha_{1}s_{1}+\ldots+\alpha_{n}s_{n}$$
Quindi il prodotto scalare $\langle v,s\rangle$ si scrive anche:
$$\langle v, \alpha_{1}s_{1}+\ldots+\alpha_{n}s_{n}\rangle$$
Dobbiamo dimostrare che equivale a $0$ .
Per la linearità del prodotto scalare è equivalente a scrivere:$$= \alpha_{1}\langle v,s_{1}\rangle +\alpha_{2}\langle v,s_{2}\rangle +\ldots+\alpha_{n}\langle v,s_n\rangle$$
Per ipotesi ognuno di questi prodotti scalari è nullo:$$= 0+\ldots+0= 0$$
E quindi $v\in S^{\perp}$ .
La tesi e dimostrata.


## Base ortogonale
Dato uno spazio vettoriale $V$ , si dice base ortogonale di $V$ una base in cui tutti gli elementi sono ortogonali fra di loro:$$B_{V}=(v_{1},\ldots,v_{n})$$
$$\langle v_{i},v_{j}\rangle = 0 \space \forall i\neq j\in \{0,1,\ldots,n\}$$



Argomento principale: [[Forme bilineari]]
#algebra 