Diciamo che $f:A\to R$ è:
1) **crescente** in $A$ , se:$$\forall x,y \in A:x<y \implies f(x)\le f(y)$$
2) **decrescente** in $A$, se:$$\forall x,y \in A: x<y \implies f(x) \ge f(y)$$
3) **strettamente crescente** in $A$, se:$$\forall x,y \in A: x<y \implies f(x) < f(y)$$
4) **strettamente decrescente** in $A$, se:$$\forall x,y \in A: x<y \implies f(x) > f(y)$$

### Funzioni crescenti e limiti unilateri
Sia $f:A\to R$ e sia $x_{0}\in R$ un punto di accumulazione di $A\cap (x_{0},+\infty)$ e $A\cap(-\infty,x_{0})$ .
Se $f$ è crescente in $A$ , allora $f$ ammette in $x_{0}$ entrambi  i limiti unilateri e vale che:$$\lim_{x\to x_{0+}}f(x)=inf\{f(x):x>x_{0},x\in A\}$$
$$\lim_{x\to x_{0-}}f(x)=sup\{f(x):x<x_{0},x\in A\}$$
### DIM
Sia $l=inf\{f(x): x>x_{0},x\in A\}$:
1) è minorante $l\le f(x) \forall x>x_{0},x\in A$ 
2) $\forall \epsilon>0\exists x_\epsilon>x_{0} , x_\epsilon\in A : f(x_\epsilon)\le l+\epsilon$ 

Sia $\epsilon>0$ arbitrario $\implies$ pongo $\delta=x_{\epsilon}-x_{0}>0$ 
allora:$$\forall x\in A\cap(x_{0},x_{0}+\delta)=A\cap(x_{0},x_\epsilon):$$
$$0\le f(x)-l\le f(x_{\epsilon})-l<\epsilon$$ Quindi $|f(x)-l|<\epsilon\implies$:$$\lim_{x\to x_{0+}}f(x)=l$$
Sia $L=sup\{f(x): x<x_{0},x\in A\}$:
1) $\forall x<x_{0},x\in A: f(x)\le L$ quindi $L$ è maggiorante
2) $\forall \epsilon\exists x_\epsilon<x_{0}, x_\epsilon\in A : f(x_\epsilon)>L-\epsilon$

Sia $\epsilon>0$ arbitrario $\implies$ pongo $\delta=x_{0}-x_\epsilon>0$ 
$$\forall x\in A\cap(x_{0}-\delta,x_{0})=A\cap(x_\epsilon,x_{0}):$$
$$0\le L-f(x)\le L-f(x_\epsilon)<\epsilon$$
$l$ e $L$ possono non combaciare.


Argomento principale: [[Funzioni]]
#analisi1