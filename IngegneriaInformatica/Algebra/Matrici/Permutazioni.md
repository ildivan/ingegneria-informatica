Dato un insieme finito $I$ costituito da $n$ elementi, si dice permutazione su $n$ oggetti qualunque biiezione del tipo:  $\alpha:I\to I$
Una permutazione su $I$ si indica con:$$\alpha= \begin{bmatrix}1 & 2 & 3  & \ldots  & n \\ \alpha(1) & \alpha(2) & \alpha(3) & \ldots & \alpha(n)\end{bmatrix}$$
Esempio:$$\alpha= \begin{bmatrix}1 & 2 & 3  & 4 \\ 4 & 2 & 1 & 3 \end{bmatrix}$$
#### NB:
L'insieme di tutte le permutazioni su n oggetti contiene esattamente $n!$ elementi.

### Composizione di permutazioni:
Date due permutazioni su $I: \beta,\gamma$
Si indica con $\gamma o \beta$ la loro composizione:$$\gamma o \beta= \begin{bmatrix}1 & 2 & \ldots & n \\ \gamma(\beta(1)) & \gamma(\beta(2)) & \ldots & \gamma(\beta(n))  \end{bmatrix}$$
#### Permutazione identica:
$$I = \begin{bmatrix}1 & 2 & \ldots  & n \\ 1 & 2 & \ldots & n\end{bmatrix}$$

### Permutazione inversa:
Si ottiene invertendo le righe della permutazione.

### Scambio:
Una permutazione si dice scambio se scambia  due elementi e lascia invariati gli altri.

### Parità di una permutazione:
Una permutazione è detta pari o dispari in base al numero di scambi in cui essa è scomponibile.

### Segno di una permutazione:
$$sgn(\alpha)=\begin{cases}+1 \text{ se è pari} \\
-1 \text{ se è dispari}\end{cases}$$

Argomento principale: [[Matrici]]
#algebra