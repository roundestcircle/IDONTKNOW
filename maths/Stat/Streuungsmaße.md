#Stat #Beschreibend 

Streuungsmaße beschreiben die Heterogenität bzw Variablilität einer Verteilung.

### Spannweite

Die Spannweite ist der Abstand zwischen dem größten und kleinsten Wert, bei klassifzierten Daten der Abstand der Untergenze bzw Obergrenze der letzten besetzten Klassen. Nicht sinnvoll vergleichbar und sehr Extremwertabhängig.

## Mittelwertbasierte Streuungsmaße

### Interquartilsabstand IQR

Der Interquartilsabstand ist der Abstand vom 25%-Quantil bis zum 75%-Quantil ([[Lagemaße#Quantile]]). Dadurch werden Extremwerte eliminiert, doch die Aussagekraft belibt gering.

### Mittlere absolute Abweichung

$\bar{d}=\frac{\sum_{i=1}^{n} |x_i-\bar{x}|}{n}$

Die mittlere absolute Abweichung ist der Durchschnitt der absoluten Abweichungen. Er ist stark extremwertabhängig.

### Varianz

$s^2=\frac{\sum_{i=1}^{n} (x_i-\bar{x})}{n}$

Die Vorzeichen fallen hier nicht durch die Betragsstriche weg, sondern durch die Quadrierung. Die Extrenwerte fallen dadurch jedoch noch stärker ind Gewicht. DIe Interpretation der Varianz ist schwierig, sie dient vor allem als Zwischenschritt zur Standardabweichung.

### Standardabweichung

$s=\sqrt{s^2}$

Die Standardabweichung ist sehr wichtig und wird extrem häufig genutzt. Durch die Wurzel liegt die Varianz wieder auf der Einheitsebene der Merkmalswerte vor.

### Variationskoeffizient

$v=\frac{s}{\bar{x}}$

Der Variationskoeffizient erlaubt Vergleiche zwichen zwei Variablen mit verschiedenen Einheiten. Er beschreibt die Schwankung um $\bar{x}$ als Anteil von $\bar{x}$.

## Formbeschreibung von Häufigkeitsverteilungen

vgl. [[Daten Ordnen#Häufigkeitstabelle|Histogramme]]

Bei der Formbeschreibung wird ein Histogramm immer im Vergleich mit der Standardnormalverteilung betrachtet.

### Basics

1. Glockenförmi
2. multimodal
3. bimodal
4. monomodal
5. flach
6. spitz
7. mit Extremwert
8. rechtsschief (rechte Seite flach, linke steil)
9. linksschief (linke Seite flach, rechte steil)

### Schiefe

Die Schiefe beschreibt die Abweichung von der Symmetrie entlang einer Symmetrieachse parallel zur x-Achse.

$$
a_3 = \frac{\sum_{i=1}^{n} (x_i-\bar{x})^3}{ns^3}
$$

1. symmetrisch: $x_{MD} = \tilde{x} = \bar{x}, a_3 = 0$
2. rechtsschief: $x_{MD} < \tilde{x} < \bar{x}, a_3 > 0$, also der Modus liegt links des Mittelwertes.
3. linksschief: $x_{MD} > \tilde{x} > \bar{x}, a_3 < 0$, also der Modus liegt rechts des Mittelwertes.

### Wölbung

Die Wölbung ist ein Maß für die Steile einer Verteilung.

$$
a_4 = \frac{\sum_{i=1}^{n} (x_i-\bar{x})^4}{ns^4}
$$

1. symmetrisch: $a_4=0$
2. steil: $a_4>0$
3. flach: $a_4<0$

[[Transformationen]]