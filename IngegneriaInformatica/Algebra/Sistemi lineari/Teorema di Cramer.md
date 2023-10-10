Un sistema lineare $A\overline{x} = b$ , in $n$ equazioni e $n$ incognite  , in cui $det(A) \neq 0$ , ammette una e una sola soluzione e per ogni incognita essa è:$$\overline{x}_{i}=\frac{det(B_{i})}{det(A)}$$
Dove $B_{i}$ è per colonne la matrice $A$ con la i-esima colonna sostituita dalla colonna dei termini noti:$$B_{i}=\begin{pmatrix} C_{1} & C_{2} & \ldots  & C_{i-1} & b  & C_{i+1} & \ldots  & C_{n} \end{pmatrix}$$
$C_{i}$ sono le colonne della matrice $A$.

### DIM:
Dimostriamo prima che se la soluzione esiste , allora essa è unica.
Supponiamo che esistano due colonne $x_{1},x_{2}$ tali che:$$Ax_{1}=b \text{ e } Ax_{2}=b$$
allora abbiamo che:$$Ax_{1}=Ax_{2}$$ se moltiplichiamo da entrambe le parti a sinistra per $A^{-1}$ otteniamo che $x_{1} =x_{2}$ , quindi la soluzione è unica.

Dimostriamo ora che esiste e che corrisponde con la tesi.

Definiamo la matrice $X_{i}$ come la matrice identica con la i-esima colonna sostituita dalla colonna $\overline{x}$ delle incognite. $$I_{n}=\begin{pmatrix} 
e_{1} & e_{2} & \ldots  & e_{n} \end{pmatrix}$$
$$X_{i}=\begin{pmatrix} e_{1} & \ldots & e_{i-1} & \overline{x} & e_{i+1} & \ldots  &  e_{n} \end{pmatrix}$$
Notiamo che per costruzione $X_{i}$ ha $det(X_{i})$ uguale all' i-esimo elemento della colonna delle incognite $\overline{x}_{i}$. 

Svolgiamo il prodotto righe per colonne $A \cdot X_{i}$ e notiamo che risulta:$$AX_{i}= \begin{pmatrix} 
A \cdot e_{1} & \ldots  & A \cdot e_{i-1}  & A\overline{x}  & A \cdot e_{i+1} & \ldots  & A \cdot e_{n} \end{pmatrix}$$
Ogni $A \cdot e_{i}$ equivale a $C_{i}$ , e la colonna $A\overline{x}$ equivale a $b$ , quindi possiamo affermare che $AX_{i} = B_{i}$ e in particolare :$$det(AX_{i})= det(B_{i})$$
Per il [[Teorema di Binet]] : $$det(A)det(X_{i}) = det(B_{i})$$
Ricordiamo che per costruzione $det(X_{i})= \overline{x}_{i}$ :$$det(A)\overline{x}_{i}=det(B_{i})$$
Dividiamo da entrambe le parti per $det(A)$ e troviamo che :$$\overline{x}_{i}=\frac{det(B_{i})}{det(A)}$$
e la tesi è confermata.

Argomento principale: [[Algebra/Sistemi lineari/Sistemi Lineari]]
Vedi: [[Prodotto righe per colonne]],[[Determinante di matrice]]
#algebra