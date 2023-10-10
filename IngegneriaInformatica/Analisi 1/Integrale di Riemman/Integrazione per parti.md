Sia $I\subseteq R$ e siano $f,g\in C^{1}(I)$, per ogni intervallo $[a,b]\in I$ , vale:$$\int_{a}^{b}f'(x)g(x)dx=[f(x)g(x)]^{b}_{a}-\int_{a}^{b}f(x)g'(x)dx$$
### DIM:
Per la formula  di Leibniz, vale che:$$(f \cdot g)'=f' \cdot g + f \cdot g'$$
quindi $f \cdot g$ è una primitiva di $f' \cdot g + f \cdot g'$ 

Quindi:$$\int_{a}^{b}\bigg(f'(x)g(x)+f(x)g'(x)\bigg)dx = [f(x)g(x)]^{b}_{a}$$
Per la linearità dell'integrale:$$\int_{a}^{b}f'(x)g(x)dx + \int_{a}^{b}f(x)g'(x)dx = [f(x)g(x)]^{b}_{a}$$
E spostando l'integrale confermiamo la tesi:$$\int_{a}^{b}f'(x)g(x)dx = [f(x)g(x)]^{b}_{a}-\int_{a}^{b}f(x)g'(x)dx$$
$Q.E.D.$


Argomento principale: [[Integrale di Riemman]]
Vedi:
#analisi1 