Siano $f,g: A \to R$ e $x_{o} \in R$ un p.a. di $A$ e supponiamo che $\forall x \in A : f(x) \le g(x)$ .
Se esistono i due limiti:$$\lim_{x\to x_{0}}f(x) = L$$e $$\lim_{x\to x_{0}}g(x) = M$$
Allora:$$L \le M$$
### DIM:
Supponiamo per assurdo che $L > M$ ,
consideriamo $f(x) - g(x)$ in $A$ e osserviamo che:$$\lim_{x\to x_{0}}(f(x)-g(x)) = L - M > 0$$
Quindi per il [[Teorema della permanenza del segno]] esiste un intorno di $x_0$ in cui $f(x) - g(x) > 0$ :$$\exists \delta>0 \text{ t.c. }\forall x \in I_{\delta}(x_{0})\cap(A\backslash \{x_{0}\}):f(x)-g(x) >0$$
Questa è una contraddizione con l'ipotesi.

Argomento principale: [[Limiti]]
#analisi1 