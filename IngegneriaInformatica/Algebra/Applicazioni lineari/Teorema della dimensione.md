
Sia $f:V\to W$ un applicazione lineare.
Allora:$$dim(V)=dim(Ker(f))+rg(f)$$
### DIM
Sia $(k_{1},\ldots,k_{r})$ una base di $Ker(f)$ , per il [[Teorema del completamento]] possiamo completare la base di $V$ che diventa $(k_{1},\ldots,k_{r},v_{r+1},\ldots,v_{n})$ .
Se $Ker(f)=\{\underline{0}\}$ allora $r= 0$.

Poniamo $w_{j}=f(v_{r+j})\in W$ con $j=1,2,\ldots,s=n-r$ , se dimostriamo che $B=(w_{1},\ldots,w_{s})$ è una base di $Im(f)$ allora abbiamo dimostrato la tesi.

Sappiamo che $Im(f)= Span(f(k_{1}),\ldots,f(k_{r}),f(v_{r+1}),\ldots,f(v_{n}))$  
Notiamo però che $f(k_{i})=\underline{0}$ per $i = 1,\ldots,r$ , quindi sono superflui:$$Im(f)=Span(f(v_{r+1}),\ldots,f(v_{n}))$$
Quindi $B$ è una sequenza di generatori.
Dimostriamo ora che i vettori di $B$ siano linearmente indipendenti.
Quindi supponiamo che:$$\alpha_{1}w_{1}+\ldots+\alpha_{s}w_{s}=\underline{0}$$
Allora dobbiamo dimostrare che tutti gli $\alpha_{i}$ siano nulli.
Passiamo da $w_{j}$ a $f(v_{r+j})$ :$$\underline{0}=\alpha_{1}f(v_{r+1})+\ldots+\alpha_{s}f(v_{r+s})=f(\alpha_{1}v_{r+1}+\ldots+\alpha_{s}v_{r+s})$$
Per cui $\alpha_{1}v_{r+1}+\ldots+\alpha_{s}v_{r+s}\in Ker(f)$ , e ciò vuol dire che si può scrivere come combinazione lineare dei vettori $(k_{1},\ldots,k_{r})$ :$$\alpha_{1}v_{r+1}+\ldots+\alpha_{s}v_{r+s}=\beta_{1}k_{1}+\ldots+\beta_{r}k_{r}$$
$$\beta_{1}k_{1}+\ldots+\beta_{r}k_{r}-\alpha_{1}v_{r+1}-\ldots-\alpha_{s}v_{r+s}=\underline{0}$$
Ma sappiamo che $(k_{1},\ldots,k_{r},v_{r+1},\ldots,v_{r+s=n})$ è la base di $V$ e perciò tutti i coefficienti (in particolare gli $\alpha_{i}$) sono nulli.

La tesi è dimostrata.

## Applicazione alle matrici
Se applichiamo la formula alle matrici , essa diventa:$$dim(K^{n})=dim(Ker(A))+rg(A)$$
$$n=dim(Ker(A))+rg(A)$$
Dove $Ker(A)$ rappresenta lo spazio delle soluzioni del sistema lineare omogeneo associato alla matrice $A$.


Argomento principale: [[Applicazioni lineari]]
Vedi: [[Base di uno spazio vettoriale]],[[Dipendenza Lineare]],[[Combinazione Lineare]],[[Rango dell'applicazione lineare]]
#algebra