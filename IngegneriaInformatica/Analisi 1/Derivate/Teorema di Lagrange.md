sia $f:[a,b] \to R$  t.c: 
	$f$ è continua in $[a,b]$
	$f$ è derivabile in $(a,b)$ 

allora $\exists  c  \in (a,b)  t.c.  f'(c) = \frac{f(b)-f(a)}{b-a}$ 

NB: è una generalizzazione del [[Teorema di Rolle]]

#### DIM:
sia $g:[a,b] \to R$ data da $$g(x) = f(x) -(x-a) \cdot \frac{f(b)-f(a)}{b-a}$$ 
quindi $g$ è continua in $[a,b]$ e è derivabile in $(a,b)$ e inoltre :$$g(a) = f(a)$$e  $$g(b) = f(b)-(f(b)-f(a)) = f(a) = g(a)$$ quindi applicando il [[Teorema di Rolle]] otteniamo che :$$\exists \space c \in \space (a,b) \space t.c. \space g'(c) = 0$$
abbiamo che :$$g'(x) = f'(x)-\frac{f(b)-f(a)}{b-a}$$
 ne segue che:$$f'(c) = \frac{f(b)-f(a)}{b-a}$$
 $Q.E.D$
 
### Significato geometrico:

Il teorema di lagrange dice che esiste un punto c nell'intervallo $(a,b)$ in cui la retta tangente al $graf(f)$  è parallela al segmento che congiunge i due punti estremi dell'intervallo:

![[lagrange.png]]


### Conseguenze : 
1. [[Teorema della derivata nulla]]
2. [[Derivata prima e monotonia]]

Argomento principale: [[Calcolo Differenziale]]

#analisi1