Ad ogni applicazione  lineare possiamo associare due sottoinsiemi importanti:
1) Il nucleo, o kernel $Ker(f)=\{ v\in V | f(v)=\underline{0} \}$ 
2) L'immagine $Im(f)=f(V)=\{ f(v)|v\in V \}\subseteq W$ 

Questi sottoinsiemi , oltre ad essere  sottospazi vettoriali, caratterizzano l'iniettività e la suriettività delle applicazioni lineari.

Infatti:
1) $Ker(f)$ è sottospazio di $V$ 
2) $Im(f)$ è sottospazio di $W$ 
3) $f$ è suriettiva $\iff Im(f)=W$ 
4) $f$ è iniettiva $\iff Ker(f)=\{\underline{0}\}$ 

##### DIM 1)
Dimostriamo le formule di chiusura per il nucleo.

Siano $v_{1},v_{2}\in Ker(f)$ , dimostriamo che $v_{1}+v_{2}\in Ker(f)$
$$f(v_{1}+v_{2})=f(v_{1})+f(v_{2})=\underline{0}+\underline{0}=\underline{0}$$
Sia $v \in Ker(f)$ , dimostriamo che $\lambda v\in Ker(f)$ 
$$f(\lambda v)=\lambda f(v)=\lambda\underline{0}=\underline{0}$$ 

##### DIM 2)
Dimostriamo le formule di chiusura per l'immagine.

Sia $f(v_{1})$  e  $f(v_{2})\in Im(f)$ , dimostriamo che $f(v_{1})+f(v_{2})\in Im(f)$.
$$f(v_{1})+f(v_{2})=f(v_{1}+v_{2})\in Im(f)$$

Sia $f(v)\in Im(f)$ , dimostriamo che $\lambda f(v)\in Im(f)$ .
$$\lambda f(v)=f(\lambda v)\in Im(f)$$

##### DIM 3)
Si dimostra per definizione di suriettività.

##### DIM 4)
Dimostriamo che se $f$ è iniettiva allora $Ker(f)=\{\underline{0}\}$ 
Sia $v\in Ker(f)$ , sappiamo che $f(v)=\underline{0}$ ,quindi possiamo scrivere $f(v)=f(\underline{0})$ , e per la iniettività di $f$ ad immagini uguali corrispondono preimmagini uguali.
Quindi abbiamo $v=\underline{0}$

Dimostriamo ora che se $Ker(f)=\{\underline{0}\}$ allora $f$ è iniettiva. 
Siano $v_{1},v_{2}\in V$ dobbiamo dimostrare che se $f(v_{1})=f(v_{2})$ allora $v_{1}=v_{2}$ .
Scriviamo che $f(v_{1})-f(v_{2})=\underline{0}$ , e quindi:$$f(v_{1}-v_{2})=\underline{0}\implies v_1-v_{2}=\underline{0}\implies v_{1}=v_{2}$$
#### Lemma 
Sia $f:V\to W$ un'applicazione lineare, e sia $(v_{1},\ldots,v_{n})$ una base di $V$ .
Allora:$$Im(f)=Span(f(v_{1}),\ldots,f(v_{n}))$$
#### DIM
Riprendiamo la definizione di $Im(f)$:$$Im(f)=\{ f(v)|v\in V \}$$
Sostituiamo $v= \alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}$ :$$Im(f)=\{ f(\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}): \alpha_{1},\ldots,\alpha_{n}\in R \}$$
$$= \{ \alpha_{1}f(v_{1})+\ldots+\alpha_{n}f(v_{n}): \alpha_{1},\ldots,\alpha_{n}\in R \}=Span(f(v_{1}),\ldots,f(v_{n}))$$



Argomento principale: [[Applicazioni lineari]]
Vedi: [[Sottospazi vettoriali]],[[Funzioni iniettive]],[[Funzioni suriettive]]
#algebra 