Sia $V$ uno spazio vettoriale su $R$ di dimensione $n$ dotato di prodotto scalare definito positivo.
Sia inoltre $S$ un sottospazio di $V$ e $S^{\perp}$ il suo complemento ortogonale, ricordiamo che:$$V=S\oplus S^{\perp}$$
Quindi ogni  elemento $v\in V$ si scrive come somma di un elemento di $S$ e un elemento di $S^{\perp}$ .$$v=s+s^{\perp}$$
Il vettore $s\in S$ viene indicato come proiezione ortogonale del vettore $v$ sul sottospazio $S$ e si indica con:$$P_{S}(v)$$

## Applicazione proiezione ortogonale, o proiettore

Si definisce l'applicazione lineare chiamata proiettore, l'applicazione che trasforma un vettore $v\in V$ nella sua proiezione ortogonale su un sottospazio $S$:$$P_{S}:V\to V$$
$P_{S}(v)$ è definita  nel seguente modo:$$P_{S}(v)= \langle v,u_{1}\rangle u_{1}+\ldots+\langle v,u_{n}\rangle u_{r}$$
Dove $(u_{1},\ldots,u_{r})$ è una base ortonormale di $S$.

#### DIM
Ricordiamo che $v=s+s^{\perp}$ , quindi $s$ è un elemento del sottospazio $S$ e può essere scritto come combinazione  lineare dei  vettori della base ortonormale $(u_{1},\ldots,u_{r})$ :$$s=a_{1}u_{1}+\ldots+a_{r}u_{r}$$
Dobbiamo dimostrare ora che:$$a_{i}= \langle v,u_{i}\rangle \space \forall i\in \{0,1,\ldots,r\}$$
Sappiamo inoltre che $v-s=s^{\perp}\in S^{\perp}$ , dunque $v-s$ appartiene  al complemento ortogonale  di $S$ e quindi è ortogonale ad ogni vettore della base di $S$:$$\langle v-s,u_{i}\rangle = 0 \space \forall i\in \{1,2,\ldots,r\}$$$$\langle v,u_{i}\rangle-\langle s,u_{i}\rangle = 0 \space \forall i\in \{1,2,\ldots,r\}$$

Sostituiamo ora ad $s$ la combinazione lineare :$$\langle  v,u_{i}\rangle-a_{1}\langle u_{1},u_{i}\rangle -\ldots-a_{r}\langle u_{r},u_{i}\rangle = 0 \space\forall i \in\{1,2,\ldots,r\} $$
Chiaramente essendo $(u_{1},\ldots,u_{r})$ una base ortonormale, i prodotti scalari $\langle u_{j},u_{i}\rangle$ con $j\neq i$ fanno $0$ , l'equazione si semplifica in :$$\langle  v,u_{i}\rangle -a_{i}=0 \space\forall i\in \{1,2,\ldots,r\}$$
Quindi:$$\langle  v,u_{i}\rangle= a_{i}\space \forall i\in \{1,2,\ldots,r\}$$
$Q.E.D.$ 

#### Proprietà proiezione ortogonale
1) $P_{S}(v)$ è un endomorfismo
2) $P_{S}(v)= \underline{0}$ se $v\in S^{\perp}$
3) $P_{S}(v) = v$ se $v\in S$ 
4) $Ker(P_{S}) = S^{\perp}$ , $Im(P_{S})= S$ 
5) $P_{S}(v)$ è idempotente, non cambia il risultato quante  volte la si applica a $v$ .

Le seguenti proprietà valgono sono per $V=R^{n}$ e per il prodotto scalare canonico $\langle , \rangle$
6) La matrice  associata a $P_{S}$ rispetto alla base canonica è:$$AA^{T}$$
7) $P_{S}$ è un endomorfismo diagonalizzabile
8) Gli unici autovalori di $P_{S}$ sono:
	1) $\lambda_{0}= 0$ con molteplicità algebrica e geometrica $n-r$ 
	2) $\lambda_{1}=1$ con molteplicità algebrica e geometrica $r$ 

 

Argomento principale: [[Forme bilineari]]
Vedi:[[Sottospazi vettoriali]],[[Vettori e basi ortonormali]],[[Ortogonalità]],[[Endomorfismi diagonalizzabili]],[[Nucleo e immagine]],[[Prodotto scalare]]
#algebra 