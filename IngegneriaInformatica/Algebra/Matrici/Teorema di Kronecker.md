Gli spazi vettoriali $L(R)$ e $L(C)$, chiamati spazio delle righe e spazio delle colonne, di una matrice $A\in Mat_{m,n}(K)$ hanno la stessa dimensione e tale dimensione coincide con il rango della matrice.

### DIM
Dimostriamo che $L(R)=rk(A)$.
Se $dim(L(R))=s$ , vuol dire che esistono $s$ righe di $A$ linearmente indipendenti, e quindi riusciamo a estrarre un minore di ordine $s$ con determinante non nullo.
Quindi $rk(A)\ge dim(L(R))=s$.

Ipotiziamo per assurdo che $rk(A)=r>s$, dovrebbe esistere un minore di ordine $r$ a determinante non nullo e quindi esisterebbero $r$ righe linearmente indipendenti e ciò è assurdo.

Quindi $rk(A)=dim(L(R))$, si dimostra analogamente per $L(C)$.

#### Enunciato alternativo
Il rango della matrice $A$ coincide con il massimo numero di righe o di colonne linearmente indipendenti estraibili dalla matrice $A$.

Argomento principale: [[Matrici]]
Vedi: [[Rango di una matrice]]
#algebra 