Sia $V$ uno spazio vettoriale su $C$ dotato di prodotto hermitiano $\langle ,\rangle$ definito positivo.
Un endomorfismo $f: V\to V$ si dice hermitiano se:$$\forall v,w \in V \space \langle f(v),w \rangle=\langle v,f(w)\rangle$$
# Proprietà

#### Matrice associata ad un endomorfismo hermitiano
Sia $B=\{u_{1},\ldots,u_{n}\}$ una base ortonormale di $V$.
Allora , $f:V\to V$ è un endomorfismo hermitiano se , e solo se la matrice rappresentativa di $f$ rispetto a $B$ è una [[Matrice hermitiana]].

#### DIM
Prendiamo due vettori generici $v,w\in V$ , essi possono essere scritti come combinazione lineare di vettori di $B$ 
$v = a_{1}u_{1}+\ldots+a_{n}u_{n}$
$w= b_{1}u_{1}+\ldots+b_{n}u_{n}$ 

Dobbiamo dimostrare ora che:$$\langle v,w\rangle = a_{1}\overline{b_{1}}+\ldots+a_{n}\overline{b_{n}}$$
Innanzitutto:$$\langle  v,w\rangle = \langle a_{1}u_{1}+\ldots+a_{n}u_{n},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle$$
Per linearità rispetto alla prima componente:
$\langle v,w\rangle =$
$a_{1}\langle u_{1},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle$
$+ a_{2}\langle u_{2},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle$
$\vdots$
$+ a_{n}\langle u_{n},b_{1}u_{1}+\ldots+b_{n}u_{n}\rangle$

Per antilinearità rispetto alla seconda componente:
$\langle v,w\rangle=$
$a_{1}\overline{b_{1}}\langle u_{1},u_{1}\rangle+a_{1}\overline{b_{2}}\langle u_{1},u_{2}\rangle +\ldots+a_{1}\overline{b_{n}}\langle u_{1},u_{n}\rangle$  
$+a_{2}\overline{b_{1}}\langle u_{2},u_{1}\rangle+a_{2}\overline{b_{2}}\langle u_{2},u_{2}\rangle +\ldots+a_{2}\overline{b_{n}}\langle u_{2},u_{n}\rangle$
$\vdots$
$+a_{n}\overline{b_{1}}\langle u_{n},u_{1}\rangle+a_{n}\overline{b_{2}}\langle u_{n},u_{2}\rangle +\ldots+a_{n}\overline{b_{n}}\langle u_{n},u_{n}\rangle$

Per ortogonalità si salvano solo gli $a_{i}\overline{b_{j}}\langle u_{i},u_{j}\rangle$ dove $i=j$ :
$$\langle v,w\rangle = a_{1}\overline{b_{1}}\langle u_{1},u_{1}\rangle +\ldots+a_{n}\overline{b_{n}}\langle u_{n},u_{n}\rangle$$

E infine, per ortonormalità:
$$\langle v,w\rangle= a_{1}\overline{b_{1}}+a_{2}\overline{b_{2}}+\ldots+a_{n}\overline{b_{n}}$$

Siano:$$x=\begin{pmatrix}a_{1} \\ \vdots \\ a_{n}\end{pmatrix}y=\begin{pmatrix}b_{1} \\ \vdots \\ b_{n}\end{pmatrix}$$
Allora scriviamo che:$$\langle  v,w\rangle = \overline{y}^{T}x$$
Ora , se ipotizziamo che l'endomorfismo $f$ è hermitiano, allora:$$\langle f(v),w \rangle=\langle v,f(w)\rangle$$
Sia $A$ la matrice associata ad $f$ , scriviamo $f(v)= Ax$ e $f(v)=Ay$ 

Quindi:
$\langle f(v),w\rangle = \overline{y}^{T}(Ax)= \overline{y}^{T}Ax$
$\langle v,f(w)\rangle = (\overline{Ay})^{T}x =(\overline{y})^{T}(\overline{A})^{T}x$   

Per ipotesi allora:$$\overline{y}^{T}Ax=(\overline{y})^{T}(\overline{A})^{T}x$$
$$A=(\overline{A})^T$$
Quindi la matrice $A$ è una [[Matrice hermitiana]].

Viceversa, se $A$ è hermitiana, e quindi vale che $A=(\overline{A})^T$ , allora:$$\overline{y}^{T}Ax=(\overline{y})^{T}(\overline{A})^{T}x$$
E quindi:$$\langle f(v),w \rangle=\langle v,f(w)\rangle$$
$f$ è un endomorfismo hermitiano.

### NB:
Il teorema ci permette di trovare un legame tra un prodotto hermitiano definito positivo qualsiasi e il prodotto hermitiano canonico:$$\langle v,w\rangle = \langle x,y\rangle_{h}$$
Dove $\langle ,\rangle_{h}$ è il prodotto hermitiano canonico e $x$ e $y$ sono i vettori colonna delle coordinate di $v$ e $w$ rispetto ad una base ortonormale $B$ di $V$.

Inoltre, se $f$ è un endomorfismo hermitiano e $A$ è la sua matrice associata:$$\langle Ax,y\rangle_{h}=\langle x,Ay\rangle_{h}$$
#### Corrispondenza tra endomorfismo hermitiano e matrice hermitiana

Per ogni endomorfismo hermitiano esiste una base ortonormale dello spazio vettoriale tale che la matrice associata all'endomorfismo è hermitiana.

Viceversa, per ogni matrice hermitiana è possibile costruire un endomorfismo hermitiano rispetto al prodotto hermitiano canonico.

### Autovalori di un endomorfismo hermitiano

Gli autovalori di un endomorfismo hermitiano $f$ definito su uno spazio vettoriale $V$ finitamente generato su $C$ , dotato di un prodotto hermitiano definito positivo sono tutti reali.

### DIM:
Fissiamo una base ortonormale $B$ di $V$ , essendo $f$ un endomorfismo hermitiano la sua matrice associata $A$ rispetto a $B$ è hermitiana.
$$A\in Mat_{n,n}(C)$$
Dove $n$ è la dimensione di $V$.

Per il [[Teorema fondamentale dell'algebra]] , il polinomio caratteristico di $A$ possiede almeno una radice $\lambda_{0}$ complessa , che per definizione è autovalore di $A$.

Dobbiamo dimostrare che $\lambda_{0}\in R$ , ovvero dobbiamo dimostrare che $\lambda_{0}= \overline{\lambda_{0}}$

Sia $v_{0}\neq\overline{0}\in C^{n}$ un autovettore rispetto a $\lambda_{0}$ , essendo $A$ hermitiana:$$\langle Av_{0},v_{0}\rangle_{h} = \langle v_{0},Av_{0}\rangle_{h}$$
$$\langle \lambda_{0}v_{0},v_{0}\rangle_{h} = \langle v_{0},\lambda_{0}v_{0}\rangle_{h}$$
$$\lambda_{0}\langle v_{0},v_{0}\rangle_{h} = \overline{\lambda_{0}}\langle v_{0},v_{0}\rangle_{h}$$
Essendo $\langle ,\rangle_{h}$ definito positivo e $v_{0}\neq \underline{0}$ :$$\lambda_{0}= \overline{\lambda_{0}}$$
E quindi:$$\lambda_{0}\in R$$
Dall'arbitrarietà della scelta di $\lambda_{0}$ , segue tale tesi valga per qualunque degli autovalori di $A$.

### Autovettori relativi ad autovalori distinti di un endomorfismo hermitiano

Sia $f:V\to V$ un endomorfismo hermitiano definito su uno spazio vettoriale $V$ finitamente generato su $C$ e dotato di prodotto hermitiano definito  positivo $\langle , \rangle$ .

Due autovettori riferiti ad autovalori distinti sono ortogonali rispetto al prodotto hermitiano considerato.

### DIM
Siano $\lambda_{0}$ e $\lambda_1$ due autovalori di $f$ , consideriamo i seguenti prodotti:$$\langle f(v_{0}),v_{1}\rangle=\langle \lambda v_{0},v_{1}\rangle = \lambda\langle v_{0},v_{1}\rangle$$
$$\langle v_{0},f(v_{1})\rangle = \langle v_{0},\lambda_{1}v_{1}\rangle = \overline{\lambda_{1}}\langle v_{0},v_{1}\rangle$$

Per l'hermitianità di $f$ allora:$$\lambda\langle v_{0},v_{1}\rangle = \overline{\lambda_{1}}\langle v_{0},v_{1}\rangle$$
$$(\lambda_{0}-\overline{\lambda_{1}})\langle v_{0},v_{1}\rangle = 0$$

Per ipotesi $\lambda_{0}\neq \lambda_{1}$ quindi $\langle v_{0},v_{1}\rangle$ deve necessariamente essere nullo, e quindi i due autovettori devono necessariamente essere ortogonali rispetto al prodotto hermitiano considerato.



Argomento principale: [[Forma sesquilineare]]
Vedi: [[Prodotto hermitiano]],[[Norma indotta  da un prodotto hermitiano]],[[Segno di un prodotto hermitiano]],[[Autovettori e autovalori di un endomorfismo]]
#algebra 