
Siano $V,W$ due spazi vettoriali, sia $v_{1},\ldots,v_{n}$ una base di $V$ e siano $w_{1},\ldots,w_{n}$ vettori qualunque di $W$.
Allora esiste una **UNICA** applicazione lineare $f:V\to W$ tale che:$$f(v_{i})=w_{i}$$ e questa applicazione lineare è definita da:$$f(\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n})=\alpha_{1}w_{1}+\ldots+\alpha_{n}w_{n}$$
### DIM
Verifichiamo per prima cosa che $f$ per come la abbiamo definita sia lineare.
Siano $v=\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}$ e $v'=\alpha'_{1}v_{1}+\ldots+\alpha_{n}'v_{n}$ .
Allora $v+v'=(\alpha_{1}+\alpha_{1}')v_{1}+\ldots+(\alpha_{n}+\alpha_{n}')v_{n}$ e quindi:$$f(v+v')=(\alpha_{1}+\alpha_{1}')w_{1}+\ldots+(\alpha_{n}+\alpha_{n}')w_{n}$$
$$= \alpha_{1}w_{1}+\ldots+\alpha_{n}w_{n}+\alpha'_{1}w_{1}+\ldots+\alpha_{n}'w_{n}$$
$$=f(v)+f(v')$$

Invece:$$f(\lambda v)= \lambda \alpha_{1}w_{1}+\ldots+\lambda \alpha_{n}w_{n}$$
$$=\lambda(\alpha_{1}w_{1}+\ldots+\alpha_{n}w_{n})=\lambda f(v)$$

Dimostriamo adesso che $f$ è unica, quindi se esistesse un altra applicazione lineare $S:V\to W$ tale che $S(v_{i})=w_{i}$ allora sarebbe equivalente a $f$ .
Abbiamo quindi:$$S(v)=S(\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n})=\alpha_{1}S(v_{1})+\ldots+\alpha_{n}S(v_{n})$$
$$= \alpha_{1}w_{1}+\ldots+\alpha_{n}w_{n}=f(v)$$
Quindi $S(v)=f(v)$ per ogni vettore $v\in V$ , e si scrive $$S\equiv f$$

Argomento principale: [[Applicazioni lineari]]
#algebra 