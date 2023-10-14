Sia $g: A \to R^{m}$ e $f: B \to R^{p}$ con $A \subseteq R^{n}$ e $B \subseteq R^{m}: g(A) \subseteq B$ ,
siano $x_{0}\in \overset{\circ}{A}$ e $g(x_{0})\in \overset{\circ}{B}$ .

Se $g$ è differenziabile in $x_{0}$ e $f$ è differenziabile in $g(x_{0})$ allora:$$\begin{cases}
f \circ g \text{ differenziabile in } x_{0} \\
D(f \circ g)(x_{0})=Df(g(x_{0}))Dg(x_{0})
\end{cases}$$
#### DIM
Dalla definizione di derivata:$$f(x_{0}+h) = f(x_{0})+Df(x_{0})h + o(h)$$$$g(x_{0}+h) = g(x_{0})+Dg(x_{0})h + o(h)$$Quindi sostituendo nella definizione di composizione:
$$(f \circ g)(x_{0}+h) = f(g(x_{0}+h))=f(g(x_{0})+Dg(x_{0})h + o(h))$$$$= f(g(x_{0})) + Df(g(x_{0}))(Dg(x_{0})h + o(h)) + o(Dg(x_{0})h + o(h))$$$$(f \circ g)(x_{0}+h)-(f \circ g)(x_{0}) = Df(g(x_{0}))Dg(x_{0})h + Df(g(x_{0}))o(h) +o(Dg(x_{0})h + o(h))$$Semplificando gli o piccolo:$$(f \circ g)(x_{0}+h) - (f \circ g)(x_{0}) = Df(g(x_{0}))Dg(x_{0})h+o(h)$$La tesi è dimostrata.

Argomento principale: [[Derivata completa e differenziabilità]]
Vedi: [[Composizione di funzioni]]
#analisi2 