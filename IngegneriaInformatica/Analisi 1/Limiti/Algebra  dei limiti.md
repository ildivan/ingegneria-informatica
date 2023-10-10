Siano $f,g:A\to R$ , e siano $x_{0}\in \overline{R}$ un punto di accumulazione di $A$ e $L,M \in \overline{R}$ .
Si pongano:$$L=\lim_{x\to x_{0}}f(x)\text{ e }M=\lim_{x\to x_{0}}g(x)$$
Valgono le seguenti proprietà:
1) $$\lim_{x\to x_{0}}(f(x)+g(x))=\lim_{x\to x_{0}}f(x)+\lim_{x\to x_{0}}g(x)=L+M$$
2) $$\lim_{x\to x_{0}}(f(x)\cdot g(x))=L \cdot M$$
3) $$\lim_{x\to x_{0}}\frac{f(x)}{g(x)}=\frac{L}{M}\text{ se }M\neq 0$$
## NB
Queste proprietà valgono solo in assenza delle seguenti **forme indeterminate**:$$+\infty-\infty,\space 0\cdot\pm \infty,\space \frac{\pm \infty}{\pm \infty} $$
## Caso $M=0$ 
Supponiamo che $L \neq 0$ e $M=0$ , allora valgono le seguenti regole:
1) se $\exists \delta>0: \forall x\in I_{\delta}(x_{0})\cap(A\backslash\{x_{0}\}):g(x)>0$ ,
	allora:$$\lim_{x\to x_{0}}\frac{f(x)}{g(x)}=\begin{cases}+\infty\text{ se } L>0 \\
-\infty se \text{ se } L<0\end{cases}$$
2) se $\exists \delta>0: \forall x\in I_{\delta}(x_{0})\cap(A\backslash\{x_{0}\}):g(x)<0$ ,
	allora:$$\lim_{x\to x_{0}}\frac{f(x)}{g(x)}=\begin{cases}-\infty\text{ se } L>0 \\
+\infty se \text{ se } L<0\end{cases}$$
3) se $g(x)$ cambia segno in ogni intorno di $x_{0}$ allora il limite non esiste, quindi se:$$\forall \delta\exists x_{1},x_{2}\in I_{\delta}(x_{0})\cap(A\backslash\{x_{0}\})\text{ t.c. } g(x_{1})\cdot g(x_{2})<0$$allora:$$\lim_{x\to x_{0}}\frac{f(x)}{g(x)}= \nexists$$
Argomento principale: [[Limiti]]
Vedi: [[Elementi di topologia]]
#analisi1 