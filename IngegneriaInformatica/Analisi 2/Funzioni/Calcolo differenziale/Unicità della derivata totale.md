Sia $f: C \to R^{m}$ con $C \subseteq R^{n}$ , sia $x_{0}\in \overset{\circ}{C}$ .
Se $A$ e $B$ sono derivate totali di $f$ in $x_{0}$ , allora:$$A = B$$
#### DIM
Per definizione di derivata totale:$$f(x_{0}+h)-f(x_{0})=Ah +o(h) \text{ per } h \to 0$$$$f(x_{0}+h)-f(x_{0})=Bh +o(h) \text{ per } h \to 0$$
Sottraiamo le due equazioni:$$0 = (A-B)h+o(h)  $$$$(A-B)h=0(h) $$Poniamo $h = te_{i}$ con $t\in R : t \to 0$ dove $e_{i}$ è uno dei vettori della base canonica di $R^{n}$, otteniamo:$$(A-B)te_{i}=o(te_{i}) \text{ per } t \to 0$$
Questo vuol dire che:$$\frac{|(A-B)te_{i}|}{|t|} \to 0 \text{ per } t \to 0$$$$\frac{|t||(A-B)e_{i}|}{|t|}\to 0 \implies|(A-B)e_{i}| \to 0$$
Quindi otteniamo che $(A-B)e_{i} = 0$, ovvero la $i$-esima colonna di $A$ e  di $B$ è uguale. 
Per arbitrarietà di $i$ possiamo affermare che $A=B$.

Argomento principale: [[Derivata completa e differenziabilità]]
Vedi: [[Base di uno spazio vettoriale]],[[o piccolo]]
#analisi2 