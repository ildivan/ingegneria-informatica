
## Spazio vettoriale delle  applicazioni lineari
Siano $V$ e $W$ due spazi vettoriali , l'insieme di tutte le applicazioni lineari del tipo $f:V\to W$ è spazio vettoriale.

Definiamo le operazioni $f+g:V\to W$ e $\lambda f:V\to W$ 
tali che $(f+g)(v)=f(v)+g(v)$ e $(\lambda f)(v)=\lambda f(v)$  

## Composizione 
Siano $f:V\to W$ e $g:W\to U$ , si chiama composizione l'applicazione lineare $g\circ f:V\to U$ tale che:$$(g\circ f)(v)=g(f(v)) \forall v\in V$$
**nb**: in generale la composizione non è commutativa.

## Inversa e invertibilità
Diciamo che un applicazione lineare $f:V\to W$ è invertibile se esiste un applicazione lineare $f^{-1}:W\to V$ , chiamata inversa di $f$,tale che:$$(f\circ g)=Id_{W}\text{ e } (g\circ f)=Id_{W}$$
##### Unicità dell'inversa
Se esiste un inversa di $f$ , allora essa è unica.

##### Requisiti  diinvertibilità
Un applicazione lineare è invertibile se, e solo se è biiettiva, ovvero  se è sia iniettiva sia suriettiva.

## Isomorfismo
Due spazi vettoriali $V$ e $W$ sono isomorfi se esiste un isomorfismo tra i due, ovvero un applicazione lineare invertibile tra $V$ e W. $$f:V\to W$$  $$f^{-1}:W\to V$$ **esempio**: matrici


Argomento principale: [[Applicazioni lineari]]
Vedi: [[Funzioni biiettive]],[[Funzione inversa]],[[Composizione di funzioni]]
#algebra 