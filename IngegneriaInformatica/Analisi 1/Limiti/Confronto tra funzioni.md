Sia $x_{0}\in \overline{R}$ e siano $f,g$ due funzioni definite in un intorno di $x_{0}$. Supponiamo che:$$\lim_{x\to x_{0}}f(x)=\lim_{x\to x_{0}}g(x) \in \{0,+\infty,-\infty\}$$Allora se esiste il limite:$$\lim_{x \to x_{0}}\frac{f(x)}{g(x)}= L \in \overline{R}$$Diciamo che:
1. $f$ è **trascurabile** rispetto a $g$ per $x \to x_{0}$ e scriviamo $f(x) = o(g(x))$ per $x\to x_{0}$ se $L=0$ 
2. $g$ è **trascurabile** rispetto  a $f$ per $x\to x_{0}$ e scriviamo $g(x)=o(f(x))$ per $x\to x_{0}$ se $L = \pm \infty$ 

#### Confronto tra alcune funzioni elementari
- $x^{n}= o(x^{m})$ per $x\to 0 \leftrightarrow n > m \space : n,m \in Z$  
- $x^{m}= o(x^{n})$ per $x\to +\infty \leftrightarrow n < m \space : n,m \in Z$  
- $x^{\alpha}= o(e^{x})$ per $x\to +\infty \space\forall \alpha\in R$  
- $e^{x}=o(|x|^\alpha)$ per $x\to -\infty$  $\forall \alpha\in R$ 
- $logx = o(x^\alpha)$ per $x\to +\infty$  $\forall \alpha> 0$ 
- $logx = o(x^{-\alpha})$ per $x\to 0^{+}$  $\forall \alpha> 0$  

Argomento principale: [[Limiti]]

#analisi1