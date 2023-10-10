Sia $[a,b]\subset R$  un intervallo chiuso e limitato e sia $f:[a,b]\to R$ continua in tutto $[a,b]$ .
Allora $f$ assume tutti i valori tra il minimo e il massimo di $f$ .$$\forall y \in [\underset{[a,b]}{min} f,\underset{[a,b]}{max}f] \space\exists c\in [a,b] \text{ t.c. } f(c)=y$$
### DIM
Dal [[Teorema di Weierstrass]] segue che:$$\exists x_{min},x_{max}\in [a,b] \text{ t.c. } \forall x\in[a,b] \space f(x_{min})\le f(x) \le f(x_{max}) $$
Siano $m = f(x_{min})$ e $M = f(x_{max})$ 

Supponiamo che $x_{min}< x_{max}$ :
Sia $y\in[m,M]$ , devo dimostrare che $\exists c\in[a,b]$ t.c. $f(c) = y$ .

Se $y\in\{m,M\}$ la tesi è verificata dal teorema di weierstrass, quindi $y\in (m,M)$.

Definisco la funzione $g:[x_{min},x_{max}]\to R$ data da:$g(x) = f(x)-y$ 

Notiamo che $g$ è continua.
Visto che:$$g(x_{min})= m-y < 0 \text{ e } g(x_{max})= M-y > 0$$
il [[Teorema degli zeri di Bolzano]] implica che:$$\exists c \in (x_{min},x_{max})\subset [a,b] \space \text{ t.c. } g(c)= 0 \iff f(c)=y$$
Il teorema si considera dimostrato.

Argomento principale: [[Continuità]]
Vedi:[[Massimi e minimi di funzione]]
#analisi1 