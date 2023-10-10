### Rapporto incrementale:
Sia $A \subseteq R$ , sia $f:A \to R$ e siano $x_{1},x_{0}\in A$ con $x_{1}>x_{0}$ .
Chiamiamo $\frac{f(x_{1})-f(x_{0})}{x_{1}-x_{0}}$ il rapporto incrementale di $f$ tra $x_{1}$ e $x_{0}$ 

### Derivata:
Sia $A \subseteq R$ , sia $f:A \to R$ e sia $x_{0}\in \overset{\circ}{A}$ , se esiste il limite:$$\lim_{x \to x_{0}}\frac{f(x)-f(x_{0})}{x-x_{0}}$$ allora esso viene chiamato **derivata** di $f$ in $x_{0}$ e viene indicato con $f'(x_{0})$ .
Se inoltre $f'(x_{0})\in R$ , allora $f$ è **derivabile** in $x_{0}$ .

#### Notazioni alternative:
$$f'(x_{0})= Df(x_{0}) = \frac{df}{dx}(x_{0}) = f^{(1)}(x_{0})$$
##### nb:
$$f'(x_{0}) = \lim_{x \to x_{0}}\frac{f(x)-f(x_{0})}{x-x_{0}}= \lim_{t\to 0} \frac{f(x+t)-f(x)}{t}$$

## Funzione derivata
Sia $f:A \to R$ , definiamo $A' = \{x\in \overset{\circ}{A} : \text{ f è derivabile in x }\}$ .
Chiamiamo la **funzione derivata** di $f$ la funzione $f':A'\to R$ che ad ogni $x\in A'$ associa il valore di $f'(x)$.

##### Retta tangente:
La retta tangente al $graf(f)$ nel punto $(x_{0},f(x_{0}))$ è data dall' equazione $y = f(x_{0})+f'(x_{0})(x-x_{0})$ 

#analisi1