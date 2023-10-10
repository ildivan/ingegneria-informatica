Sia $V(K)$ uno spazio vettoriale, la sequenza di vettori $B=(v_{1},\ldots ,v_{n})$ è una base di $V(K)$ se, e solo se:
1) $B$ è una sequenza di generatori di $V$
2) $B$ è una sequenza libera

A differenza delle sequenza di generatori , una base $B$ dello spazio vettoriale $V$ ci dice che ogni vettore di $V$ può essere scritto **univocamente** come combinazione lineare dei vettori di $B$ .

Quindi, se supponiamo che $B$ sia una base di $V$,e abbiamo $\alpha_1,\ldots,\alpha_{n}$ e $\beta_{1},\ldots,\beta_{n}$ tali che:$$w= \alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n} \text{ e anche }w= \beta_{1}v_{1}+\ldots+\beta_{n}v_{n}$$
Allora:$$\alpha_{i}=\beta_{i} \space\forall i = 0,1,\ldots,n$$
#### Coordinate
Sia $B=(v_{1},\ldots,v_{n})$ una base di $V(K)$ e sia $v\in V$.
Scriviamo $v$ nella forma $v=\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}$ 

I valori $\alpha_{1},\ldots,\alpha_{n}$ si chiamano **coordinate di $v$ rispetto alla base $B$** 


## Esistenza della base
Ogni spazio vettoriale contentente un insieme **finito** di generatori ammette base finita.
In caso contrario, la base sarà anch'essa infinita.

### Sottoinsieme massimale
Sia $A\subseteq V$ un sottoinsieme di uno spazio vettoriale $V$ . Diciamo che $B\subseteq A$ è un sottoinsieme massimale in $A$ di vettori linearmente indipendenti se:
1) tutti gli elementi di $B$ sono linearmente indipendenti
2) aggiungendo in $B$ un qualunque altro elemento di $A$ si ottiene un insieme di vettori  linearmente dipendenti.


#### Basi e sottoinsiemi massimali
Se $B$ è una base di $V(K)$ ,allora è un insieme massimale in $V$ di vettori linearmente indipendenti.
Vale il viceversa.
Ovvero, la base è una sequenza minimale di generatori o una sequenza massimale di vettori linearmente indipendenti.  


Argomento principale: [[Spazi vettoriali]]
Vedi: [[Generatori di uno spazio vettoriale]],[[Sequenze libere e legate]]
#algebra 