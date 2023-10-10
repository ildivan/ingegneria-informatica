
La disuguaglianza di Cauchy-Schwarz afferma che:
$$\forall v,u\in V \space |v*u|\le ||v||\cdot||u||$$
## DIM
Osserviamo che se $v=\underline{0}$ , allora:$$v*u = 0 = ||v||$$
e quindi vale che:$$|v*u |= ||v||\cdot||u||=0 \space \forall u\in V $$
Ripetiamo lo stesso procedimento per $u=\underline{0}$ e abbiamo verificato che la disuguaglianza è verificata se almeno uno dei due vettori è nullo.

Supponiamo che $v$ e $u$ siano diversi dal vettore nullo, notiamo che per ogni $a$ vale:$$0\le(\alpha u+v)^{2}= (\alpha u+v)*(\alpha u + v)$$$$= v*(\alpha u+v)+\alpha u*(\alpha u+v)=$$$$\alpha^{2}(u*u) +2\alpha(u*v)+v*v\ge 0$$
Se vale $\forall \alpha$ vuol dire che calcolando il discriminante esso sarà necessariamente negativo o al più nullo:$$\frac{\Delta}{4}=\langle u,v\rangle^{2}-\langle u,u\rangle\langle v,v\rangle=\langle u,v\rangle^{2}-||u||^{2}||v||^{2}\le 0$$$$|\langle u,v\rangle|\le ||u||\cdot||v||$$
$Q.E.D.$

Argomento principale: [[Forme bilineari]]
Vedi: [[Norma indotta da un prodotto scalare]],[[Prodotto scalare]]
#algebra