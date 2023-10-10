
#### Autovalori di una matrice reale e simmetrica
Sia $A\in Mat_{n}(R)$ , se $A$ è simmetrica allora i suoi autovalori sono reali.
### DIM
Sia $A\in Mat_{n}(R)$ una matrice simmetrica.
Sia $\lambda\in C$ un autovalore di $A$,sia $X^{T}\in C^{n}$ un autovettore relativo a $\lambda$, sia $\overline{\lambda}$ il coniugato di $\lambda$ e sia $\overline{X}^{T}$ il coniugato di $X^{T}$ .
Dobbiamo dimostrare che $\lambda=\overline{\lambda}$.
Calcoliamo :$$\lambda(X^{T}\overline{X})=(\lambda X)^{T}\overline{X}=(AX)^{T}\overline{X}=X^{T}A^{T}\overline{X}$$
Ma $A$ è simmetrica $A=A^{T}$, quindi:$$=X^{T}A\overline{X}=X^{T}\overline{\lambda}\overline{X}=\overline{\lambda}(X^{T}\overline{X})$$
Quindi abbiamo trovato che $\lambda(X^{T}\overline{X})=\overline{\lambda}(X^{T}\overline{X})$ , e visto che $X^{T}\overline{X}$ non può essere nullo deve valere che $\lambda=\overline{\lambda}$, quindi $\lambda$ è reale.

Argomento pricipale: [[Matrici]]
Vedi: [[Autovalori e autovettori di una matrice]]
#algebra 