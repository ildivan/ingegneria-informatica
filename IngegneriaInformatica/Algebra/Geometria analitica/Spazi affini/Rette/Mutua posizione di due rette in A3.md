Siano $r$ e $s$ due rette di $A_{3}(R)$ , studiarne la mutua posizione equivale a studiare il sistema delle loro equazioni:
$$r=[P;V_{1}]:\begin{cases}ax+by+cz+d=0\\a'x+b'y+c'z+d'=0\end{cases}$$$$\text{ con }rk\begin{pmatrix}a & b & c \\ a' & b' & c'\end{pmatrix}=2$$
$$s=[Q;V_{1}']:\begin{cases}a''x+b''y+c''z+d''=0 \\
a'''x+b'''y+c'''z+d'''=0\end{cases}$$
$$\text{ con }rk\begin{pmatrix}a'' & b'' & c'' \\ a''' & b''' & c'''\end{pmatrix}=2$$
Quindi studiamo il seguente sistema:$$\begin{cases}ax+by+cz+d=0 \\
a'x+b'y+c'z+d'=0 \\
a''x+b''y+c''z+d''=0 \\
a'''x+b'''y+c'''z+d'''=0\end{cases}$$
Come visto in precedenza, ci sono diversi casi possibili:$$r\cap s=\begin{cases}\emptyset\begin{cases} complanari\iff \text{ parallele e distinte } \\
sghembe \end{cases} \\
\{P\} \text{ incidenti (ovviamente complanari)}  \\
r=s \text{ coincidenti (anche complanari e parallele)} \end{cases}$$
1) Se le due rette hanno intersezione vuota vuol dire che il sistema è incompatibile e questo vuol dire che $rk(A)\neq rk(A|B)$:
	1) Se $rk(A)=2$ e $rk(A|B)=3$ significa che $V_{1}=V'_{1}$ , quindi sono parallele e visto che non hanno punti in comune sono parallele e distinte.
	2) Se $rk(A)=3$ e $rk(A|B)=4$ significa che $V_{1}\neq V'_{1}$ quindi non sono parallele e non hanno punti in comune, quindi sono sghembe.
2) Se il sistema ha una sola soluzione ovvero se $rk(A)=rk(A|B)=3$, vuol dire che le due rette sono incidenti.
3) Se il sistema ha $\infty^{1}$ soluzioni, ovvero se $rk(A)=rk(A|B)=2$, allora le rette coincidono.

Argomento principale: [[Spazi affini]]
Vedi: [[Equazione cartesiana di  una retta in A3]],[[Mutua posizione di rette e piani]]
#algebra 