Sia $f: A\to R$ e sia $x_{0}\in R$ un punto  di accumulazione di $A$ .
Supponiamo che esistano $L\in R$ e $L' \in R$ tali che:$$\lim_{x\to x_{0}}f(x)=L \text{ e } \lim_{x\to x_{0}}f(x)=L'$$
Allora $L=L'$.

### DIM:
Sia $\epsilon>0$ arbitrario:
1) $$\lim_{x\to x_{0}}f(x)=L\implies \exists \delta_{1}>0 \text{ t.c. } \forall x\in I_{\delta_{1}}(x_{0})\cap(A\backslash \{x_{0}\}): |f(x)-L|<\epsilon$$
2) $$\lim_{x\to x_{0}}f(x)=L'\implies \exists \delta_{2}>0 \text{ t.c. } \forall x\in I_{\delta_{2}}(x_{0})\cap(A\backslash \{x_{0}\}): |f(x)-L'|<\epsilon$$
pongo $\delta = min\{\delta_{1},\delta_{2} \}$ e ottengo:$$\forall x \in I_\delta(x_{0})\cap(A\backslash\{x_{0}\}): |L-L'| = |L -f(x)+f(x)-L'|$$
Questo vale perchè abbiamo preso la prima identità e abbiamo sommato e sottratto per $f(x)$ , notiamo però che per la [[Disuguaglianza triangolare]] vale che:$$|L-f(x)+f(x)-L'|\le \underset{<\epsilon}{|L-f(x)|}+\underset{<\epsilon}{|f(x)-L'|}<2\epsilon$$
Si deduce  facilmente che $0\le |L-L'|<2\epsilon\implies |L-L'|=0\implies L=L'$ 

Argomento principale: [[Limiti]]
Vedi: [[Elementi di topologia]]
#analisi1 