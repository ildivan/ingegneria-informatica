Sia $f:A\to R$ limitata e sia $D$ una suddivisione di $[a,b]$ .
Chiamiamo:$$s(f,D)= \sum\limits_{j=1}^{n}(\underset{x\in I_{j}}{inf}\space f(x))(x_{j}-x_{j-1})$$
La **somma inferiore** di $f$ rispetto alla suddivisione $D$.
Analogamente, chiamiamo:$$S(f,D)= \sum\limits_{j=1}^{n}(\underset{x\in I_{j}}{sup}\space f(x))(x_{j}-x_{j-1})$$
### Proprietà:
Sia $D_{n}$ una successione di suddivisioni t.c. $D_{n+1}$ è più precisa di $D_{n}$, ovvero:$$D_{n}\subset D_{n+1}$$
Per le proprietà di $sup$ e $inf$ :$$\begin{matrix} s(f,D_{n}) \le s(f,D_{n+1})\space \forall n\in N  \\ S(f,D_{n}) \ge S(f,D_{n+1})\space \forall n\in N \end{matrix} $$
Quindi esistono finiti i limiti:$$\lim_{n\to \infty}s(f,D_{n}) \text{ e } \lim_{n\to \infty}S(f,D_{n})$$
E per il teorema del confronto:$$\lim_{n\to \infty}s(f,D_{n}) \le \lim_{n\to \infty}S(f,D_{n})$$

Argomento principale:[[Integrale di Riemman]]
Vedi:[[Suddivisione di un intervallo]],[[Limiti]],[[Estremo superiore e inferiore]]
#analisi1 