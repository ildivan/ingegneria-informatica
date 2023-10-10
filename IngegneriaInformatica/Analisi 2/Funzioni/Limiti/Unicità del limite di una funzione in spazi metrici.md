Siano $(X,d_{x})$ e $(Y,d_{y})$ spazi metrici, sia $A \subseteq X$ , sia $x_{0}$  di acc. per $A$.
Data $f: A \to Y$ , se:$$\exists l,L\in Y : \lim_{x \to x_{0}}f(x)=l ,\lim_{x \to x_{0}}f(x)=L$$
allora $l = L$

#### DIM
Per definizione di limite:$$\forall \epsilon> 0 \exists \delta' > 0 : \forall x\in A \text{ t.c. } x \neq x_{0}, d_x(x,x_{0})<\delta' \text{ vale } d_{y}(f(x),l)<\epsilon$$$$\forall \epsilon> 0 \exists \delta'' > 0 : \forall x\in A \text{ t.c. } x \neq x_{0}, d_x(x,x_{0})<\delta'' \text{ vale } d_{y}(f(x),L)<\epsilon$$
Scegliamo $\epsilon$ tale che $\delta = \min\{\delta',\delta''\}$ , quindi consideriamo:$$d_{y}(l,L) \le d_{y}(f(x),l)+d_{y}(f(x),L) < 2\epsilon$$
E quindi per arbitrarietà di $\epsilon$:$$d_{y}(l,L)=0 \implies l=L$$
Argomento principale: [[Funzioni in spazi metrici]]
Vedi: [[Teorema di unicità del limite]],[[Unicità del limite di successione in spazio metrico]]
#analisi2 
