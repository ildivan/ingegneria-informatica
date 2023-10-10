Sia $A \subseteq R$ e siano $f,F : A \to R$ .
Diciamo che $F$ è primitiva di $f$ se $F$ è derivabile in $A$ e se $\forall x \in A: F'(x)=f(x)$

Se $f$ ammette almeno una primitiva , allora rappresentiamo la famiglia di funzioni primitive di $f$ con:$$\int f(x)dx$$
Lo chiamiamo **integrale indefinito**.

##### NB:
Se $F(x)$ è una primitiva di $f$,anche $F(x)+c \forall c\in R$ è una primitiva di $f$.
Non tutte le funzioni integrabili ammettono primitiva.

### TEO:
Sia $I\subseteq R$  un intervallo e sia $f:I\to R$ .
Supponiamo che esistono due primitive di $f$ e chiamiamole $F_{1}(x)$ e $F_{2}(x)$.
Allora esiste una costante $x\in I$ tale che:$$\forall c\in R: F_{1}(x)=F_{2}(x)+c$$
#### DIM:
Sia $F = F_{1}-F_{2}$ , abbiamo che:$$F'(x)=F_{1}'(x)-F_{2}'(x)=f(x)-f(x)=0$$
Per il [[Teorema della derivata nulla]]:$$\forall x \in I : f(x)=c$$
#### Convenzione:
$$\begin{matrix} \int_{\alpha}^{\beta}f(x)dx = -\int_{\beta}^{\alpha}f(x)dx \\ \int_{\alpha}^{\alpha}f(x)dx=0 \end{matrix}$$

### Primitive di funzioni elementari:
$$\begin{matrix} \int x^{\alpha}dx=\frac{x^{\alpha+1}}{\alpha+1}+c \space \forall \alpha\neq -1 \\ \int x^{-1}dx= log|x|+c \\ \int sin(x)dx = -cosx+c \\ \int cos(x)dx=sinx+c \\ \int e^{x}dx=e^{x}+c \\ \int \frac{1}{x^{2}+1}dx=arctan(x)+c \end{matrix}$$

Argomento principale: [[Integrale di Riemman]]
#analisi1 