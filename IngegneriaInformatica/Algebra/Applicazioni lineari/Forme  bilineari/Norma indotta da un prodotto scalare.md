Sia $V$ uno spazio vettoriale con un prodotto scalare definito positivo $\langle , \rangle:V\times V\to R$ .
Si dice norma la funzione $|| \cdot||:V\to R^{+}\cup \{0\}$ che associa ad ogni vettore in cui è definito il prodotto scalare un numero reale positivo o nullo (solo per il vettore nullo). 
Viene definitto come:$$||v||:=\sqrt{\langle v,v\rangle} \space\forall v\in V$$
#### Significato geometrico
Rappresenta nel caso del prodotto scalare standard la "lunghezza" del vettore.

## Proprietà
- $||v|| = 0 \iff v= \underline{0}$
- $||v||>0 \iff v\neq 0$
- $||\lambda v||=|\lambda|\cdot ||v||$
- [[Disuguaglianza di Cauchy-Schwarz]]
- Disuguaglianza triangolare:
	- $||v+w||\le ||v||+||w||$


##### DIM 1/2)
Per ipotesi il prodotto scalare è definito positivo e quindi il prodotto scalare di un vettore per se stesso è 0 se , e solo se il vettore è nullo.
Quindi per la definizione di norma:$$||v||=\sqrt{\langle v,v\rangle}= 0 \iff v= \underline{0}$$
E per ogni altro vettore il prodotto scalare è positivo,quindi:$$||v|| =\sqrt{\langle v,v\rangle}>0 \forall v\neq \underline{0} \in V$$
##### DIM 3)
Dimostriamo che:$$||\lambda v||=|\lambda| \cdot||v||$$
Per la definizione di norma:$$||\lambda v|| = \sqrt{\langle \lambda v,\lambda v \rangle}$$
E per le proprietà del prodotto  scalare:$$= \sqrt{\lambda^{2}\langle v,v\rangle }=|\lambda|\sqrt{\langle v,v\rangle}=|\lambda|\cdot||v||$$
##### DIM 5)
Dimostriamo che:$$\forall v,w\in V \space ||v+w||\le ||v||+||w||$$
Notiamo che:$$||v+w||^{2}=\langle v+w,v+w\rangle$$
$$= \langle v,v+w\rangle + \langle w,v+w\rangle$$
$$= \langle v,v\rangle + \langle v,w\rangle + \langle  w,v\rangle + \langle w,w\rangle$$
$$= \langle v,v\rangle +2\langle v,w\rangle +\langle w,w\rangle$$
Per definizione di norma:$$= ||v||^{2} +2\langle v,w\rangle+||w||^{2}$$
Dalla disuguaglianza di Cauchy-Schwarz abbiamo che:$$|\langle v,v \rangle|\le ||v||\cdot||w||$$
Quindi:$$||v||^{2}+2\langle v,w\rangle +||w||^{2}\le ||v||^{2}+2||v||\cdot||w||+||w||^{2}$$
Notiamo che:
$$||v+w||^{2}=||v||^{2}+2\langle v,w\rangle +||w||^{2}$$
$$||v||^{2}+2||v||\cdot||w||+||w||^{2}=(||v||+||w||)^2$$
Sostituiamo:$$||v+w||^{2} \le (||v||+||w||)^2$$
Estraiamo la radice:$$||v+w||\le ||v||+||w||$$
La proprietà è dimostrata.


Argomento principale: [[Forme bilineari]]
Vedi: [[Segno del prodotto scalare]]
#algebra 