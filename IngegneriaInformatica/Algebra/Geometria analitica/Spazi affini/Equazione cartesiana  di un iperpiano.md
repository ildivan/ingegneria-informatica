Con il crescere della dimensione del sottospazio lineare, la sua rappresentazione parametrica diventa sempre più complessa.

Nel caso particolare in cui il sottospazio lineare considerato sia di dimensione $n-1$ , ovvero è un iperpiano , esiste una rappresentaione più comoda di quella parametrica:$$X=X' +t_{1}A_{1}+\ldots+t_{n-1}A_{n-1}$$
con $t_{1},\ldots,t_{n-1}\in R$ e $rk(A_{1}\space A_{2}\ldots\space A_{n-1})=n-1$ 

#### Proposizione
Un iperpiano di $A_{n}(R)$ è rappresentato dall'equazione:$$a_{1}x_{1}+\ldots+a_{n}x_{n}+a_{0}=0$$
con $(a_{1},a_{2},\ldots,a_{n})\in R^{n}$ non tutti nulli e $a_{0}\in R$.
Essa è detta **equazione cartesiana di un iperpiano**.

### DIM
Prendiamo le equazioni parametriche dell'iperpiano:$$X=X' +t_{1}A_{1}+\ldots+t_{n-1}A_{n-1}$$
$$X-X'=t_{1}A_{1}+\ldots+t_{n-1}A_{n-1}$$
Quindi la colonna $(X-X')$ è linearmente dipendente dalle $(A_{j})_{j\in I_{n-1}}$ , il che significa che presa la matrice $H=X-X' \space A_{1}\space \ldots\space A_{n-1}$ allora $det(H)=0$ . 
Anche la sua trasposta ha determinante nullo:$$|H^{T}|=det\begin{pmatrix} x_{1}-x'_{1} & x_{2}-x'_{2} & \ldots & x_{n}-x'_{n} \\ a_{11} & a_{21} & \ldots & a_{n1} \\ \vdots & \vdots  & \ddots & \vdots \\ a_{1n-1} & a_{2n-1} & \ldots & a_{nn-1}\end{pmatrix}=0$$
Sviluppando usando Laplace secondo gli elementi della prima riga otteniamo un equazione nella forma:$$b_{1}x_{1}+b_{2}x_{2}+\ldots+b_{n}x_{n}+b_{0}=0$$
Gli $(x_{i})_{i\in I_{n}}$ sono le incognite mentre i $(b_{i})_{i\in I_{n}}$ sono coefficienti non nulli in quanto minori di matrice di ordine $n-1$ estratti dalle $n-1$ righe libere $(A_{1}\space A_{2}\space\ldots\space A_{n-1})^{T}$ .

#### Proposizione
In $A_{n}(R)$ un equazione lineare nelle incognite $(x_{i})_{i\in I_{n}}$ :$$a_{1}x_{1}+\ldots+a_{n}x_{n}+a_{0}=0$$
con $(a_{1},\ldots,a_{n})\neq (0,\ldots,0)$ rappresenta un iperpiano. 

### DIM
In $A_{n}(R)$, sia $I$ il luogo dei punti rappresentato dall'equazione:$$a_{1}x_{1}+\ldots+a_{n}x_{n}+a_{0}=0$$$$a_{1}x_{1}+\ldots+a_{n}x_{n}=-a_{0}$$
Possiamo vedere quest'equazione come un sistema lineare di un equazione in $n$ incognite, e questo sistema è compatibile siccome  $rk(a_{1}\space\ldots\space a_{n})=rk(a_{1}\space\ldots\space a_{n}\space-a_{0})=1$ .

Le soluzioni $(x_{i})_{i\in I_{n}}$ sono date dalla somma di una soluzione particolare $(x'_{i})_{i\in I_{n}}$ con la soluzione generica del sistema omogeneo associato $a_{1}x_{1}+\ldots+a_{n}x_{n}=0$ .

Il sistema omogeneo associato ha $\infty^{n-1}$ soluzioni, ovvero tutte le combinazioni lineari di $n-1$ autosoluzioni particolari.
Indichiamo le autosoluzioni particolari con:$$A_{1}=\begin{pmatrix}a_{11} \\ a_{21} \\ \vdots \\ a_{n1}\end{pmatrix},\ldots,A_{n-1}=\begin{pmatrix}a_{1n-1}  \\ a_{2n-1}\\ \vdots \\ a_{nn-1}\end{pmatrix}$$
Ponendo:$$X=\begin{pmatrix}x_{1} \\ x_{2} \\ \vdots \\ x_{n}\end{pmatrix}X'=\begin{pmatrix}x'_{1} \\ x'_{2} \\ \vdots \\ x'_{n}\end{pmatrix}$$
otteniamo:$$X=X'+t_{1}A_{1}+t_{2}A_{2}+\ldots+t_{n-1}A_{n-1}$$ dove $t_{1},\ldots,t_{n-1}\in R$ e $rk(A_{1}\space A_{2}\space \ldots\space A_{n-1})=n-1$.

Le equazioni ottenute sono equivalenti all'equazione di partenza e rappresentano il luogo dei traslati di $P=(x'_{i})_{i\in I_{n}}$ tramite i vettori di uno spazio vettoriale di dimensione $n-1$ , e di conseguenza $I$ risulta essere un **iperpiano**.

Argomento principale: [[Spazi affini]]
Vedi: [[Equazioni parametriche di un sottospazio lineare]]
#algebra 