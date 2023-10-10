Sia $f:(a,b)\to R$ una funzione derivabile. allora valgono le seguenti affermazioni:
1. $f'(x) \ge 0$  $\forall x \in (a,b)$ se, e soltanto se, $f$ è crescente in $(a,b)$ 
2. $f'(x) \le 0$  $\forall x \in (a,b)$ se, e soltanto se, $f$ è decrescente in $(a,b)$
3. Se $f'(x) >0$  $\forall x \in (a,b)$ , allora $f$ è strettamente crescente in $(a,b)$ 
4. Se $f'(c) <0$  $\forall x \in (a,b)$ , allora $f$ è strettamente decrescente in $(a,b)$

### DIM:
Dimostriamo il punto 1. e 3. (2. e 4. si dimostrano nello stesso modo):
1. a) Supponiamo che $f'(x) \ge 0$  $\forall x \in (a,b)$ , dobbiamo dimostrare che $\forall x_{1,}x_{2}\in (a,b)$ vale che:$$x_{1} \le x_{2} \implies f(x_{1}) \le f(x_{2})$$ Applico il [[Teorema di Lagrange]] nell'intervallo $(x_{1},x_{2})$ , il che ci dice che: $$\exists c \in (x_{1},x_{2}) : f'(c) = \frac{f(x_{2})-f(x_{1})}{x_{2}-x_{1}}$$Siccome $f'(c) \ge 0$ , si ha che $f(x_{2}) \ge f(x_{1})$ , quindi $f$ è crescente.                                                                                       b) Supponiamo che $f$ sia crescente, dobbiamo dimostrare che $f'(x) \ge 0$   $\forall x \in (a,b)$ 
	Si ha che:$$f'(x) = \lim_{t \to o}\frac{f(x + t)-f(x)}{t}$$ Se $t>0$ , allora $f(x+t)-f(x) > 0$ perchè f è crescente, invece se $t<0$ , allora $f(x+t)-f(x)<0$ per lo stesso motivo. Quindi in ogni caso abbiamo che:$$\frac{f(x+t)-f(x)}{t}\ge 0$$ e per il [[Teorema del confronto]] :$$f'(x) = \lim_{t \to 0}\frac{f(x+t)-f(x)}{t}> 0$$
3. Dobbiamo dimostrare che $f$ è strettamente crescente in $(a,b)$ sapendo che $\forall x\in (a,b)$  $f'(x)> 0$ , per farlo procediamo applicando Lagrange come nel punto 1.a$$\exists c \in (x_{1},x_{2}) : f'(c) = \frac{f(x_{2})-f(x_{1})}{x_{2}-x_{1}}$$Però avendo che $f'(c)>0$ , ciò implica che $f(x_{2})>f(x_{1})$ e quindi $f$ è strettamente crescente.

$Q.E.D.$

Vedi: [[Monotonia di una funzione]],[[Calcolo Differenziale]]

#analisi1 