Siano $K$ un campo e $V$ un insieme , si dice che $V$ è uno spazio vettoriale sul [[Campo]] $K$ se sono definite le seguenti operazioni:
1. $\overline{+}:V\times V\to V$    operazione interna binaria su V detta somma.
2. $\circ:K\times V\to V$    prodotto per scalari, operazione esterna.

Queste operazioni devono avere certe caratteristiche:
- $(V,\overline{+})$ è gruppo abeliano.
- Il prodotto per scalari deve avere le seguenti proprietà:
	- $(h\cdot k)\circ \overline{v}$ = $h \circ (k \circ \overline{v})$  $\forall h,k \in K$ e $\forall\space \overline{v}\in V$  
	- $(h+k)\circ \overline{v}$ = $h \circ \overline{v} \overline{+} k\circ \overline{v}$   $\forall h,k \in K$ e $\forall \space\overline{v}\in V$  
	- $h \cdot(\overline{v}\overline{+}\overline{w})$ = $h \circ \overline{v} \overline{+} h\circ \overline{w}$   $\forall h \in K$ e $\forall \space \overline{v},\overline{w}\in V$  
	- $1\circ \overline{v} = \overline{v}$  $\forall \space \overline{v} \in V$ 

Gli elementi $k \in K$ vengono chiamati scalari.
Gli elementi $\overline{v} \in V$ vengono chiamati vettori.

#### Notazione:
Uno spazio vettoriale $V$ su un campo $K$ si indica con $V(K)$ .
Il vettore nullo è indicato con $\underline{0}$ .
L'opposto di un vettore  si indica con $-v$.

#### Esempi di spazi vettoriali:
- [[Spazio vettoriale geometrico]]
- [[Potenze di campi]]
- [[Matrici]]
- [[Funzioni]] del tipo $f:A\to R$ 

#algebra