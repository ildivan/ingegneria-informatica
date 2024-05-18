#### *M*PLI 
$$min\space\space\space\ \sum_{j = 1}^{l}t_{j}\space-\space\sum_{i=1}^{n}x_{i}\sum_{j=1}^{l}w_{ij}$$
- $\forall j \in D \space\space\space \sum_{i=1}^{n}x_{i} w_{ij} \le t_{j}$
- $\forall z \in M \space\space\space \sum_{i=1}^{n}x_{i} q_{iz} \le Q_{z}$
- $\sum_{i=1}^{n}\space (c_{i}- p_{i})x_{i} \ge P$
- $\forall i \in K \space\space\space x_{i} \ge 0$
#### M\*PLI
Vincoli aggiuntivi:
- $\forall i \in K \space\space\space x_{i} \ge u_{i}y_{i}$
- $\forall i \in K \space\space\space x_{i} \le S_{i}y_{i}$
- $\sum_{i = 1}^{n} y_{i} = s$
- $\forall i \in K \space\space\space y_{i} \in \{ 0,1 \}$
**NB** : $S_{i}$ rappresenta un numero maggiore o uguale alla massima produzione possibile di cucine di un certo tipo rispettando tutti gli altri vincoli
##### QUESITO I
Dopo aver risolto con Gurobi il modello MPLI e il suo rilassamento continuo, ho trovato che i valori ottimali della funzione obiettivo erano diversi,ma coerenti con la teoria: il rilassamento continuo fornisce un lower bound, quindi ha un valore della funzione obiettivo inferiore rispetto al modello MPLI. Ho determinato i valori delle variabili di Slack/Surplus ciclando su tutti i vincoli del modello. I vincoli con una variabile di Slack pari a 0 sono quelli attivi nella soluzione. Per verificare la degenerazione della soluzione, ho controllato che nessuna variabile di base avesse valore nullo all'ottimo. Per verificare l'unicità della soluzione, ho controllato che nessuna variabile non di base avesse un coefficiente di costo ridotto pari a zero.
##### QUESITO II
Ho aggiunto $n$ variabili binarie $y_{i}$ per rappresentare se un determinato tipo di cucina è stato scelto, permettendomi di implementare i due vincoli aggiuntivi.
##### QUESITO III
Per determinare il minimo e massimo incremento di P senza cambiare la soluzione ottima, ho utilizzato gli attributi SARHSLow e SARHSup del vincolo sul profitto. Per il valore minimo di $t_{e}$ , ho risolto il modello decrementando $t_{e}$ fino a quando la soluzione ottima è cambiata .