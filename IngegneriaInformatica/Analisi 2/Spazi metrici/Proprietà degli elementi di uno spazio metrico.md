Sia $(X,d)$ uno spazio metrico, sia $x_{0}\in X$ e $A\subseteq X$ $A\neq \emptyset$ , allora:
1) $x_{0}$ è interno ad $A$ $\xrightleftharpoons{} \exists r>0: B(x_{0},r)\subseteq A$ 
2) $x_{0}$ è esterno ad $A \xrightleftharpoons{} \exists r>0:B(x_{0},r)\cap A= \emptyset$ 
3) $x_{0}$ è di frontiera per A $\xrightleftharpoons{} \forall r>0: B(x_{0},r)\cap A \neq \emptyset \land B(x_{0},r) \cap (X\backslash A)\neq \emptyset$  
4) $x_{0}$ è di accumulazione per $A$ $\xrightleftharpoons{}  \forall r>0 B(x_{0},r)\cap A \backslash \{x_{0}\}$ 
5) $x_{0}$ è isolato per $A$ $\xrightleftharpoons{} \exists r>0 : B(x_{0},r)\cap A=\{x_{0}\}$

### Parte interna di $A$ 
Si dice parte interna di $A$ l'insieme:$$\mathring{A}=\set{x\in X:x \text{ è interno ad } A}$$
### Frontiera di $A$
Si dice frontiera di $A$ l'insieme:$$\partial A = \set{x\in X: x \text{ è di frontiera per } A}$$

### Chiusura di $A$
Si dice chiusura di $A$ l'insieme:$$\overline{A} = \set{x\in X: x\in A \text{ oppure } x \text{ di accumulazione per } A}$$

### Prop
Sia $(X,d)$ uno spazio metrico, sia $A \subseteq X : A\neq \emptyset$ ,
dato $x_{0}\in A$ , sappiamo che:$$\begin{cases}\text{o }x_{0}\text{ è isolato per } A  \\\text{o }x_{0}\text{ è di accumulazione per } A
\end{cases}$$
#### DIM
Se $x_{0}$ non è isolato per $A$ , allora :$$\forall r>0 \space B(x_{0},r)\cap A  \neq \{x_{0}\}$$
Equivalentemente:$$\forall r>0 \space B(x_{0},r)\cap A \backslash \{x_{0}\} \neq \emptyset$$
E questa è esattamente  la definizione di punto di accumulazione, la tesi è dimostrata.

Argomento principale: [[Spazi metrici]]
Vedi: [[Sfera aperta]]
#analisi2 