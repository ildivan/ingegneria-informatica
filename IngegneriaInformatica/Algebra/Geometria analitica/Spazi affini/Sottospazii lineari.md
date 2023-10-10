Sia $A_{n}(K)$ uno spazio affine.
Si dice **sottospazio lineare** di dimensione $h$ e si indica con $S_{h}=[P;V_{h}(K)]$ , l'insieme dei traslati di un punto fissato $P$,detto origine, mediante i vettori di un sottospazio $V_{h}(K)$ di dimensione $h$,detto spazio di traslazione.

#### Classificazione dei sottospazi lineari
- Si dicono **punti** i sottospazi lineari di dimensione $0$.
- Si dicono **rette** i sottospazi lineari di dimensione $1$.
- Si dicono **piani** i sottospazi lineare di dimensione $2$.
- In generale, considerando uno spazio affine di dimensione $n$, un sottospazio lineare di dimensione $n-1$ si dice **iperpiano**.


### Scelta dell'origine
Ogni punto del sottospazio lineare $S_{h}$ di $A_{n}(K)$ può essere scelto come sua origine.

### DIM:
Sia $S_{h}=[O,V_{h}(K)]$ un sottospazio lineare di $A_{n}(K)$ e sia $P$ un punto qualsiasi di $V_{h}$.
Sia $S'_{h}=[P,V_{h}(K)]$ , dimostriamo che coincide con $S_{h}$.

Sia $R\in S_{h}$  , è quindi ottenuto traslando $O$ con un vettore di $V_{h}$ e quindi $\overrightarrow{OR}\in V_{h}$ , ma anche  $\overrightarrow{PO}\in V_{h}$.

Quindi $\overrightarrow{PO}+\overrightarrow{OR}=\overrightarrow{PR}\in V_{h}$ , il che vuol dire che $R\in S'_{h}$ ovvero $R$ è ottenuto traslando $P$ mediante un vettore di $V_{h}$.
Per la generalità di $R$, possiamo dire che $S_{h}\subseteq S'_{h}$ 
Analogamente si dimostra che $S'_{h}\subseteq S_{h}$ , e che in conclusione $S_{h}=S'_{h}$.


#### Proposizione
Siano $S_{h}$ ed $S_{k}$ due sottospazi lineari di $A_{n}(K)$ , allora:
1) $S_{h}\subseteq S_{k}\iff V_{h}\subseteq V_{k}$ e $S_{h}\cap S_{k}\neq 0$ 
2) Se $S_{h}\cap S_{k}\neq 0\implies S_{h}\cap S_{k}= [P,V_{h}\cap V_{k}]$ dove $P$ è un qualunque punto di $S_{h}\cap S_{k}$


Argomento principale: [[Spazi affini]]
#algebra 