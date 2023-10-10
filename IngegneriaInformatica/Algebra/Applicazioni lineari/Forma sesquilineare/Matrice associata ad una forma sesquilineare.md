Consideriamo lo spazio vettoriale $V$ finitamente generato su $C$ e di dimensione $n$ , e sia $B=(v_{1},\ldots,v_{n})$ una base di $V$ .
Sia $f:V\times V\to C$ una forma sesquilineare, la sua matrice associata rispetto alla base $B$ è:$$a_{ij}=f(v_{i},v_{j})\space\forall i,j=\{1,2,\ldots,n\}$$
$$A^{B}_{f}=\begin{pmatrix}f(v_{1},v_{1}) & f(v_{1},v_{2}) & \ldots & f(v_{1},v_{n}) \\ f(v_{2},v_{1}) & f(v_{2},v_{2}) & \ldots & f(v_{2},v_{n}) \\ \vdots & \vdots & \ddots & \vdots \\ f(v_{n},v_{1}) & f(v_{n},v_{2}) & \ldots & f(v_{n},v_{n}) \end{pmatrix}$$

Vediamo ora , dati $v,w\in V$ come rappresentare in forma matriciale la scrittura $f(v,w)$.
Dati $V^{B}$ e $W^{B}$ , i vettori  delle coordinate di $v$ e $w$ rispetto alla base $B$ :$$V^{B}=\begin{pmatrix}u_{1} \\ \vdots \\ u_{n}\end{pmatrix}W^{B}=\begin{pmatrix}w_{1} \\ \vdots \\ w_{n}\end{pmatrix}$$
Allora:$$f(v,w)=(V^{B})^{T}\cdot A^{B}_{f} \cdot \overline{W^{B}}$$
## Cambio  di base tra matrici associate alla stessa forma sesquilineare

Sia $V$ uno spazio vettoriale finitamente generato in $C$ , e sia $f: V\times V\to C$ una forma sesquilineare.
Prendiamo due basi di $V$ : $B$ e $B'$
Definiamo ora le matrici associate ad $f$ rispetto alle due basi:
1) $A=A^{B}_{f}$
2) $A'=A^{B'}_{f}$

Indichiamo con $M$ la matrice del cambiamento di base da $B$ a $B'$ :
$$M= M_{B'\to B }$$

Consideriamo il generico vettore $v\in V$ e indichiamo con $v_{B}$ e $v_{B'}$ i vettori colonna delle coordinate di $v$ rispetto alle basi $B$ e $B'$.
Dalla definizione di matrice del cambiamento di base segue che:$$(*)\space v_{B}=M \cdot v_{B'} $$
Dalla definizione di matrice associata ad una forma sesquilineare:
1) $f(v,v)= (v_{B})^{T}\cdot A \cdot \overline{v_{B}}$ 
2) $f(v,v)= (v_{B'})^{T}\cdot A' \cdot \overline{v_{B'}}$

Quindi:$$(**) \space (v_{B})^{T}\cdot A \cdot \overline{v_{B}}=(v_{B'})^{T}\cdot A' \cdot \overline{v_{B'}}$$
Per $(*)$ vale che:$$(v_{B})^{T}\cdot A \cdot \overline{v_{B}}= (M \cdot v_{B'})^{T}A \cdot \overline{M \cdot v_{B}}=(v_{B'})^{T}\cdot M^{T}A\overline{M}\cdot \overline{v_{B'}}$$
Per la $(**)$ :$$(v_{B'})^{T}\cdot M^{T}A\overline{M}\cdot \overline{v_{B'}}=(v_{B'})^{T}\cdot A' \cdot \overline{v_{B'}}\implies A' = M^{T}A\overline{M}$$


Argomento principale: [[Forma sesquilineare]]
#algebra 