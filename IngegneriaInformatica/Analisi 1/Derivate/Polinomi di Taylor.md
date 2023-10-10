Sia $f:A \to R$ e sia $x_{0}\in \overset{\circ}{A}$,supponiamo che $f \in C^{n}(x_{0})$ 

#### Obbiettivo:
Vogliamo approssimare $f$ con un polinomio di grado $\le n$ in modo tale che:$$f(x)-Pn(x)=o((x-x_{0})^{n}) \text{ per } x\to x_{0}$$
### DEF:
Sia $f$ derivabile $n$ volte in un intorno di $x_{0}$ .
Allora chiamiamo polinomio di taylor di f di grado n e di centro $x_{0}$ il seguente:$$(T_{x_{0}}^{n}f)(x)=\sum\limits_{k=0}^{n}\frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k}$$
##### NB:
se $x_{0}=0$, scriviamo:$$(T^{n}f)(x)=\sum\limits_{k=0}^{n}\frac{f^{(k)}(x_{0})}{k!}x^{k}$$


### Formula di Taylor con resto di Peano
Sia $f:A \to R$ e sia $x_{0}\in \overset{\circ}{A}$ e supponiamo che $f\in C^{n}(x_{0})$.
Allora vale:$$f(x) = (T^{n}_{x_{0}}f)(x)+o((x-x_{0})^{n})$$
###### per n=1:
$$(T^{1}_{x_{0}}f)(x) = f(x_{0})+f'(x_{0})(x-x_{0})$$
###### per n=2:
$$(T^{1}_{x_{0}}f)(x) = f(x_{0})+f'(x_{0})(x-x_{0})+\frac{f''(x_{0})}{2}(x-x_{0})^{2}$$

###### per n=3:
$$(T^{1}_{x_{0}}f)(x) = f(x_{0})+f'(x_{0})(x-x_{0})+\frac{f''(x_{0})}{2}(x-x_{0})^{2}+\frac{f^{(3)}(x_{0})}{6}(x-x_{0})^{3}$$


Argomento principale: [[Calcolo Differenziale]]
Vedi: [[Confronto tra funzioni]], [[Limiti]],[[Insieme delle funzioni derivabili]]

#analisi1