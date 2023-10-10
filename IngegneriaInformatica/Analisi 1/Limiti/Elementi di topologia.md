#### Intorni
Dato un $x_{0}\in R$ e $r > 0$, chiamiamo intorno di centro $x_{0}$ e raggio $r$ il seguente [[Intervallo]] :$$I_{r}(x_{0})=(x_{0}-r,x_{o}+r)$$
Se $x_{0}\in \{-\infty,+\infty\}$ e sia $a \in R$ , chiamiamo:
	$(a,+\infty)$ intorno di $+\infty$ di estremo inferiore $a$
	$(-\infty,a)$ intorno di $-\infty$ di estremo superiore $a$


#### Punto interno, di accumulazione ed isolato
Sia $A\subseteq R$ un insieme e $x_{0}\in R$ .
$x_{0}$ può essere:
- punto interno di $A$ se $\exists \epsilon>0$ t.c. $I_{\epsilon}(x_{0})\subseteq A$ 
- punto di accumulazione di $A$ se $\forall \epsilon> 0 : I_{\epsilon}(x_{0})\cap (A\backslash \{x_{0}\}) \neq \emptyset$ 
- punto isolato di $A$ se $\exists \epsilon>0: I_{\epsilon}(x_{0})\cap A=\{x_{0}\}$ 

**NB:** ogni punto interno è anche un punto di accumulazione

## Notazione:
$\overset{\circ}{A}$ è la parte interna di $A$
$\overline{A}$ è la chiusura di A
$\delta A = \overline{A}\backslash\overset{\circ}{A} = \{x\in\overline{A}:x\notin \overset{\circ}{A}\}$ è la frontiera di $A$ 
$\overset{\circ}{A} \subseteq A \subseteq \overline{A}$ 

Argomento principale: [[Limiti]]
#analisi1