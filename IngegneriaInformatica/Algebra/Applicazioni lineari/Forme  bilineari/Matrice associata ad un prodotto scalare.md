Ad ogni prodotto scalare è possibile associare una matrice.

Sia $V$ uno spazio vettoriale con $dim(V)=n$ e sia $V$ dotato di prodotto  scalare $\langle,\rangle:V\times V\to R$ .
Sia $B_{V}=(v_{1},\ldots,v_{n})$ una base di $V$.
Definiamo la matrice associata al prodotto scalare rispetto alla base $B_{V}$ come:
$$a_{ij}=\langle v_{i},v_{j}\rangle$$
$$A  =\begin{pmatrix} \langle v_{1},v_{1}\rangle  & \langle v_{1},v_{2}\rangle  & \ldots & \langle v_{1},v_{n} \rangle \\ \langle v_{2},v_{1}\rangle  & \langle v_{2},v_{2}\rangle & \ldots & \langle v_{2},v_{n} \\ \vdots & \vdots & \ddots 
 & \vdots \\ \langle v_{n},v_{1}\rangle & \langle v_{n},v_{2}\rangle  & \ldots & \langle v_{n},v_{n}\rangle \end{pmatrix}$$


Utilizzando la matrice associata, è facile calcolare il prodotto scalare dati due vettori $v,w\in V(K)$ .
Siano $X^{t}=(x_{1},x_{2},\ldots,x_{n})$ e $Y^{t}=(y_{1},y_{2},\ldots,y_{n})$ le componenti rispetto a $B_{V}$ rispettivamente  di $v$ e $w$ ,
allora $\langle v,w\rangle = X^{t}AY$ 

Argomento principale: [[Forme bilineari]]
#algebra 