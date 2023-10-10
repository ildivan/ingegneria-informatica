Sia $f:A \to R$  e sia $x_{0} \in \overset{\circ}{A}$ un punto di estremo relativo di f.
se f è derivabile in $x_{0}$ , allora $f'(x_{0})=0$ .

### DIM:
Supponiamo , ad esempio che $x_{0}$ sia un punto di  massimo relativo.
Siccome $x_{0}\in \overset{\circ}{A}$ , allora:$$\exists \delta > 0 \space t.c. \forall x \in I_{\delta}(x_{0}):f(x) \le f(x_{0})$$
Sappiamo che $\forall x \in (x_{0}-\delta , x_{0})$ il rapporto incrementale tra x e $x_{0}$ è positivo:$$\frac{f(x)-f(x_{0})}{x-x_{0}} \ge 0$$
Quindi per il [[Teorema del confronto]] si ha che: $$f'_{-}(x_{0}) = \lim_{x \to x_{0-}}(\frac{f(x)-f(x_0)}{x-x_{0}})\ge 0$$
D'altro canto sappiamo che $\forall x\in (x_{0},x_{0}+ \delta)$ abbiamo:$$\frac{f(x)-f(x_{0})}{x-x_{0}}\le 0$$
Per il teorema del confronto:$$f'_{+}(x_{0})= \lim_{x\to x_{0+}}\frac{f(x)-f(x_{0})}{x-x_{0}}\le 0$$
Siccome per ipotesi f è derivabile in $x_{0}$ , si ha che :$$0 \le f'_{-}(x_{0}) = f'_{+}(x_{0}) \le 0 \implies f'(x_{0}) = 0$$
$Q.E.D.$

Vedi: [[Massimi e minimi di funzione]], [[Elementi di topologia]]


#analisi1 