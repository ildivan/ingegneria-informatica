Sia $A\in R, x_{0}\in R$ un p.a di $A$ e sia $f:A\to R$ ,
supponiamo che $$\lim_{x\to x_{0}}f(x) = L \neq  0$$
Allora esiste un intorno in cui la funzione ha segno uguale al segno del limite  in ogni suo punto, ovvero:$$\exists \delta>0 \text{ t.c. } \forall x \in I_{\delta}(x_{0})\cap (A\backslash \{x_{0}\}) : sgn(f(x)) = sgn(L)$$
### DIM:
La definizione di limite ci garantisce che:$$\forall \epsilon \space\exists \delta>0 \text{ t.c. } [\forall x \in I_{\delta}(x_{0})\cap (A\backslash \{x_{0}\}) : |f(x)-L|< \epsilon]$$
o equivalentemente:$$L-\epsilon<f(x)<L+\epsilon$$
Osserviamo che questa relazione vale per ogni valore di $\epsilon$ e quindi abbiamo la possibilità di scegliere un valore arbitrario purchè valga che $\epsilon> 0$ , poniamo quindi $\epsilon= \frac{|L|}{2}$ .
Di conseguenza la nostra catena di disequazioni diventa:$$L-\frac{|L|}{2} < f(x) < L + \frac{|L|}{2}$$
Sappiamo che $L \neq 0$ quindi dimostriamo per valori positivi e analogamente per valori negativi.
Supponiamo che $L > 0$ , allora abbiamo che:$$\frac{L}{2}< f(x)<\frac{3L}{2}$$
Possiamo affermare che esiste un intorno di $x_{0}$ in cui $f(x)$ è positiva in quanto è maggiore  di una quantità positiva, ovvero:$$0<\frac{L}{2}<f(x) \space \space \forall x \in I_{\delta}(x_{0})\cap(A\backslash \{x_{0}\})$$
Quindi il teorema è verificato per $L>0$ , analogamente si dimostra per $L<0$ .

$Q.E.D.$

Argomento principale: [[Limiti]]
#analisi1