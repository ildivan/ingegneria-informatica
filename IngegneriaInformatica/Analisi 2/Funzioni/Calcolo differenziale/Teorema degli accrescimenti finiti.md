Sia $f: C \to R^{m}$ con $C \subset R^{n}$ convesso.
Siano $x_{0},x_{1}\in C : \set{tx_{1}+(1-t)x_{0} : t\in [0,1]} \subseteq \overset{\circ}{C}$ 
Se $f$ è differenziabile in $\overset{\circ}{C}$ $\implies$$$||f(x_{1})-f(x_{0})|| \le \sup_{x\in \text{ segmento }} ||Df(x)|| \space ||x_{1}-x_{0}||$$
#### DIM
Definiamo la funzione $\phi : [0,1] \to R$ che a $t$ associa $\phi(t)=f(tx_{1}+(1-t)x_{0}) \cdot v$ con $v\in R^{m} : v \neq 0$ .

Per il [[Teorema di Lagrange]] :$$\phi(1)-\phi(0) = \phi'(c) \cdot 1 \text{ con } c \in ]0,1[$$$$f(x_{1})\cdot v-f(x_{0})\cdot v = Df(cx_{1}+(1-c)c_{0})(x_{1}-x_{0}) \cdot v$$
Poniamo $v = \frac{f(x_{1})-f(x_{0})}{||f(x_{1})-f(x_{0})||}$ , ne segue che $||v|| = 1$.

$$||f(x_{1})-f(x_{0})|| \le ||Df(cx_{1}+(1-c)x_{0})|| \space||x_{1}-x_{0}|| \space ||v||$$$$\le \sup_{x \in \text{ segmento }}||Df(x)|| \space ||x_{1}-x_{0}||$$

Argomento principale: [[Derivata completa e differenziabilità]]
Vedi: [[Analisi 2/Spazi metrici/Segmento|Segmento]],[[Insieme convesso]],[[Estremi di insieme]]
#analisi2 