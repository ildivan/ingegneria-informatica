Sia $f:[a,b]\to R$ una funzione continua e sia $G:[a,b]\to R$ una sua primitiva.
Allora:$$\int_{a}^{b}f(x)dx = G(b)-G(a)= [G(x)]_{a}^{b}$$

### DIM:
Sia $F(x)$ un altra primitiva di $f$ , quindi abbiamo che:$$F(x) = \int_{a}^{x}f(t)dt = G(x)+c$$
Per $x=a$ abbiamo che:$$\int_{a}^{a}f(t)dt = F(b)=0 = G(a)+c \implies c = -G(a)$$
Per $x=b$ abbiamo che:$$\int_{a}^{b}f(t)dt = F(b) = G(b)+c = G(b)-G(a)$$
$Q.E.D.$


Argomento principale: [[Integrale di Riemman]]
Vedi: [[Continuità]]
#analisi1 