Sia $f: A \to R^{m}$ con $A \subseteq R^{n}$ e $x_{0}\in \overset{\circ}{A}$ .

Si dice che $f$ è **differenziabile** in $x_{0}$ $\xleftrightharpoons{}$ $$\exists M \in R^{m \times n} : f(x_{0}+h)-f(x_{0})=Mh +o(h) \text{ per } h \to 0$$O equivalentemente:$$f(x)-f(x_{0}) = M(x-x_{0})+o(x-x_{0}) \text{ per } x \to x_{0}$$

Dove $M$ è la matrice che chiamiamo **derivata completa di $f$ in $x_{0}$** :$$Df(x_{0}) = M$$
#### Notazione
$Df(x_{0})$  per $m \times n$  
$f'(x_{0})$ per $1 \times 1$ 
$\nabla f(x_{0})$ per $1 \times n$ 
$J_{f}(x_{0})$ per $n \times n$ 
$\overset{\dot{}}{f} (x_{0})$ per $m \times 1$ 

#### Legame tra derivata completa e derivate parziali 
Sia $f: A \to R^{m}$ con $A \subseteq R^{n}$ e $x_{0}\in \overset{\circ}{A}$ , 
Se $f$ è differenziabile in $x_{0}$ , allora:$$\forall i \in \set{1,\ldots,n} \space \partial_{i}f(x_{0}) = Df(x_{0})e_{i}$$
Ovvero la matrice della derivata completa ha per colonne le derivate parziali.
#### DIM
Dalla definizione di derivata parziale:$$\lim_{h \to 0}\frac{f(x_{0} + he_{i})-f(x_{0})}{h}$$
Per definizione di derivata abbiamo:$$f(x_{0}+he_{i}) = f(x_{0}) + Df(x_{0})he_{i}+o(he_{i})$$
Quindi:$$\lim_{h \to 0}\frac{f(x_{0} + he_{i})-f(x_{0})}{h} = \lim_{h \to 0}\frac{Df(x_{0})he_{i}+o(he_{i})}{h}$$$$= \lim_{h \to 0} Df(x_{0})e_{i}+\lim_{h \to 0}\frac{o(he_{i})}{h} = Df(x_{0})e_{i}$$
Vedi: [[o piccolo]],[[Derivate parziali]]
#analisi2 