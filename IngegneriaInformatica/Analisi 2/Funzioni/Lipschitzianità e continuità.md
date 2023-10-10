Siano $(X,d_{x})$ e $(Y,d_{y})$ due spazi metrici, sia $A \subseteq X$.
Data $f: A \to Y$ ,
se $f$ è di lipschitz su $A$ allora è continua su $A$.
#### DIM
Per definizione di funzione di lipschitz:$$\exists L \ge 0 : \forall x_{1},x_{2}\in X \space d_{y}(f(x_{1}),f(x_{2}))\le Ld_{x}(x_{1},x_{2})$$
Dobbiamo dimostrare che $\forall x_{0}\in A$ $f$ è continua su $x_{0}$:$$\forall \epsilon>0 \exists \delta>0 : \forall x\in A \text{ t.c. } \space d_{x}(x,x_{0})< \delta \text{ vale } d_{y}(f(x),f(x_{0}))<\epsilon$$
Poniamo $\delta = \frac{\epsilon}{L}$ , dalla definizione di funzione di lipschitz :$$d_{y}(f(x_{1}),f(x_{2})) \le Ld_{x}(x_{1},x_{2})$$
Dato che $d_{x}(x_{1},x_{2})<\delta$:$$d_{y}(f(x_{1}),f(x_{2})) \le Ld_{x}(x_{1},x_{2}) \le L \delta = \epsilon$$
E quindi la definizione di continuità è soddisfatta.

Argomento principale: [[Funzioni in spazi metrici]]
Vedi: [[Funzioni di Lipschitz]], [[Continuità di funzioni in spazi metrici]]
#analisi2 