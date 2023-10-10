In $A_{n}(R)$ consideriamo i due sistemi di riferimento:$$RA=[O,B=(e_{i})_{i\in I_{n}}]$$$$RA'=[O',B' =(e'_{i})_{i\in I_{n}}]$$
Sia $O'=(t_{i})_{i\in I_{n}}$ rispetto ad $RA$.
Siano $(x_{i})_{i\in I_{n}}$ e $(x'_{i})_{i\in I_{n}}$ le coordinate di un punto $P$ in $RA$ e $RA'$ rispettivamente.
Indichiamo tutto in forma matriciale:$$X=\begin{pmatrix}x_{1} \\ \vdots \\ x_{n}\end{pmatrix}X'=\begin{pmatrix}x'_{1} \\ \vdots \\ x'_{n}\end{pmatrix}T=\begin{pmatrix}t_{1} \\ \vdots \\ t_{n}\end{pmatrix}E=\begin{pmatrix}e_{1} \\ \vdots \\ e_{n}\end{pmatrix}E'=\begin{pmatrix}e'_{1} \\ \vdots \\ e'_{n}\end{pmatrix}$$Valgono le seguenti affermazioni:
1) $\overrightarrow{OO'} = T^{T}E$ , perchè $\overrightarrow{OO'}$ rappresenta il punto $O'$ in $RA$.
2) $\overrightarrow{O'P}=X'^{T}E'$, perchè rappresenta il punto $P$ in $RA'$.
3) $\overrightarrow{OP}=X^{T}E$, perchè rappresenta il punto $P$ in $RA$.

Quindi scrivere $\overrightarrow{OO'}+\overrightarrow{O'P}=\overrightarrow{OP}$ equivale a scrivere:$$T^{T}E+X'^{T}E'=X^{T}E$$
Ricordiamo che $E' = AE$ dove $A$ è la matrice del cambiamento di base da $B$ a $B'$, quindi la nostra equazione diventa:$$T^{T}E+X'^{T}AE=X^{T}E$$$$(T^{T}+X'^{T}A)E=X^{T}E$$$$T^{T}+X'^{T}A=X^{T}$$
$$X=T+A^{T}X'$$

Ponendo $E=A^{-1}E'$ dove $A^{-1}$ è la matrice del cambiamento di base da $B'$ a $B$, quindi la nostra equazione diventa:$$T^{T}A^{-1}E'+X'^{T}E'=X^{T}A^{-1}E'$$$$(T^{T}A^{-1}+X'^{T})E'=X^{T}A^{-1}E'$$$$T^{T}A^{-1}+X'^{T}=X^{T}A^{-1}$$$$X'^{T}=X^{T}A^{-1}-T^{T}A^{-1}$$$$X'=(A^{-1})^{T}X-(A^{-1})^{T}T$$
Argomento principale: [[Spazi affini]]
Vedi: [[Riferimento cartesiano affine]],[[Matrice del cambiamento di base]],[[Matrice inversa]]
#algebra 