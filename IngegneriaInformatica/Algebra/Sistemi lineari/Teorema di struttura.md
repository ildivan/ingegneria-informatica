Sia $AX=B$ un sistema lineare con soluzione $S\in R^{n}$ .
Allora ogni altra soluzione è della forma:$$S'=S+W:W\in R^{n}$$
Dove $W$ è una soluzione del sistema omogeneo associato $AX=\underline{0}$ .

## DIM
Dimostriamo per prima cosa che tutte le soluzioni di $AX=B$ si scrivono nella forma $S+W$.
Per definizione di soluzione abbiamo $AX=B$ e $AW=\underline{0}$ , quindi:$$AX+AW=B+\underline{0}\implies A(X+W)=B$$
Dimostriamo ora che si scrivono solo in questa forma, ovvero che se $\overline{X}$ è soluzione di $AX=B$ allora è del tipo $S+W$ .
Se calcoliamo $A(\overline{X}-S)$ otteniamo:$$A(\overline{X}-S)=A\overline{X}-AS=B-B=\underline{0}=A(W)$$$$\implies \overline{X}-S=W\implies \overline{X}=S+W$$

Argomento principale: [[Algebra/Sistemi lineari/Sistemi Lineari]]
Vedi: [[Caratteristiche Sistemi Lineari]]
#algebra 