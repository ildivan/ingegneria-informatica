Sia $AX = B$ un sistema lineare compatibile , in $m$ equazioni ed $n$ incognite, cioè $\rho(A) = \rho(A | B) = p$ .
Si dice **sistema principale equivalente** al sistema $AX=B$ un sistema $A'X = B'$ ottenuto estraendo $p$ equazioni del sistema $AX = B$ , in modo tale che $\rho(A')=\rho(A'|B')=p$ .

### TEO:
Ogni sistema compatibile ha le stesse soluzioni di un suo qualunque sistema principale equivalente.

### DIM:
Sia $AX = B$ un sistema lineare compatibile , in $m$ equazioni ed $n$ incognite, cioè $\rho(A) = \rho(A | B) = p$ e sia $A'X = B'$ un  sistema principale equivalente al sistema $AX=B$  ,quindi tale che: $\rho(A')=\rho(A'|B')=p$ .

Cambiando l'ordine delle righe del sistema $AX =B$ possiamo supporre che il sistema $A'X=B'$ sia ottenuto estraendo le prime $p$ righe di $AX=B$ .

Dato che le matrici $A|B$ e $A'|B'$ hanno per ipotesi lo stesso rango possiamo dire che le ultime $m-p$ righe di $A|B$ sono combinazione lineare delle prime $p$ righe.

Dimostriamo che che i due sistemi hanno la stessa soluzione.
Ovviamente ogni soluzione di $AX=B$ è anche soluzione di $A'X=B'$, viceversa ogni soluzione di $A'X=B'$ soddisfa le prime $p$ equazioni di $AX=B$, e quindi anche le ultime righe che sono combinazioni lineari delle altre.


Argomento principale: [[Algebra/Sistemi lineari/Sistemi Lineari]]
Vedi: [[Dipendenza Lineare]],[[Rango di una matrice]],[[Matrici]]
#algebra