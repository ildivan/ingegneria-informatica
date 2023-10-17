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
## Dalle derivate parziali alla derivata completa
Sia $f: A \to R^{m}$ con $A \subseteq R^{n}$ con $x_{0}\in \overset{\circ}{A}$ ,
Se $\forall i \in \set{ 1,\ldots,n }$ esiste la $i$-esima derivata parziale in un intorno di $x_{0}$ , ed è continua in  $x_{0}$, allora $f$ è differenziabile in $x_{0}$.
#### DIM (Caso da $R^2$ ad $R$)
Sia $f: A \to R$ con $A \subseteq R^{2}$ e $(x_{0},y_{0})\in \overset{\circ}{A}$ ,
Dobbiamo dimostrare che esistono $\partial_{x}f(x_{0},y_{0})$ e $\partial_{y}f(x_{0},y_{0})$ e che siano continue in $(x_{0},y_{0})$.

Ovviamente vale che:$$f(x_{0}+h,y_{0}+k)-f(x_{0},y_{0})$$$$= [f(x_{0}+h,y_{0}+k)-f(x_{0}+h,y_{0})]+[f(x_{0}+h,y_{0})-f(x_{0},y_{0})]$$
Per $(h,k)$ con norma sufficientemente piccola, grazie al [[Teorema di Lagrange]] possiamo scrivere:$$f(x_{0}+h,y_{0}+k) -f(x_{0}+h,y_{0})= \partial_{y}f(x_{0}+h,y_{0}+\beta k)k$$$$f(x_{0}+h,y_{0})-f(x_{0},y_{0})=\partial_{x}f(x_{0}+\alpha h,y_{0})h$$
dove $\alpha,\beta\in ]0,1[$ . Quindi troviamo che:$$f(x_{0}+h,y_{0}+k) -f(x_{0},y_{0}) = \partial_{x}f(x_{0}+\alpha h,y_{0})h+\partial_{y}(x_{0}+h,y_{0}+ \beta k)k$$
Sottraiamo da entrambe le parti $Df(x_{0},y_{0})\begin{bmatrix}h \\ k\end{bmatrix} = \frac{\partial f}{\partial x}(x_{0},y_{0})h + \frac{\partial f}{\partial y}(x_{0},y_{0})k$$$f(x_{0}+h,y_{0}+k)-f(x_{0},y_{0})-Df(x_{0},y_{0})\begin{bmatrix}
h \\ k
\end{bmatrix}$$$$= (\frac{\partial f}{\partial x}(x_{0}+\alpha h ,y_{0} )- \frac{\partial f}{\partial x}(x_{0},y_{0}))h+(\frac{\partial f}{\partial y}(x_{0}+h,y_{0}+ \beta k) - \frac{\partial f}{\partial y}(x_{0},y_{0}))k$$ 
Ragioniamo per norme:
$$||f(x_{0}+h,y_{0}+k) - f(x_{0},y_{0})-Df(x_{0},y_{0})\begin{bmatrix}
h \\ k
\end{bmatrix}|| \le$$$$||(\frac{\partial f}{\partial x}(x_{0}+\alpha h ,y_{0} )- \frac{\partial f}{\partial x}(x_{0},y_{0}))h||+||(\frac{\partial f}{\partial y}(x_{0}+h,y_{0}+ \beta k) - \frac{\partial f}{\partial y}(x_{0},y_{0}))k||$$$$\le ||(\frac{\partial f}{\partial x}(x_{0}+\alpha h ,y_{0} )- \frac{\partial f}{\partial x}(x_{0},y_{0}))|| \space ||h|| +||(\frac{\partial f}{\partial y}(x_{0}+h,y_{0}+ \beta k) - \frac{\partial f}{\partial y}(x_{0},y_{0}))|| \space ||k||$$$$\le ||(\frac{\partial f}{\partial x}(x_{0}+\alpha h ,y_{0} )- \frac{\partial f}{\partial x}(x_{0},y_{0}))|| \space \sqrt{h^{2}+k^{2}} +||(\frac{\partial f}{\partial y}(x_{0}+h,y_{0}+ \beta k) - \frac{\partial f}{\partial y}(x_{0},y_{0}))|| \space \sqrt{h^{2}+k^{2}}$$$$= o(1)\sqrt{h^{2}+k^{2}} \text{ per } \begin{bmatrix}
h \\ k
\end{bmatrix} \to 0$$
E quindi abbiamo la differenziabilità.

Vedi: [[o piccolo]],[[Derivate parziali]]
#analisi2 