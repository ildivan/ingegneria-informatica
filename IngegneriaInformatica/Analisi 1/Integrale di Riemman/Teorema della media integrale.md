Sia $f:[a,b]\to R$ continua in $[a,b]$ , allora esiste $c\in[a,b]$ tale che $f(c)=\frac{\int_{a}^{b}f(x)dx}{b-a}$ 

Il numero $\alpha = \frac{\int_{a}^{b}f(x)dx}{b-a}$ si chiama media integrale di $f$ in $[a,b]$ 

### DIM:
Per il [[Teorema di Weierstrass]] $f$ ammette min e max assoluto in $[a,b]$. Quindi:$$\exists m,M \in R \text{ t.c. } \forall x \in [a,b] : m \le f(x) \le M$$
E per la proprietà del confronto:$$\int_{a}^{b}mdx \le \int_{a}^{b}f(x)dx \le \int_{a}^{b}Mdx$$
$m$ e $M$ sono funzioni costanti quindi sostituiamo i loro integrali con $m(b-a)$ e $M(b-a)$ :$$m(b-a)\le \int_{a}^{b}f(x)dx \le M(b-a)$$
Dividiamo tutti i membri della catena di disequazioni per $(b-a)$ e otteniamo:$$m \le \frac{\int_{a}^{b}f(x)dx}{b-a} \le M$$
Il [[Teorema dei valori intermedi]] implica che dato $\alpha\in [m,M]$ allora esiste $c\in[a,b]$ tale che $f(c)=\alpha$

$Q.E.D$

Argomento principale: [[Integrale di Riemman]]
Vedi: [[Proprietà dell'integrale di Riemman]]
#analisi1 