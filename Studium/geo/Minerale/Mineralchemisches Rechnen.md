#Min #Basics 

Wie kommt man vom Analyseergebnis zur tatsächlichen Zusammensetzung? Das Analyseergebnis zeigt nur einzelne Oxide, und nicht die volle Zusammensetzung. Für die Berechnung legen wir eine Tabelle an.

1. Spalte 1 zeigt dabei die Masseanteile in g der jeweiligen Oxide, normiert auf 100, also entweder zu verstehen als Masseprozentanteil, oder als Grammzahl in einer Probe, die 100 Gramm wiegt. Diese Spalte ist die Ausgabe des Analysegeräts.
2. In Spalte zwei ermitteln wir nun das Mol-Gewicht der einzelnen Oxide aus den Atomgewichten der Bestandteile.
3. In Spalte 3 teilen wir nun Spalte 1 durch Spalte 2 und erhalten die Molanzahl des jeweiligen Oxids, das in der Probe (normiert auf 100g) enthalten ist. Beispiel: 0.8 Mol SiO2.
4. Nun ermitteln wir die enthaltene Molzahl der Bestandteile des Oxids, indem wir deren Anzahl mit Spalte 3 multiplizieren. Dies machen wir für die Anionen (O) und die Kationen. Beispiel: 0.8 Mol SiO2: 0.8 Mol Si, 1.6 Mol O.
5. Nun normieren wir die beiden Werte auf die gewünschte Formeleinheit/Zusammensetzung. Da für diese etwa bei [[Plagioclase]]n nur die O-Zahl bekannt ist, beginnen wir damit. Dafür summieren wir die Mol-Zahlen des Sauerstoffs auf und teilen dann den erwarteten/gewünschten Wert durch diese Summe. Dadurch erhalten wir einen Normierungsfaktor.
6. Nun normieren wir mit diesem Faktor alle Molzahlen. Die Summe der Mol-Zahlen für O und die verschiedenen Kationenkombinationen müssten nun der Erwartung/einer Formeleinheit entsprechen. 
7. Nun können wir die Formel aufstellen, indem wir einfach die Werte als Faktorzahl klein hinter die Ionen in der Formel schreiben.

Beispiel:

Analyse eine Plagioclas: $$ \ce (Ca, Na, K)[(Al, Si)_4O8] $$

| Oxide | Ma.%  | Mol-Gew. | Molekularquotient | Kationen unn. | Sauerstoff unn. | Sauerstoff n. | Kationen n. |
| ----- | ----- | -------- | ----------------- | ------------- | --------------- | ------------- | ----------- |
| SiO2  | 56.22 | 60.09    | 0.936             | 0.936         | 1.871           | 5.002         | 2.501       |
| Al2O3 | 28.60 | 101.94   | 0.281             | 0.561         | 0.842           | 2.250         | 1.500       |
| CaO   | 10.45 | 56.08    | 0.186             | 0.186         | 0.186           | 0.498         | 0.498       |
| Na2O  | 5.18  | 61.98    | 0.084             | 0.167         | 0.084           | 0.223         | 0.447       |
| K2O   | 0.93  | 94.20    | 0.010             | 0.020         | 0.010           | 0.026         | 0.053       |
| SUMME | 99.96 |          |                   |               | 2.993           | 8.000         | 4.999       |

Anzahl O pro Formeleinheit: 8
Normierungsfaktor: 8 / 2.993 = 2.673

Finale Zusammensetzung, leicht gerundet : $$ \ce Ca_{0.5}Na_{0.45}K_{0.05}[Al_{1.5}Si_{2.5}O8] $$

Mit dieser Formel lässt sich der Stoff nun auch in ternäre Phasendiagramme einordnen ([[Feldspäte Basics#Feldspatdreieck]]).