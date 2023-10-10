Siano $(X,d_{x})$ e $(Y,d_{y})$ spazi metrici, sia $A \subseteq X$ .
$f: A \to Y$ è continua in $x_{0}\in A$ se:$$\forall \epsilon > 0 \space \exists \delta\in N : \forall x\in A \space t.c. d_{x}(x,x_{o}) < \delta \implies d_{y}(f(x),f(x_{0}))< \epsilon$$
$f: A \to Y$ è continua in $A$ se:$$\forall x \in A : f \text{ è continua in } x$$
### Prop 
Siano $(X,d_{x})$ e $(Y,d_{y})$ spazi metrici, sia $A \subseteq X$ .
$f:A \to Y$ è continua in $x_{0}\in A$ $\iff$ $$\begin{cases}
 \text{ o } x_{0} \text{ è di acc. per } A \text{, e  }  \lim_{x \to x_{0}} f(x) = f(x_{0}) \\
\text{ o } x_{0} \text{ è isolato per } A
\end{cases}$$
#### DIM
Per continuità: $$\forall \epsilon > 0 \space \exists \delta\in N : \forall x\in A \space t.c. d_{x}(x,x_{o}) < \delta \space d_{y}(f(x),f(x_{0}))< \epsilon$$
Vale $\forall x \in A$ , quindi vale anche $\forall x\in A : x \neq x_{0}$:$$\forall \epsilon > 0 \space \exists \delta\in N : \forall x\in A \space t.c. x \neq x_{0} \land d_{x}(x,x_{o}) < \delta \space d_{y}(f(x),f(x_{0}))< \epsilon$$
Questa però è la definizione di limite per $l = f(x_{0})$.
Inversamente, se $x = x_{0}$ allora $d_{y}(f(x),f(x_{0})) = 0 < \epsilon$ in quanto $f(x) = f(x_{0})$ , e quindi $f$ è continua.

Se $x_{0}$ è un punto isolato di $A$ allora $\exists r > 0 : B(x_{0},r)\cap A = \{x_{0}\}$ ,
se prendiamo la definizione di continuità con $\delta= r$ allora:$$\forall \epsilon > 0 \space \forall x\in A \space t.c. d_{x}(x,x_{o}) < r \space d_{y}(f(x),f(x_{0})) = 0< \epsilon$$
E quindi è continua in $x_{0}$.

Vedi: [[Continuità]]
#analisi2 