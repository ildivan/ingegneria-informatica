Una matrice $A\in K^{m,n}(K)$ ha rango $p$ se ,e soltanto se, esiste un minore $M$ di ordine $p$ a determinante non nullo e tutti i minori di ordine $p+1$ che contengono $M$, hanno determinante nullo.

### DIM
Se $rk(A)=p$ esiste un minore $M$ di ordine $p$ con determinante non nullo, e tutti i minori di ordine $p+1$ hanno determinante nullo, quindi anche quelli che contengono $M$.

Viceversa, sia $M$ un minore di ordine $p$ con determinante $\neq 0$ e siano con determinante nullo tutti i minori di ordine $p+1$ che lo contengono.
Supponiamo per assurdo che $rk(A)=r>p$, allora per il [[Teorema di Kronecker]] lo spazio delle righe(colonne) è di dimensione $r>p$.
Quindi alle righe(colonne) contenenti $M$ è possibile aggiungere una riga opportuna e ottenere comunque un sistema libero, questo è assurdo perchè implicherebbe l'esistenza di un minore di ordine $p+1$ contenente $M$ con determinante non nullo.

Argomento principale: [[Matrici]]
Vedi: [[Rango di una matrice]]
#algebra 