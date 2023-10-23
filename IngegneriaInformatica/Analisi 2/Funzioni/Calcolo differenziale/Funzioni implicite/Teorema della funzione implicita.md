Sia $f: X \times Y \to R^{m}$ con $X \subseteq R^{n}$ e $Y \subseteq R^{m}$ , tale che $f\in C^{0}(X \times Y , R^{m})$ .
Siano $x_{0}\in \overset{\circ}{X}$ e $y_{0}\in \overset{\circ}{Y}$ tali che:$$f(x_{0},y_{0}) = 0$$ 
Consideriamo la funzione $f_{x}: Y \to R^{m}$ che rappresenta la funzione $f(x,y)$ con $x$ tenuto costante, chiamiamo nel seguente modo la sua derivata:$$Df_{x}= D_{y}f \in R^{m \times m}$$
Se $\exists D_{y}f$ in un intorno di $(x_{0},y_{0})$ continua in $(x_{0},y_{0})$ e sia $D_{y}f(x_{0},y_{0})$ invertibile, allora: $$\exists Z \subseteq X , W \subseteq Y \text{ con } x_{0}\in Z , y_{0}\in W$$$$\exists \phi : Z \to W \text{ tale che } \begin{cases}
f(x_{0},y_{0})= 0 \\
x\in Z \\
y\in W \\

\end{cases} \iff y = \phi(x)$$
Inoltre, la funzione implicita $\phi$ da $f(x,y) = 0$ in un intorno di $(X_{0},y_{0})$ è unica:$$\exists \phi_{1}: Z_{1}\to W_{1},\phi_{2}: Z_{2}\to W_{2}\implies \phi_{1}(x)=\phi_{2}(x) \space \forall x\in Z_{1}\cap z_{2}\cap Z$$
#### DIM
Definiamo la funzione :$$T : \overline{B(x_{0},r_{x})} \times\overline{B(y_{0},r_{y})} \to \overline{B(y_{0},r_{y})}$$$$T : x,y \to y - [D_{y}f(x_{0},y_{0})]^{-1}f(x,y)$$
Dimostriamo che $T$ è una contrazione, quindi innanzitutto dimostriamo che:$$||T(x,y_{2})-T(x,y_{1})|| \le K||y_{2}-y_{1}||$$
Definiamo $$D_{y}T(x,y) = Id - [D_{y}f(x_{0},y_{0})]^{-1}D_{y}f(x,y)=$$$$= [D_{y}f(x_{0},y_{0})]^{-1}(D_{y}f(x_{0},y_{0})-D_{y}f(x,y))$$ Visto che possiamo scegliere $r_x$ e $r_{y}$ piccoli a scelta, otteniamo che $|| D_{y}T(x,y)||$ è piccolo a piacere:$$||D_{y}T(x,y)|| \le||[D_{f}(x_{0},y_{0})]^{-1}||\cdot||D_{y}f(x_{0},y_{0})-D_{y}f(x,y)||< \frac{1}{2}$$
$\frac{1}{2}$ è un numero arbitrario , che sarà comodo per la dimostrazione.

Per il [[Teorema degli accrescimenti finiti]]:$$||T(x,y_{2})-T(x,y_{1})|| \le \sup_{y \in \overline{B(y_{0},r_{y})}}||D_{y}T(x,y)||\cdot||y_{2}-y_{1}|| \le \frac{1}{2}||y_{2}-y_{1}||$$
Dove $\frac{1}{2}$ è la costante di contrazione.

Per dimostrare che $T$ è una contrazione non ci resta dimostrare che l'insieme di partenza e di arrivo coincidano , ovvero che $T$ ha valori in $\overline{B(y_{0},r_{y})}$ :$$\forall x \in \overline{B(x_{0},r_{x})} \forall y \in \overline{B(y_{0},r_{y})} \space T(x,y)\in \overline{B(y_{0},r_{y})}$$
Partiamo dalla seguente norma:$$|| T(x,y)-y_{0}|| = ||T(x,y)-T(x,y_{0})|| + ||T(x,y_{0})-y_{0}||$$$$= ||T(x,y)-T(x,y_{0})|| + ||y_{0}-[D_{y}f(x_{0},y_{0})]^{-1}f(x,y_{0})-y_{0}||$$$$= ||T(x,y)-T(x,y_{0})|| + ||[D_{y}f(x_{0},y_{0})]^{-1}f(x,y_{0})||$$$$\le \frac{1}{2}||y-y_{0}|| + ||[D_{y}f(x_{0},y_{0})]^{-1}|| \cdot ||f(x,y_{0}) - 0||$$
Essendo $f(x_{0},y_{0})= 0$ per ipotesi, allora:$$|| T(x,y)-y_{0}|| \le \frac{1}{2}||y-y_{0}|| + ||[D_{y}f(x_{0},y_{0})]^{-1}|| \cdot ||f(x,y_{0}) - f(x_0,y_{0})||$$$$ \le \frac{1}{2}r_{y}+ \frac{1}{2}r_{y} = r_{y}$$
Quindi $||T(x,y)-y_{0}|| \le r_{y} \implies$ $T$ è a valori in $\overline{B(y_{0},r_{y})}$ , e di conseguenza abbiamo dimostrato che $T$ è una **contrazione.**

Grazie al [[Teorema delle contrazioni]] troviamo il punto fisso di $T$ , e troviamo che è il punto che soddisfa $f(x,y)=0$:$$T(x,y)=y$$$$y-[D_{y}f(x_{0},y_{0})]^{-1}f(x,y) = y$$$$-[D_{y}f(x_{0},y_{0})]^{-1}f(x,y) = 0$$$$\implies T(x,y)=y \iff f(x,y)=0$$
Detto questo possiamo affermare che $\forall x \in \overline{B(x_{0},r_{x})} \space \exists ! y \in \overline{B(y_{0},r_{y})}: T(x,y)= y$ $$\exists \phi:\overline{B(x_{0},r_{x})} \to \overline{B(y_{0},r_{y})} \space y = \phi(x) \iff T(x,y)=y \iff f(x,y)=0 $$
E quindi sia l'esistenza che l'unicità sono dimostrate.

Argomento principale: [[Funzione implicita]]
Vedi: [[Teorema della funzione implicita (caso lineare)]],[[Contrazione]]
#analisi2 