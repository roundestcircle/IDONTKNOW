#Stat #Zusammenhänge 

## Kovarianz

Die Kovarianz ist nicht standartisiert und deswegen nicht gut vergleichbar.
Sie wird nur für lineare Zusammenhänge genutzt. Sie ist ein Maß für das gemeinsame Streuen zweier Maßzahlen. 

$$
s_{xy}=\frac{\sum_{i=1}{n} (x_i-\bar{x})\cdot(y_i-\bar{y})}{n}
$$
vgl. [[Streuungsmaße#Varianz]]

Veranschaulichung: Die Mittelwerte bilden ein Kreuz im Streudiagramm. Liegt ein Wert imm unteren linken oder oberen rechten Quadranten steht dementsprechend eine positive Zahl auf dem Bruchstrich (- mal - oder + mal +). Im oberen linken und unteren rechten Quadranten steht stattdessen ein negativer Wert auf dem Bruchstrich (- mal +).

Sind die Werte also hauptsächlich oben rechts und unten links, ist die Kovarianz positiv, und dementsprechend auch der Zusammenhang. Ist die Kovarianz negativ, ist auch der Zusammenhang negativ. Sind die Punkte im Streudiagramm annähernd gleichverteilt, löschen sich positive und negative Zahlen aus, der Wert liegt annähernd bei 0. Die Höhe des Werts bleibt dennoch schlecht interpretierbar, das Vorzeichen ist hier die wichtigste Interpretationsbasis.

## Korrelationskoeffizient/Pearson r

Der Korrelationskoeffizient ist standartisiert, und kann deswegen neben der Richtung auch zur Interpretation der Stärke eines Zusammenhangs genutzt werden.

$$
r_{xy} = \frac{s_xy}{s_x \cdot s_y} = \frac{\text{Kovarianz}}{\text{Produkt der Standardabweichungen}}
$$

Bildlich vorgestellt: Bei perfekter Korrealtion, wenn alle Punkte auf einer Gerade liegen würden, wären die Verhältnisse der Abweichung von $\bar{x}$ und $\bar{y}$ immer gleich, und zwar das der Standardabweichungen. Demnach würden dann, wenn man alle Werte betrachtet, auf und unter dem Bruchstrich dasselbe stehen, der Korrelationskoeffizient wäre damit 1 oder -1.

### Auswertung

Die Auswertung ist mehr oder weniger frei festzulegen, es gibt verschiedene Konventionen, etwa die von Zimmermann-Jaschitz:

- 0-0,4: kein Zusammenhang
- 0,4-0,6: schwacher Zusammenhang
- 0,6-0,8: deutlicher Zusammenhang
- 0,8-1: starker Zusammenhang

### Probleme

Der Korrelationskoeffizient sollte nie als einziges Mittel der Analyse genutzt werden, da er nur für lineare Zusammenhänge brauchbar ist. Berechnet man ihn mit einem Datensatz, der nicht linear korreliert ist, kann es leicht zu Fehlinterpretationen kommen.

Des Weiteren:
1. Der Zusammenhang muss nicht für alle Einheiten gelten
2. Kein Zusammenhang bei r bedeutet nicht, dass kein Zusammenhang besteht
3. Der statistische Zusammenhang bedeutet nicht unbedingt, dass es auch einen inhaltlichen Zusammenahng gibt.
4. Ökologischer Fehlschluss: Der Rückschluss von Aggregaten auf Individuen ist immer problematisch.