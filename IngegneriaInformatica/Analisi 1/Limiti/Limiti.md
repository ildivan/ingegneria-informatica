Sia $A\subseteq R$ ,sia $x_{0}\in R$ un punto di accumulazione di $A$ e sia $f:A\to R$ .
Diciamo che $f$ **converge**  a $L\in R$ per $x$ che tende ad $x_{0}$ e si scrive:$$\lim_{x\to x_{0}}f(x)=L$$
se:$$\forall \epsilon> 0 \space\exists \delta> 0 \text{ t.c. } \forall x\in I_{\delta}(x_{0})\cap (A\backslash \{x_{0}\}): |f(x)-L|<\epsilon$$
![[limite.png]]

#### NB
1) Non è richiesto che $x_{0}\in A$ 
2) Il valore di $f(x_{0})$ non influenza il valore del limite.


## Limiti infiniti
Estendiamo la definizione di limite nei casi in cui :$$\lim_{x\to x_{0}}f(x)=\pm \infty$$
Sia quindi $f:A\to R$ , $x_{0}\in R$ un punto di accumulazione di A e $L\in \{+\infty,-\infty\}$.
Ci sono due  casi:
1) $$\lim_{x\to x_{0}}f(x)=+\infty$$ se:$$\forall m\in R\exists \delta> 0 : \forall x\in I_\delta(x_{0})\cap(A\backslash\{ x_{0}\}): f(x)>m$$
2) $$\lim_{x\to x_{0}}f(x)=-\infty$$se:$$\forall m\in R\exists \delta> 0 : \forall x\in I_\delta(x_{0})\cap(A\backslash\{ x_{0}\}): f(x)<m$$
## Limiti ad infinito
Estendiamo la definizione di limite ai casi in cui $$\lim_{x\to\pm \infty}f(x)=L\in R$$
1) Sia quindi $f:[r,+\infty)\to R$ , $r\in R$  :$$\lim_{x\to +\infty}f(x)=L$$se:$$\forall \epsilon> 0 \exists a>r:\forall x\in (a,+\infty):|f(x)-L|<\epsilon$$
2) Sia $f:(-\infty,r]\to R$ , $r\in R$ :$$\lim_{x\to -\infty}f(x)=L$$se:$$\forall \epsilon> 0 \exists a<r : \forall x\in (-\infty,a): |f(x)-L|<\epsilon$$

## Limiti infiniti ad infinito

Estendiamo la definizione di limite ai casi:$$\lim_{x\to \pm \infty}f(x)=\pm \infty$$
1) Sia $f:[r,+\infty)\to R$ con $r\in R$,scriviamo: $$\lim_{x\to+\infty}f(x)=+\infty$$  se:$$\forall m\in R\space\exists x_{0}>r : \forall x \in(x_{0},+\infty)\space f(x)> m$$
2) Sia $f:[r,+\infty)\to R$ con $r\in R$,scriviamo:$$\lim_{x\to +\infty}f(x)=-\infty$$se:$$\forall m\in R \space \exists x_{0}> r : \forall x \in (x_{0},+inf)\space f(x)<m$$
La definizione per $x\to -\infty$ è simile.

Vedi: [[Elementi di topologia]],[[Funzioni]]
#analisi1 