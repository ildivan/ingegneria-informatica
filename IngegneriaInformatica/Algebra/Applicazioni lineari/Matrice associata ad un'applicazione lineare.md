Siano $V,W$ due  spazi  vettoriali con$dim(V)=n,dim(W)=m$  e sia $f:V\to W$ un applicazione lineare.

Siano basi di $V$ e $W$:
$B_{V}=(v_{1},\ldots,v_{n})$ 
$B_{W}=(w_{1},\ldots,w_{m})$ 

Calcoliamo le immagini rispetto a $f$ di tutti i vettore di $B_{V}$ :$$f(v_{1}),f(v_{2}),\ldots,f(v_{n})$$
Scriviamo ora i vettori $f(v_{i})$ come combinazione lineare dei vettori di $B_{W}$ :
$f(v_{1})=\alpha_{11}w_{1}+\alpha_{21}w_{2}+\ldots+\alpha_{m1}w_{m}$
$f(v_{2})=\alpha_{12}w_{1}+\alpha_{22}w_{2}+\ldots+\alpha_{m2}w_{m}$ 
   $\vdots$ 
$f(v_{n})=\alpha_{1n}w_{1}+\alpha_{2n}w_{2}+\ldots+\alpha_{mn}w_{m}$


La matrice che  ha come i-esima colonna le coordinate del vettore $f(v_{i})$ rispetto alla base $B_{W}$ si dice **matrice associata all'applicazione lineare $f$** rispetto alle basi $B_{V}$ e $B_{W}$ .
Questa  matrice si indica con:$$A^{B_{V},B_{W}}_{f}=\begin{pmatrix} 
\alpha_{11} & \alpha_{12} & \ldots & \alpha_{1n} \\ \alpha_{21} & \alpha_{22} & \ldots & \alpha_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ \alpha_{m1} & \alpha_{m2} & \ldots & \alpha_{mn} \end{pmatrix}$$

Argomento principale: [[Applicazioni lineari]]
Vedi: [[Base di uno spazio vettoriale]],[[Matrici]]
#algebra 