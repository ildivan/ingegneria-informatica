Sia $E\subseteq R$ , $E\neq \emptyset$ , chiamiamo $a\in R$ :
1) **minorante** di $E$ se $\forall x \in E$ : $a\le x$ 
2) **maggiorante** di $E$ se $\forall x\in E: a\ge x$ 

### Insieme dei maggioranti e minoranti:
$$M(E)= \{ a\in R : \forall x\in E : a\ge x \}$$
$$m(E)= \{ a\in R: \forall x\in E: a\le x \}$$


#### Insiemi limitati:
Sia $E\subseteq R$  e sia $E\neq \emptyset$ , si dice che $E$ è:
1) superiormente limitato se $M(E)\neq \emptyset$
2) inferiormente limitato se $m(e)\neq \emptyset$ 
3) limitato se ammette sia minoranti sia maggioranti


## NB
Sia $E\subseteq R$ con $E\neq\emptyset$ e supponiamo che $E$ sia superiormente/inferiormente limitato. allora $M(E)/m(E)$  ammette minimo/massimo.

Dimostriamo il primo caso:
	Consideriamo $E$, $M(E)\neq \emptyset$
	$\forall x\in E,\forall y\in M(E)$ vale $x\le y$ 
	Quindi per l' [[Assioma di completezza]] : $\exists c\in R : \forall x\in E, \forall y\in M(E): x\le c\le y$ 
	Per definizione $c\in M(E)$ e $c=min(M(E))$ 



Argomento principale: [[Insiemi numerici]]
Vedi: [[Massimi e minimi di un insieme]]
#analisi1 