Sia $B=(v_{1},\ldots,v_{n})$ una base di $V(K)$ e sia $C=(w_{1},\ldots,w_{p})$ con $p\le n$ vettori linearmente indipendenti.
Allora esistono $n-p$ vettori di $B$ che aggiunti a $C$ formano una base di $V$.

### DIM

Notiamo che $w_{1}=\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}$ 
I coefficienti $\alpha_{i}$ non possono essere tutti nulli perchè avremmo $w_{1}= \underline{0}$ e questo  va contro l'ipotesi che i vettori di $C$ siano linearmente indipendenti.
Quindi scambiando $w_{1}$ e $v_{1}$ e dividendo per $\alpha_{1}$ otteniamo:$$v_{1}=\frac{1}{\alpha_{1}}w_{1}-\frac{\alpha_{2} }{\alpha_{1}}v_{2}-\ldots-\frac{\alpha_{n}}{\alpha_{1}}v_{n}\in Span(w_{1},v_{2},\ldots,v_{n}) $$
Sappiamo che $(w_{1},v_{2},\ldots,v_{n})$ è una sequenza di generatori di $V(K)$ perchè $v_{1}$ è un vettore generico di $V$ e può essere scritto come c.l. degli elementi di $(w_{1},v_{2},\ldots,v_{n})$ 
Essendo  che ogni base di $V(K)$ ha lo stesso numero di elementi , $(w_{1},v_{2},\ldots,v_{n})$ è una base di $V(K)$ .
Ripeto la sequenza altre $n-(p-1)$ volte partendo dalla sequenza $(w_{1},v_{2},\ldots,v_{n})$ e prendendo sostituendo ogni  volta $v_{i}$ con $w_{i}$ per ogni $i=1,\ldots,p$ .
Alla  fine avremo la sequenza $(w_{1},\ldots,w_{p},v_{p+1},\ldots,v_{n})$
E la tesi è dimostrata.


Argomento principale: [[Spazi vettoriali]]
Vedi: [[Dipendenza Lineare]],[[Base di uno spazio vettoriale]],[[Generatori di uno spazio vettoriale]]
#algebra 