
# Naturali

Chiamato $N$ , l'insieme dei  naturali contiene  tutti gli interi positivi e lo zero.$$N=\{0,1,2,3,\ldots \}$$
Vale che:$$\forall n_{1},n_{2}\in N: n_{1}+n_{2}\in N \land n_{1}\cdot n_{2}\in N$$
#### NB:
Ogni numero $n\in N$ possiede in $N$ il suo unico successore, ovvero il numero più piccolo maggiore di $n$

# Interi

Chiamato $Z$,l'insieme degli interi contiene tutti i naturali e i loro opposti.$$Z=\{ \ldots,-2,-1,0,1,2,\ldots \}$$
# Razionali

Chiamato $Q$,l'insieme dei razionali contiene tutti i numeri rappresentabili come frazione, ovvero come  rapporto tra due numeri interi.$$Q=\{ \frac{n}{d}| n,d\in Z \space\land  d\neq 0 \}$$
In $Q$ è definita una relazione d'ordine cotale $\le$ , cioè:$$\forall p,q \in Q:p\le q \space\lor q\le p$$
Quindi $(Q,\le)$ è un [[Campo ordinato]].

Non tutti i numeri appartengono a $Q$, un esempio è $\sqrt{2}$ , ora lo dimostriamo:
### DIM
Supponiamo , per assurdo, che esista un numero $x\in Q$ tale che $x^{2}= 2$ .
Per la definizione di numero razionale $x$ può essere scritto nella forma $\frac{p}{q}$ con $p$ e $q$ primi tra loro, e quindi sappiamo che almeno uno tra $p$ e $q$ è dispari.
Si deduce che $x^{2}=\frac{p^{2}}{q^{2}}=2$ , moltiplicando da entrambe le parti per $q^{2}$ si ottiene:$$p^{2}= 2q^{2}$$
Notiamo che $p^{2}$ è divisibile per due e quindi è pari, questo significa che anche $p$ deve essere pari.
Non ci resta che verificare che $q$ sia dispari.
Poniamo $p=2m$ visto che è pari, sostituiamo nell'equazione e otteniamo:$$(2m)^{2}=4m^{2}=2q^{2}$$
Dividiamo per 2:$$q^{2}= 2m^{2}$$
Quindi anche $q$ è pari, e ciò è una contraddizione con la tesi.


#analisi1 