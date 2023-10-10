Siano $f,g,h:A\to R$ e sia $x_{0}\in R$ un punto di accumulazione di $A$ .
Supponiamo che:$$\forall x \in A : h(x)\le f(x)\le g(x)$$
Se $h$ e $g$ ammettono lo stesso limite $L$ in $x_{0}$, allora anche $f$ ammette limite per $x\to x_{0}$ e vale:$$\lim_{x\to x_{0}}f(x)=L$$
### DIM
Sia $\epsilon>0$ arbitrario:
$$\lim_{x\to x_{0}}h(x) = L \implies \exists \delta_{1}: \forall x\in(I_{\delta_{1}}(x_{0})\cap(A\backslash\{x_{0}\})) \text{ t.c. }|h(x)-L|<\epsilon$$
$$\lim_{x\to x_{0}}g(x) = L \implies \exists \delta_{2}: \forall x\in(I_{\delta_{2}}(x_{0})\cap(A\backslash\{x_{0}\})) \text{ t.c. }|g(x)-L|<\epsilon$$

poniamo $\delta=min\{\delta_{1},\delta_{2}\}$ , quindi $\forall x\in (I_{\delta}(x_{0})\cap(A\backslash\{x_{0}\}))$ si ha:
1) $f(x)-L\le g(x)-L<\epsilon$
2) $f(x)-L\ge h(x)-L \ge -|h(x)-L| > -\epsilon$

Il chè implica:$$-\epsilon<f(x)-L<\epsilon$$
$$|f(x)-L|<\epsilon$$
$Q.E.D$

### Corollario
Siano $f,g:A\to R$ , sia $x_{0}$ un punto di accumulazione di $A$ .
Supponiamo che:
1) $$\lim_{x\to x_{0}}f(x)=0$$
2) La funzione $g$ è limitata in $A$ , ovvero:$$\exists M\in R:\forall x\in A : |g(x)|\le M$$
allora:$$\lim_{x\to x_{0}}f(x)g(x)=0$$
#### DIM:
Siccome $|g(x)|\le M\space \forall x\in A$ vale che:$$0\le |f(x)g(x)|\le|f(x)|M$$
Per il teorema dei  carabinieri: $$0\le\lim_{x\to x_{0}}|f(x)g(x)|\le M\lim_{x \to x_{0}}|f(x)|$$
$$0\le \lim_{x\to x_{0}}|f(x)g(x)|\le 0$$
$Q.E.D.$

Argomento principale: [[Limiti]]
#analisi1 