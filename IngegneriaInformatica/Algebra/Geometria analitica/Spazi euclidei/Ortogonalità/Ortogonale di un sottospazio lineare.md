Siano $S_{h}=[P;V_{h}]$ e $S_{k}=[Q;V_{k}]$ due sottospazi lineari di $E_{n}(R)$.
Il sottospazio $S_{h}$ si dice **ortogonale** di $S_{k}$ se lo spazio di traslazione di $S_{h}$ è confrontabile con il complemento ortogonale dello spazio di traslazione di $S_{k}$.
Ovvero $S_{h}$ è ortogonale di $S_{k}$ se:$$V_{h}\subseteq V_{k}^{\perp}\text{ oppure }V_{k}^{\perp}\subseteq V_{h}$$

### Casi particolari
1) In $E_{2}(R)$ due rette $r=[P;V_{1}]$ e $s=[P;\overline{V_{1}}]$ sono ortogonali quando $V_{1}=\overline{V_{1}}^{\perp}$ oppure $V_{1}^{\perp}=\overline{V_{1}}$ .
2) In $E_{3}(R)$ due rette $r = [P;V_{1}]$ e $s=[P;\overline{V_{1}}]$ sono ortogonali quando $V_{1}\subseteq \overline{V_{1}}^{\perp}$ oppure $\overline{V_{1}}\subseteq V_{1}^{\perp}$.
3) In $E_{3}(R)$ due piani $\alpha=[P;V_{2}]$ e $\beta=[P;\overline{V_{2}}]$ sono ortogonali quando $\overline{V_{2}}^{\perp}\subseteq V_{2}$ oppure $V_{2}^{\perp}\subseteq \overline{V_{2}}$.
4) In $E_{3}(R)$ un piano $\alpha=[P;V_{2}]$ e una retta $r=[P;V_{1}]$ sono ortogonali quando $V_{2}=V_{1}^{\perp}$ oppure $V_{2}^{\perp}= V_{1}$.


### Rette ortogonali in un punto
In $E_{2}(R)$ dati una retta $r=[P;V_{1}]$ e un punto $H$ esiste una e una sola retta per $H$ ortogonale a $r$.

### Piano e retta ortogonali in un punto
In $E_{3}(R)$ siano $r=[P;V_{1}]$ una retta, $\alpha=[Q;V_{2}]$ un piano e $H$ un punto.
Esiste una e una sola retta passante per $H$ ortogonale ad $\alpha$.
Esiste uno e un solo piano passante  per $H$ ortogonale a $r$.

## Rette e piani ortogonali
In $E_{3}(R)$ siano $r=[P;V_{1}]$ una retta e $\alpha=[Q;V_{2}]$ un piano .
Se $\alpha$ ed $r$ sono ortogonali allora:
1) $r$ è ortogonale ad ogni retta di $\alpha$
2) $\alpha$ è ortogonale ad ogni piano per $r$
Se  $\alpha$ ed $r$ non sono ortogonali allora esiste uno e un solo piano per $r$ ortogonale ad $\alpha$.

### DIM
Se $\alpha$ e $r$ sono ortogonali risulta che $V_{1}=V_{2}^{\perp}$ e $V_{1}^{\perp}=V_{2}$ .

Prendiamo una retta generica $s$ con uno spazio di traslazione $W_{1}$, quest'ultimo allora è contenuto in $V_{2}=V_{1}^{\perp}$.
Di conseguenza $W_{1}\subseteq V_{1}^{\perp}$ e questa è la condizione di ortogonalità tra la retta $r$ e la retta generica $s$
contenuta in $\alpha$.

Prendiamo un piano generico $\beta$ contenente $r$, il suo spazio di traslazione $W_{2}$ contiene $V_{1}=V_{2}^{\perp}$.
Quindi $V_{2}^{\perp}\subseteq W_{2}$ e questa è la condizione di ortogonalità tra $\alpha$ è il piano generico $\beta$.

Se $\alpha$ e $r$ non sono ortogonali, $V_{1}$ e $V_{2}^{\perp}$ sono entrambi sottospazi di dimensione $1$ e sono distinti, quindi la loro somma è diretta e ha dimensione $2$.
Costruiamo $\beta=[P;V_{1}\oplus V_{2}^{\perp}]$ che risulta essere un piano.
Chiaramente $\beta$ contiene la retta $r$ ed è ortogonale a $\alpha$ in quanto lo spazio di traslazione di $\beta$ contiene $V_{2}^{\perp}$ , e per costruzione è l'unico piano che soddisfa queste condizioni.
$Q.E.D.$



Argomento principale: [[Spazi euclidei]]
Vedi: [[Ortogonalità]]
#algebra 