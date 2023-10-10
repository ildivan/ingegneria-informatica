Sia $(X,d)$ uno spazio metrico e sia $x:N \to X$ una successione.
$x$ è di Cauchy $\xrightleftharpoons{}$ $$\forall \epsilon > 0 \space\exists \nu\in N : \forall n,m > \nu \space d(x_{n},x_{m})<\epsilon$$
#### Prop 
Se $\exists l\in X$ tale che:$$\lim_{n \to +\infty} x_{n}=l$$
Allora $x$ è di Cauchy.
#### DIM
Per definizione di limite:$$\forall \epsilon> 0 \exists \nu\in N : \forall n > \nu \space d(x_{n},l)< \epsilon$$
Per definizione di successione di Cauchy:$$\forall \epsilon > 0 \space\exists \nu\in N : \forall n,m > \nu \space d(x_{n},x_{m})<\epsilon$$
Per proprietà della funzione distanza:$$d(x_{n},x_{m}) \le d(x_{n},l)+ d(x_{m},l) < 2 \epsilon$$
La definizione di successione di Cauchy è rispettata.


#### Prop 
Se $x$ è di Cauchy, allora è limitata.
#### DIM
Per definizione di successione di Cauchy:$$\forall \epsilon > 0 \space\exists \nu\in N : \forall n,m > \nu \space d(x_{n},x_{m})<\epsilon$$
Scelgo $\epsilon = 1$, quindi:$$\exists \overline{\nu} \in N : \forall n > \overline{\nu} \space d(x_{n},x_{\overline{\nu}}) < 1$$
Poniamo $K= \max_{n= 0 ,\ldots, \overline{\nu}-1}d(x_{n},x_{\overline{\nu}})$ , allora:$$\forall n \in N: d(x_{n},x_{\overline{\nu}})<max\{K,1\}$$
E quindi la successione è limitata.

Argomento principale: [[Successioni in spazi metrici]]
Vedi: [[Limitatezza di una successione]], [[Funzione distanza]]
#analisi2 