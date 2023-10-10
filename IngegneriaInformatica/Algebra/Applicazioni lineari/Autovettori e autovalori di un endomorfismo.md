Sia $V(K)$ uno spazio vettoriale finitamente generato e sia $f$ un endomorfismo $f:V\to V$

### Autovettori
Un vettore non nullo $v\in V$ è detto autovettore di $f$ se :$$f(v)=\lambda_{0} v$$
#### Autovalore
Dato un autovettore $v\in V$ di $f$, il valore $\lambda_{0}$ è l'autovalore di $v$, oppure, $v$ è autovettore rispetto all'autovalore $\lambda_{0}$ .

### Autospazio
Prende il nome di autospazio l'insieme dei vettori non nulli che sono autovettori riferiti ad un certo autovalore.$$V_{\lambda_{0}} =\{ v\in V: f(v)=\lambda_{0}v \}$$
**NB:** è un sottospazio.

Per descrivere $V_{\lambda_{0}}$ è sufficiente trovare una sua base, in quanto ogni autovettore rispetto a $\lambda_{0}$ potrà essere scritto come combinazione lineare dei vettori della base.

### Spettro dell'endomorfismo
Si dice spettro l'insieme di tutti gli autovalori di $f$ .
Si indica con $sp(f)$.


## Calcolo degli autovalori,autospazi e autovettori

Sappiamo che per trovare autovalori di $f:V\to V$ dobbiamo trovare $v\in V$ tale che:$$f(v)=\lambda v$$
E quindi:$$f(v)-\lambda v = 0_{V}$$
$\lambda v$ si riscrive mediante l'utilizzo della funzione identica:$$f(v)-\lambda Id(v)=0_V$$
$$(f-\lambda Id)(v)=0_V$$
Sostituiamo $f$ con la matrice associata $A$ , sostituiamo $Id_{V}$ con la matrice identica di ordine $n$ = $dim(V)$ e $v$ con il vettore $x=(x_{1},\ldots,x_{n})^t$  rappresentante  le coordinate di $v$ rispetto alla base $B$.
$$(A-\lambda Id_{n})(x)=0_{R^{n} }$$
Abbiamo ottenuto la forma matriciale di un sistema lineare.
Sappiamo che un sistema lineare omogeneo ammette soluzioni non banali se , e solo se il determinante della matrice associata  è nullo.
Poniamo quindi il determinante di $A-\lambda Id_{n}$ uguale a 0.
$$det(A-\lambda Id_{n})=0$$
Il risultato dipenderà da $\lambda$, più precisamente sarà un polinomio con $\lambda$ come incognita, detto **polinomio caratteristico** e indicato con $p_{A}(\lambda)$.

Le radici del polinomio sono gli autovalori cercati, e la molteplicità di ognuna di  esse si chiama **molteplicità algebrica** e si indica con $m_{a}(\lambda)$.

Per ogni autovalore troviamo il proprio autospazio e ne estraiamo una base.
Prendiamo la definizione di autospazio:$$V_{\lambda_{0}} =\{ v\in V: f(v)=\lambda_{0}v \}$$
Che diventa:$$V_{\lambda_{0}} =\{ v\in V: (f-\lambda Id_{V})(v)=0_{V} \}$$
Si deduce facilmente che $V_{\lambda_{0}}$ non è altro che il nucleo dell'applicazione lineare $(f-\lambda Id_{V})$, quindi dobbiamo trovare una base del nucleo che si traduce nel trovare il sottospazio delle soluzioni di un sistema lineare omogeneo:$$(f-\lambda Id_{n})x=0_{R^{n} }$$
Indichiamo questa base con $B_{sol}$ , ricordiamo che è una sequenza di vettori di coordinate  rispetto alla base $B$ e consentono di costruire una base di $V_{\lambda_{0}}$ una volta che li si moltiplica per i vettori di $B$.

## Proprietà utili
1) Se dei vettori sono autovettori riferiti ognuno ad un autovalore diverso, allora essi sono linearmente indipendenti.
2) Siano $\lambda_{1},\ldots,\lambda_{n}$ degli autovalori , allora l'unione delle basi dei loro autospazi è una sequenza di vettori linearmente indipendenti.

Argomento principale: [[Applicazioni lineari]]
Vedi: [[Algebra/Sistemi lineari/Sistemi Lineari]],[[Algebra/Sistemi lineari/Insieme  delle soluzioni]],[[Determinante di matrice]]
#algebra 