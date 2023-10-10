$(X,+,\cdot)$ è uno spazio normato se:
1) $(X,+,\cdot)$ è uno spazio vettoriale
2) è definita una norma $||\space||:X\to R$  con le seguenti caratteristiche:
	1) $\forall x\in X\space ||x||\ge 0$
	2) $\forall x\in X \space ||x||=0\iff x=\underline{0}$ 
	3) $\forall x,y\in X \space ||x+y||\le ||x||+||y||$
	4) $\forall x\in X \space \forall \lambda\in R\space ||\lambda x|| = |\lambda|\cdot||x||$

### Legame con gli spazi metrici
Se $(X,+,\cdot)$ è uno spazio normato , allora $(X,d)$ è uno spazio metrico con $d(x,y)=||y-x||$
Inoltre:
1) $\forall x,y\in X$ $d(x,y) = d(x+z,y+z)$
2) $\forall x,y \in X$ $\forall \lambda\in R$ $d(\lambda x,\lambda y) = |\lambda|d(x,y)$

#### DIM
Dimostriamo che $d: X\times X \to R$ definita come $d(x,y)=||y-x||$ sia una [[Funzione distanza]] valida.
1) $\forall x,y\in X$ $d(x,y) \ge 0$ $$\impliedby d(x,y) = ||y-x|| \ge 0$$
2) $\forall x,y\in X$ $d(x,y)=0\iff x=y$$$\impliedby d(x,y) = ||y-x|| = 0 \iff x=y$$
3) $\forall x,y\in X$ $d(x,y) = d(y,x)$ $$\impliedby d(x,y)=||y-x||=||x-y|| = d(y,x)$$
4) $\forall x,y,z\in X$ $d(x,y)\le d(x,z)+d(y,z)$$$||y-x||=||y-z+z-x||\le ||y-z||+||z-x||=d(x,z)+d(y,z)$$
Dimostriamo le altre due affermazioni:
1)  $\forall x,y\in X$ $d(x,y) = d(x+z,y+z)$$$d(x+z,y+z) = || (y+z) -(x+z)||=||y-x||=d(x,y)$$
2) $\forall x,y \in X$ $\forall \lambda\in R$ $d(\lambda x,\lambda y) = |\lambda|d(x,y)$$$d(\lambda x,\lambda y)=||\lambda y - \lambda x||=||\lambda(y-x)||=|\lambda|\space||y-x||=|\lambda|d(x,y)$$

Argomento principale: [[Spazi metrici]]
Vedi: [[Spazi vettoriali]],[[Norma indotta da un prodotto scalare]]
#analisi2