Il seguente teorema fornisce un modo per determinare velocemente se un sitema è compatibile.

### Enunciato:
Un sistema lineare $AX = B$  in m equazioni e n incognite, è compatibile se , e soltanto se, $\rho(A)=\rho(A|B)$.

### DIM:
Se un sistema $AX = B$ ha soluzione , esiste una n-upla di elementi di $K$ che soddisfa tutte le equazioni, ovvero:
$$\alpha_{1}C_{1}+\alpha_{2}C_{2}+\ldots +\alpha_{n}C_{n}=B$$
E' evidente che  B è una combinazione lineare delle colonne di A, quindi il numero massimo di colonne linearmente indipendenti estraibili da A equivale al numero massimo di colonne linearmente indipendenti estraibili da A|B.
E visto che il numero di colonne linearmente equivalenti equivale al rango :  $\rho(A) = \rho(A|B)$ 

Viceversa  se  $\rho(A) = \rho(A|B)$ , sappiamo che aggiungendo la colonna B alla matrice A il numero massimo di colonne l.i. non aumenta e quindi deduciamo che B è combinazione lineare delle colonne di A, quindi:
$$\exists (\alpha_{1}, \alpha_{2},\ldots,\alpha_{n}) \text{    t.c.    }\alpha_{1}C_{1}+\alpha_{2}C_{2}+\ldots +\alpha_{n}C_{n}=B$$
Il sistema ha pertanto soluzione.

Argomento principale: [[Algebra/Sistemi lineari/Sistemi Lineari]]
Vedi: [[Rango di una matrice]],[[Combinazione Lineare]],[[Dipendenza Lineare]]
#algebra