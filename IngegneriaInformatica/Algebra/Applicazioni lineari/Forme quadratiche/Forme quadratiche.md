Sia $V$ uno spazio vettoriale reale e $\varphi: V\times V\to  R$ una forma bilineare simmetrica su $V$ , ossia un prodotto scalare.

Definiamo come forma quadratica associata alla forma bilineare $\varphi$ , l'applicazione da $V\to R$ che ad ogni  vettore $v\in V$ associa $\varphi(v,v)$:$$Q:V\to R$$$$Q(v)=\varphi(v,v)$$
### Forma polare di una forma quadratica

Dalla definizione di forma quadratica segue che ogni prodotto scalare individua un unica forma quadratica.$$Q(v)=\varphi(v,v)$$
Viceversa, dimostriamo che ogni forma quadratica individua un unico prodotto scalare:$$Q(v+w)=\varphi(v+w,v+w)$$$$Q(v+w)=\varphi(v,v+w)+\varphi(w,v+w)$$
$$Q(v+w)=\varphi(v,v)+\varphi(v,w)+\varphi(w,v)+\varphi(w,w)$$$$Q(v+w)=\varphi(v,v)+2\varphi(v,w)+\varphi(w,w)$$
Ora isoliamo $\varphi(v,w)$:$$\varphi(v,w)=\frac{1}{2}(Q(v+w)-Q(v)-Q(w))$$
Data una forma quadratica $Q$ , tramite questa formula detta **formula di polarizzazione** troviamo la **forma polare  $\varphi(v,w)$** associata a $Q$.

#algebra 

