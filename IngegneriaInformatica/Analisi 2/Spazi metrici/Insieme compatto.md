Sia $(X,d)$ uno spazio metrico, sia $C\subseteq X, C \neq \emptyset$ .
$C$ è compatto $\xrightleftharpoons{}$$$\forall x : N \to X \text{ con } x_{n}\in C \space\forall n \in N \space $$$$\exists \text{ sottosuccessione convergente ad un } l\in C$$
#### Prop 
$C$ è compatto $\implies$ $C$ è chiuso e limitato
#### DIM
Per assurdo, ipotizziamo che $C$ non è chiuso:$$C\neq \overline{C}\implies C \subset \overline{C} \implies \exists x_{0} \text{ di acc. per } C : x_{0}\notin C$$$$\implies \exists x: N \to X\text{ t.c. } \begin{cases} x_{n}\in C \space \forall n \in N  \\
 \lim_{n \to +\infty} x_{n}= x_{0} \notin C \implies C \text{ non è compatto.}\end{cases}$$
Ora ipotizziamo che $C$ non sia limitato:
$$\implies \sup_{x,y\in C} d(x,y) = +\infty$$
$$\forall x_{0} \in C  \sup_{x\in C} d(x,x_{0}) = +\infty$$$$\forall n\in N \space \exists x_{n} \in C : d(x_{n},x_{0})> n$$$$\implies \text{ qualunque sottosuccessione di x è illimitata} \implies C \text{ non è compatto}$$
#### Prop 
Sia $(R^{n},d)$ con $d(x,y) = ||y-x||$, sia $C \subseteq R^{n}$ $C \neq \emptyset$
$C$ è compatto $\iff$ $C$ è chiuso e limitato.

Argomento principale: [[Spazi metrici]]
Vedi:[[Successioni in spazi metrici]],[[Limitatezza di una successione]],[[Funzione distanza]],[[]]
#analisi2 