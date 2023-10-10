Sia $f:[a,b]\to R$ una funzione **continua**,
Sia $F:[a,b]\to R$ data da:$$F(x)=\int_{a}^{x}f(t)dt$$
Allora F è derivabile e la sua derivata coincide con: $$F'(x) = f(x) \space\forall x\in (a,b)$$
### DIM:

Calcoliamo la derivata di $F(x)$:$$F'(x)=\lim_{h\to0}\frac{F(x+h)-F(x)}{h}$$
In particolare $F(x+h)-F(x)$ può essere scritto come:$$\int_{a}^{x+h}f(t)dt-\int_{a}^{x}f(t)dt$$
Per la proprietà di addività:$$\int_{a}^{x}f(t)dt+\int_{x}^{x+h}f(t)dt-\int_{a}^{x}f(t)dt$$
E quindi:$$F(x+h)-F(x)=\int_{x}^{x+h}f(t)dt$$
se $h>0$ , per il [[Teorema della media integrale]] : $$\exists c_{n}\in [x,x+h] :   f(c_{n}) = \frac{\int_{x}^{x+h}f(t)dt}{h} \implies \int_{x}^{x+h}f(t)dt = hf(c_{n})$$
se $h<0$, allora:$$\exists c_{n} \in [x,x+h] : \int_{x}^{x+h}f(t)dt=-\int_{x+h}^{x}f(t)dt = -(-h)f(c_{n})$$
Torniamo al limite iniziale e dividiamolo nei suoi limiti unilaterali:$$\lim_{h\to 0^{+}}\frac{F(x+h)-F(x)}{h}=\lim_{h\to 0_{+}}\frac{hf(c_{n})}{h} = \lim_{h\to 0^{+} }f(c_{n}) = f(x)$$
Il limite tende a $f(x)$ perchè $h\to 0^{+}$ implica che $f(c_{n})=f(x)$ con $c_{n}\in[x,x+h]$ 

Allo stesso modo verifichiamo il limite:$$\lim_{h\to 0^{-} }\frac{F(x+h)-F(x)}{h}= f(x)$$
Quindi $F'(x) = f(x)$.

$Q.E.D.$

Argomento principale: [[Integrale di Riemman]]
Vedi: [[Limiti unilaterali]],[[Proprietà dell'integrale di Riemman]],[[Continuità]]
#analisi1 