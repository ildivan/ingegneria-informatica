Si dice che l'endomorfismo $f:V\to V$ è simmetrico se , dati $v_{1},v_{2}\in V$ , il prodotto scalare tra l'immagine di $v_{1}$ e $v_{2}$ è uguale al prodotto scalare tra $v_{1}$ e l'immagine di $v_{2}$$$\langle f(v_{1}),v_{2}\rangle = \langle v_{1},f(v_{2})\rangle$$
# Proprietà degli endomorfismi simmetrici

### Matrice associata
Sia $V$ uno spazio vettoriale finitamente generato definito su $R$ , sia $\langle,\rangle$ un prodotto scalare definito positivo su $V$ e $B$ una base ortonormale di $V$ .

La matrice associata a $f:V\to V$ rispetto a $B$ è simmetrica se e solo se $f$ è un endomorfismo simmetrico.

### DIM
Siano $v,w\in V$ , possiamo scriverli come combinazione lineare degli elementi di $B=\{u_{1},\ldots,u_{n}\}$ :
$v= a_{1}u_{1}+\ldots+a_{n}u_{n}$
$w=b_{1}u_{1}+\ldots+b_{n}u_{n}$

Dobbiamo dimostrare ora che:$$\langle v,w\rangle = a_{1}b_{1}+a_{2}b_{2}+\ldots+a_{n}b_{n} $$
Innanzitutto:$$\langle v,w\rangle = \langle a_{1}u_{1}+\ldots+a_{n}u_{n},b_{1}u_{1}+\ldots+b_{n}u_{n} \rangle$$
Per la linearità rispetto alla prima componente:
$\langle v,w\rangle=$
$a_{1}\langle u_{1}, b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle+$
$a_{2}\langle u_{2},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle+$
$\vdots$
$a_{n}\langle u_{n},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle$

Per linearità rispetto alla seconda componente:
$\langle v,w\rangle=$
$a_{1}b_{1}\langle u_{1},u_{1}\rangle+a_{1}b_{2}\langle u_{1},u_{2}\rangle +\ldots+a_{1}b_{n}\langle u_{1},u_{n}\rangle+$
$a_{2}b_{1}\langle u_{2},u_{1}\rangle+a_{2}b_{2}\langle u_{2},u_{2}\rangle +\ldots+a_{2}b_{n}\langle u_{2},u_{n}\rangle+$
$\vdots$
$a_{n}b_{1}\langle u_{n},u_{1}\rangle+a_{n}b_{2}\langle u_{n},u_{2}\rangle +\ldots+a_{n}b_{n}\langle u_{n},u_{n}\rangle$

Chiaramente per l'ortogonalità di $B$ ogni prodotto scalare $\langle u_{i},u_{j}\rangle$ con $i\neq j$ è nullo, quindi:$$\langle v,w\rangle = a_{1}b_{1}\langle u_{1},u_{1}\rangle +a_{2}b_{2}\langle u_{2},u_{2}\rangle+\ldots+a_{n}b_{n}\langle u_{n},u_{n}\rangle$$
E per ortonormalità di $B$ ognuno di questi  prodotti scalari è $= 1$ :$$\langle v,w\rangle=a_{1}b_{1}+\ldots+a_{n}b_{n}$$
Quindi se prendiamo:$$x=\begin{pmatrix}a_{1} \\ \vdots \\ a_{n}\end{pmatrix}y=\begin{pmatrix}b_{1} \\ \vdots \\ b_{n}\end{pmatrix}$$
$x$ e $y$ sono i vettori colonna delle coordinate di $v$ e $w$ rispetto alla base $B$.

Allora:$$\langle v,w\rangle = x^{T}y$$
Chiamiamo $A$ la matrice rappresentativa di $f$ rispetto a $B$. Il prodotto $Ax$ coincide con il vettore  delle coordinate  di $f(v)$ rispetto a $B$ e $Ay$ con il vettore delle coordinate di $f(w)$ rispetto a $B$.

Quindi:
$\langle  f(v),w\rangle =(Ax)^{T}y=x^{T}A^{T}y$
$\langle v,f(w)\rangle=x^{T}(Ay)=x^{T}Ay$  

Essendo  per ipotesi $f$ simmetrico, ciò implica che:$$A = A^{T}$$
Quindi, è simmetrica.

Viceversa, se $A$ è simmetrica allora $A=A^{T}$ , e quindi:$$x^{T}Ay=x^{T}A^{T}y$$
E quindi dimostriamo che $f$ è simmetrico:
$x^{T}Ay=x^{T}(Ay)=\langle v,f(w)\rangle$
$x^{T}A^{T}y=(Ax)^{T}y=\langle f(v),w\rangle$

Quindi $f$ è simmetrico.


##### Corollario
Se $V=R^{n}$ , il prodotto scalare è quello canonico , l'endomorfismo $f:V\to V$ è simmetrico se, e solo se la sua matrice associata rispetto alla base canonica è simmetrica.

##### Osservazioni
1) Se $B$ è una base ortonormale di uno spazio vettoriale $V$ definito su $R$ con un prodotto scalare definito positivo $\langle,\rangle$ definito su $V$ , allora per ogni $v,w\in V$:$$\langle v,w\rangle=x^{T}y$$Con:$$x=\begin{pmatrix}v_{1} \\ \vdots \\ v_{n}\end{pmatrix}y=\begin{pmatrix}w_{1} \\ \vdots \\ w_{n}\end{pmatrix}$$$x$ e $y$ sono i vettori di coordinate di $v$ e $w$ rispetto a $B$.
2) $x^{T}y$ equivale al prodotto scalare canonico $x \cdot y$ , quindi esiste la seguente relazione tra prodotto scalare canonico e un qualsiasi prodotto scalare definito positivo:$$\langle v,w\rangle = x \cdot y$$
3) Se $A$ è la matrice rappresentativa di un endomorfismo simmetrico rispetto ad una base ortonormale, allora:$$(Ax)y=x(Ay)$$
4) Ad ogni endomorfismo simmetrico è possibile associare una matrice simmetrica rispetto ad una base ortonormale dello spazio vettoriale. Viceversa, ad ogni matrice simmetrica è possibile associare un endomorfismo simmetrico rispetto al prodotto scalare canonico:$$f: R^{n}\to R^{n},\space f(v)=Av$$
### Autovalori di un endomorfismo simmetrico
Sia $f:V\to V$ una endomorfismo simmetrico di uno spazio vettoriale $V$ finitamente generato su $R$ e dotato di prodotto scalare definito positivo.
Allora gli autovalori di $f$ sono tutti reali.

### DIM:
Sia $B$ una base ortonormale di $V$ , la matrice $A$ associata a $f$ rispetto a $B$ è simmetrica.

Data $n=dim(V)$ , allora $A\in Mat_{n,n}(R)$ , ed essendo $Mat_{n,n}(R)\subset Mat_{n,n}(C)$ diciamo che:$$A\in Mat_{n,n}(C)$$
Per il [[Teorema fondamentale dell'algebra]] il polinomio caratteristico associato ad $A$ deve contenere almeno una radice $\lambda_{0}$ complessa, che per definizione è anche autovalore della matrice $A$.

Dobbiamo dimostrare che $\lambda_{0}\in R$ , o equivalentemente $\lambda_{0}= \overline{\lambda_{0}}$ .

Sia $v_{0}\in C^{n}$ un autovettore relativo a $\lambda_{0}$ , poichè $A$ è simmetrica allora è anche hermitiana e quindi vale per definizione la seguente proprietà:$$\langle Av_{0},v_{0}\rangle_{h} = \langle v_{0},Av_{0}\rangle_{h}$$
dove $\langle,\rangle_{h}$ è il prodotto hermitiano canonico in $C^{n}$.

Per la definizione di autovettore:$$\langle Av_{0},v_{0}\rangle_{h}=\langle \lambda_{0}v_{0},v_{0}\rangle_{h}$$$$\langle v_{0},Av_{0}\rangle_{h}=\langle v_{0},\lambda_{0}v_{0}\rangle_{h}$$
$$\langle \lambda_{0}v_{0},v_{0}\rangle_{h} = \langle v_{0},\lambda_{0}v_{0}\rangle_{h}$$
Per linearità rispetto al primo termine e antilinearità rispetto al secondo:$$\lambda_{0}\langle v_{0},v_{0}\rangle_{h} = \overline{\lambda_{0}}\langle v_{0},v_{0}\rangle_{h}$$
Il prodotto hermitiano canonico è definito positivo quindi $\lambda_{0}=\overline{\lambda_{0}}\implies \lambda_{0}\in R$ 

Dall'arbitrarietà della scelta di $\lambda_{0}$ , segue che qualsiasi radice del polinomio caratteristico e quindi ogni autovalore di $f$ sia reale.

### Autovettori riferiti ad autovalori distinti
Sia $f:V\to V$ un endomorfismo simmetrico su uno spazio vettoriale $V$ definito su $R$, dotato di un prodotto scalare $\langle ,\rangle$ definito positivo.

Due autovettori di $f$ riferiti a due autovalori distinti sono tra loro ortogonali rispetto al prodotto scalare scelto.

### DIM
Siano $v_{0}$ e $v_{1}$ due autovettori riferiti rispettivamente a $\lambda_{0}$ e $\lambda_{1}$.

Essendo $f$ simmetrico allora:$$\langle  f(v_{0}),v_{1}\rangle = \langle v_{0},f(v_{1})\rangle$$
Per definizione di autovettore:$$\langle \lambda_{0}v_{0},v_{1}\rangle = \langle v_{0},\lambda_{1}v_{1}\rangle$$
Per simmetria rispetto al primo e secondo termine:$$\lambda_{0}\langle v_{0},v_{1}\rangle = \lambda_{1}\langle v_{0},v_{1}\rangle $$
$$(\lambda_{0}-\lambda_{1})\langle  v_{0},v_{1}\rangle = 0$$
Per la legge di annullamento del prodotto, $\lambda_{0}-\lambda_{1}=0$ oppure $\langle v_{0},v_{1}\rangle = 0$ .
D'altro canto $\lambda_{0}$ e $\lambda_{1}$ sono autovalori distinti e questo implica che $\langle v_{0},v_{1}\rangle = 0\implies$ $v_0$ e $v_{1}$ sono ortogonali.


Argomento principale: [[Forme bilineari]]
Vedi: [[Vettori e basi ortonormali]],[[Prodotto scalare]],[[Autovettori e autovalori di un endomorfismo]]
#algebra 