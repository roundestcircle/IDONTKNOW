#Stat #Zusammenhänge 

Arithmetisches Mittel und Varianz stehen hier nicht zur Verfügung.

## Rangkorrelationskoeffizient/Spearmans rho

Für den Rangkorrelationskoeffizient werden ale tatsächlichen Werte gelöscht und durch Ränge ersetzt. Der höchste Wert bekommt Rang eins und so weiter. Bei einer perfekten Korrelation müssten die Rangplätze zweier Merkmalswerte eines Merkmalsträgers identisch sein.

$$
\begin{align*}
d_i &= \text{ Rangplatzdifferenz } = rg(x_i)-rg(y_i) \\
\rho &= 1- \frac{6\sum_{i=1}^{n}d_i^2}{n(n^2-1)}
\end{align*}
$$

Aus der Formel ergibt sich, dass der Wert näher an 1 ist, je geringer die Rangplatzdifferenzen und damit je stärker der Zusammenhang ist. 

Achtung: Diese Formel ist nur gültig, wenn alle Rangplätze nur einmal vergeben werden. Sie muss angepasst werden, wenn Rangplätze zum Besipiel bei identischen Ursprungswerten mehrfach vergeben werden.

Spearmans rho ist nicht auf lineare Zusammenhänge beschränkt.