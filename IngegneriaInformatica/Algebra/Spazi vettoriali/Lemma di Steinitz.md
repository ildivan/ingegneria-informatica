
Sia $V(K)$ uno spazio vettoriale finitamente generato, sia $B=(v_{1},\ldots,v_{n})$ una sequenza  di generatori di $V$ e sia $A= (u_{1},\ldots,u_{m})$ un sistema  libero di vettori  di $V$ .
Allora $m\le n$ .

## DIM

Supponiamo per assurdo che $m> n$ 
Dato che $B$ genera $V$ , il vettore $u_{1}$ è linearmente dipendente da $B$ e quindi può essere  scritto come:$$u_{1}=\alpha_{1}v_{1}+\ldots+\alpha_{n}v_{n}$$
Non tutti i  coefficienti $\alpha_{i}$ possono essere nulli perchè avremmo $u_{1}=\underline{0}$ e va contro l'ipotesi che $A$ è una sequenza libera.
Non è restrittivo supporre che $\alpha_{1}\neq 0$ e quindi:$$(*)\space v_{1}=\frac{1}{\alpha_{1}}u_{1}-\frac{\alpha_{2} }{\alpha_{1}}v_{2}-\ldots-\frac{\alpha_{n}}{\alpha_{1}}v_{n}\space  $$
Anche $B'=(u_{1},v_{2},\ldots,v_{n})$ genera $V$.

Prendiamo ora in considerazione $u_{2}$ , esso dipende linearmente da $B'$ cioè:$$u_{2}=k_{1}u_{1}+k_{2}v_{2}+\ldots+k_{n}v_{n}$$
Supponiamo che $k_{2}\neq 0$ visto che i $k_{i}$ non possono essere tutti nulli, allora possiamo scrivere $v_{2}$ come combinazione lineare dei vettori $B''=(u_{1},u_{2},v_{3},\ldots,v_{n})$ .
Quindi anche $B''$ è una sequenza di generatori di $V$.
Ripetiamo la procedura fino ad ottenere la sequenza $C=(u_{1},\ldots,u_{n})$ che sappiamo che genera $V$, questo va contro l'ipotesi che $A$ sia libera in quanto i vettori $(u_{n+1},\ldots,u_{m})$ sono linearmente dipendenti da $C$. 
La tesi è dimostrata.

Argomento principale:  [[Spazi vettoriali]]
Vedi: [[Sequenze libere e legate]],[[Generatori di uno spazio vettoriale]]
#algebra 