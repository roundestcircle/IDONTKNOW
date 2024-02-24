#Stat #Zusammenhänge 

Arithmetisches Mittel und Varianz stehen hier nicht zur Verfügung.

## Häufigkeitstabelle

In der Häufigkeitstabelle werden die Häufigkeiten aller möglichen Merkmalskombinationen eingetragen. Die Variable X ist dabei, wie bei Streudiagrammen, per Definition die unabhängige Variable.

Beispiel mit zwei Merkmalsausprägungen pro Variable, es können auch mehr sein.

|       | $x_1$ | $x_2$ |     |
| ----- | ----- | ----- | --- |
| $y_1$ | a     | b     | a+b |
| $y_2$ | c     | d     | c+d |
|       | a+c   | b+d   | N   |

Falls ein Zusammenhang besteht, ist eine der Diagonalen häufiger als die andere. Die Berechnung ist jedoch nicht ganz so einfach, weil die Merkmale unterschiedlich oft vorkommen können.

## Prozentsatzdifferenz

Die Prozentsatzdifferenz lässt sich nur auf zwei dichotome Variablen anwenden.

Idee: Falls kein Zusammenhang besteht, müssten a und b jeweils den gleichen Anteil an ihrer Spalte haben (die unabhängige Variable hat keinen Einfluss auf die abhängige).

$$
d\% = 100 \cdot (\frac{a}{a+c} - \frac{b}{b+d})
$$

Dieser Wert nähert sich 0 an, wenn kein Zusammenhang besteht, und ist positiv, wenn a und d überwiegen: Zusammenhang entlang dieser Diagonalen, bzw negativ, wenn b und c überwiegen: Zusammenhang entlang dieser Diagonalen.

## Chi-Quadrat

Chi-Quadrat ist nicht auf dichotome Variablen beschränkt. Chi-Quadrat vergleicht die tatsächlichen Werte in den Zellen mit den erwarteten Werten, wenn kein Zusammenhang bestünde.

Das Ausmaß der Abweichung von diesen Werten beschreibt die Stärke des Zusammenhangs.

$$
\begin{align*}
\chi^2 &= \sum_{i=1}^{k} \frac{(b_i-e_i)^2}{e_i} \\
e_i \text{ (Erwartungswert) } &= \frac{\text{Zeilensumme}\cdot\text{Spaltensumme}}{n}
\end{align*}
$$

Hier fällt direkt eine schwierigkeit auf: der Wert wird immer größer, je mehr Zellen es gibt.

### Kontingenzkoeffizient

Da Chi-Quadrat schwierig zu interpretieren ist, nutzt man für genauere Analysen den Kontingezkoeffizient.

$C = \sqrt{\frac{\chi^2}{\chi^2+n}}$

Dieser Koeffizient ist jedoch immernoch von der Tabellengröße abhängig, deswegen wird er am maximalen C-Wert der Tabelle normalisiert.

$C_{max} = \sqrt{\frac{k-1}{k}}$

k ist hier die Zeilen- oder Spaltenzahl, je anchdem, welche geringer ist.

$C_{korr} = \frac{C}{C_{max}}$

Dieser finale Wert beschreibt, welchen Anteil der maximalen Abweichung von Symmetrie/Gleichverteilung/keinem Zusammenhang die Verteilung erreicht. Er kann dementsprechend Werte zwischen 0 und 1 erreichen, wobei 0 keinen Zusammenhang und 1 eine perfekten Zusammenhang bedeutet.