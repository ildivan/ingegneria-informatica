## Teorema di ortogonalizzazione di Gram-Schmidt
Sia $V$ uno spazio vettoriale su $R$ e siano $v_{1},\ldots,v_{n}\in V$ vettori linearmente indipendenti.
Sia definito un prodotto scalare su $V$:$$\langle ,\rangle :V\times  V\to R$$
Allora esiste una sequenza $(w_{1},\ldots,w_{n})\in V$ tali che:
1) $\langle w_{i},w_{j}\rangle = 0 \space \forall i\neq j$ 
2) $Span(v_{1},\ldots,v_{n})=Span(w_{1},\ldots,w_{n})$

### DIM
Siano:
- $w_{1}:=v_{1}$
- $w_{2}:= v_{2}-\frac{\langle v_{2},w_{1}\rangle}{\langle w_{1},w_{1}\rangle}w_{1}$ 
Notiamo che  $\langle w_{1},w_{1}\rangle \neq 0$ per come è stato definito $w_{1}$ e per l'indipendenza lineare dei vettori $v_{1},\ldots,v_{n}$ .

Verifichiamo che $w_{1}$ e $w_{2}$ siano ortogonali fra loro:
$$\langle w_{1},w_{2}\rangle = \langle w_{1},v_{2}-\frac{\langle v_{2},w_{1}\rangle}{\langle w_{1},w_{1} \rangle}w_{1}\rangle$$
Per la linearità del prodotto scalare:
$$=\langle w_{1},v_{2}\rangle -\frac{\langle v_{2},w_{1}\rangle}{\langle w_{1},w_{1} \rangle}\langle w_{1},w_{1}\rangle$$
$$= \langle w_{1},v_{2}\rangle -\langle v_{2}-w_{1}\rangle = 0$$
Quindi $w_{1}$ e $w_{2}$ sono ortogonali tra loro.
Inoltre , essendo $w_{1},w_{2}$ definiti come combinazioni lineari di $v_{1},v_{2}$ allora:$$Span(v_{1},v_{2})=Span(w_{1},w_{2})$$
Poniamo:$$w_{3}:= v_{3}-\frac{\langle v_{3},w_{1}\rangle}{\langle w_{1},w_{1}\rangle}w_{1}-\frac{\langle v_{3}, w_{2}\rangle}{\langle w_{2},w_{2} \rangle}w_{2}$$
Allo stesso modo si dimostra che:$$\langle w_{3},w_{2} \rangle=\langle w_{3},w_{1} \rangle= 0$$
Quindi $w_{1},w_{2},w_{3}$ sono ortogonali tra di loro e inoltre:$$Span(v_{1},v_{2},v_{3})=Span(w_{1},w_{2},w_{3})$$

Reiterando la procedura arriviamo a definire il vettore:$$w_{n}= v_{n}-\frac{\langle v_{n},w_{1}\rangle}{\langle w_{1},w_{1}\rangle}w_{1}-\frac{\langle v_{n}, w_{2}\rangle}{\langle w_{2},w_{2} \rangle}w_{2}-\ldots-\frac{\langle v_{n},w_{n-1}\rangle}{\langle w_{n-1},w_{n-1} \rangle}w_{n-1}$$
tale  che $w_{n}$ è ortogonale con tutti gli altri $w_{i}$ e tale che:$$Span(w_{1},\ldots,w_{n})=Span(v_{1},\ldots,w_{n})$$
Il teorema è dimostrato.

### Corollario
Sia $V$ uno spazio vettoriale, $B_V=(v_{1},\ldots,v_{n})$ una sua base e $\langle,\rangle:V\times V \to R$ un prodotto scalare definito positivo.

Per il teorema di Gram-Schmidt esiste una sequenza $(w_{1},\ldots,w_{n})$ tale che i suoi vettori sono ortogonali fra di loro ed è una base di $V$ .

Quindi $(w_{1},\ldots,w_{n})$ è una base ortogonale di $V$.

## NB:
Se trovi una base ortogonale e dividi ogni suo vettore per la propria norma, ottieni una base ortonormale.

Argomento principale: [[Forme bilineari]]
Vedi: [[Ortogonalità]],[[Prodotto scalare]],[[Copertura lineare]]
#algebra 