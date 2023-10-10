Si passa da $x\in [a,b]$ alla variabile $t\in[c,d]$ tramite una funzione biiettiva $\phi:[c,d]\to[a,b]$ di classe $C^{1}(c,d)$ e tale che $x = \phi(t)$

Sia $f:[a,b]\to R$ continua e sia $\phi:[c,d]\to[a,b]$ biettiva e di classe $C^{1}(c,d)$, allora:$$\int_{a}^{b}f(x)dx = \int_{\phi^{-1}(a)}^{\phi^{-1}(b) }f(\phi(t))\phi'(t)dt$$
### DIM:
Sia $F$ una primitiva di $f$ .
Allora $\frac{d}{dt}F(\phi(t))$ = $F'(\phi(t))\phi'(t)$ = $f(\phi(t))\phi'(t)$ .
Quindi possiamo affermare che $F(\phi(t))$ è una primitiva di $f(\phi(t))\phi'(t)$ , e di conseguenza :$$\int_{\phi^{-1}(a) }^{\phi^{-1}(b)}f(\phi(t))\phi'(t)dt = [F(\phi(t))]_{\phi^{-1}(a) }^{\phi^{-1}(b) } = F(\phi(\phi^{-1}(b))) - F(\phi(\phi^{-1}(a)))$$
$\phi(\phi^{-1}(b))$ diventa $b$ e $\phi(\phi^{-1}(a))$ diventa a, quindi l'integrale equivale a:$$F(b)-F(a) = \int_{a}^{b}f(x)dx$$

### NB:
Cambiare sempre gli estremi di integrazione.

Argomento principale: [[Integrale di Riemman]]
Vedi: [[Primitive]],[[Funzioni biiettive]],[[Insieme delle funzioni derivabili]],[[Continuità]]
#analisi1 