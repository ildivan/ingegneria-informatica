Sia $f:A \to R$ e sia $x_{0} \in \overset{\circ}{A}$ un punto stazionario di $f$ .
se $f$ è derivabile 2 volte in $x_{0}$ , allora valgono le seguenti affermazioni:
1. $f''(x_{0}) > 0 \implies x_{0}$ è un punto di minimo relativo
2. $f''(x_{0}) < 0 \implies x_{0}$ è un punto di massimo relativo

### DIM:
Dimostriamo la prima affermazione, la seconda si dimostra  in modo analogo.
Visto che $x_{0}$ è un punto stazionario di $f$ , allora $f'(x_{0}) = 0$ , quindi abbiamo che :$$f''(x_{0}) = \lim_{x\to x_{0}} \frac{f'(x)-f'(x_{0})}{x-x_{0}} = \lim_{x\to x_{0}}\frac{f'(x)}{x-x_{0}} > 0 \text{ per ipotesi}$$
quindi per il [[Teorema della permanenza del segno]] esiste un intorno $I_{\delta}(x_{0})$ t.c. $\forall x \in I_{\delta}(x_{0})\cap (A\backslash \{x_{0}\})$ in cui abbiamo che $\frac{f'(x_{0})}{x-x_{0}}> 0$ , quindi ciò implica che:
1. se $x \in (x_{0}-\delta,x_{0})$ allora $f'(x) <0$
2. se $x \in (x_{0},x_{0}+\delta)$ allora $f'(x) >0$ 
Quindi $x_{0}$ è un punto di minimo relativo.
$Q.E.D.$


Argomento principale: [[Calcolo Differenziale]]
Vedi: [[Derivate di ordine superiore]],[[Massimi e minimi di funzione]]

#analisi1