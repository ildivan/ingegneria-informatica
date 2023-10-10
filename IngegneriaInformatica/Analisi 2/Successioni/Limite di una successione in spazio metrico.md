Sia $(X,d)$ uno spazio metrico e sia $x: N \to X$ una successione.

Si definisce come limite per $n$ che tende a $+\infty$ di $x_{n}$:$$\lim_{n\to +\infty}x_{n}= l\in X \xrightleftharpoons{} \forall \epsilon > 0 \space\exists \nu \in N : \forall n > \nu \space d(x_{n},l)< \epsilon $$
#### Prop
$$\lim_{n \to + \infty} x_{n}=l \iff \lim_{n \to + \infty}d(x_{n},l) = 0$$

#### DIM
Dalla definizione di limite:$$\forall \epsilon> 0 \space \exists \nu\in N : \forall n>\nu: d(x_{n},l)<\epsilon$$
Quindi:$$\lim_{n \to+\infty} d(x_{n},l) = 0 \implies \forall \epsilon> 0 \space \exists \nu\in N : \forall n>\nu: |d(x_{n},l)| <\epsilon$$
$$\implies \lim_{n \to +\infty}x_{n} = l$$
La tesi è verificata.

Argomento principale: [[Successioni in spazi metrici]]
Vedi: [[Spazi metrici]]
#analisi2 