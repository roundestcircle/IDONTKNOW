#PC 

Gruppe:: Grundlagen

[[Kurvendiskussion in höheren Dimensionen#Partielle Ableitungen]]

## Partielle Ableitung

Am Beispiel [[Ideale Gase#Zustandsgleichung idealer Gase]]

Molare Form: $pV_m=RT$: Enthält drei Variablen, jetzt umstellen und p nach V ableiten, während T, n konstant bleiben. Bie partiellen Ableitungen wird immer nur nach einer Variable abgeleitet.

$(\frac{\partial p}{\partial V})_{V,n}=(\frac{\partial}{\partial V}(\frac{nRT}{V}))_{T,n}$

Das $\frac{\partial}{\partial V}$ ist dabei wie eine Anweisung zu verstehen: Hier bitte nach V ableiten! Es entsteht, da für p die allgemeine Gasgleichung eingesetzt wird. n, R und T sind konstant und werden nicht abgeleitet, also muss nur 1/V abgeleitet werden.

Ergebnis: $(\frac{\partial p}{\partial V})_{V,n}=nRT(-\frac{1}{V^2})$

## Totales Differential

Im totalen Differential werden alle Veränderungsmöglichkeiten, also partiellen Ableitungen zusammengefasst.

$u=f(x_1,...,x_n)$
$du=(\frac{\partial u}{\partial x_1})dx_1+...+(\frac{\partial u}{\partial x_n})dx_n$

