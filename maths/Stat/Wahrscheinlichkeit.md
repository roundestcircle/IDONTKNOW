#Stat #Schließend 

vgl. [[Kombinatorik]]

### Zufallsexperimente

In Zufallsexperimenten bilden alle Möglichen Ergebnisse den Ereignisraum. Jedes Ereignis hat eine Auftretenswahrscheinlichkeit zwischen 0 und 1, alle Wahrscheinlichkeiten zusammen ergeben 1. Die Ergebnisse eines Zufallsexperimentes (wie zum Beispiel dem Ziehen einer [[Stichprobe]]) nennt man Zufallsvariablen.
Alle Zufallsvariablen lassen sich als [[Daten Ordnen#Häufigkeitstabelle|Histogramm]] oder als kumulative Verteilungsfunktionen darstellen.

#### Diskrete Zufallsvariablen

Bei diskreten Zufallsvariablen ist die Wahrscheinlichkeit eines Ereignisses einfach die Zahl der günstigen/gewünschten  Ergebnisse geteilt durch die Zahl der möglichen Ergebnisse. Beispiel: Würfeln: Ein günstiges Ereignis, 6 mögliche: Wahrscheinlichkeit 1/6.

#### stetige Zufallsvariablen

Der Ereignisraum ist ein Intervall, die Zahl der möglichen Fälle ist unendlich. Dementsprechend tendiert die Wahrscheinlichkeit eines einzelnen Falles gegen 0. Wahrscheinlichkeiten lassen sich somit nur für bestimmte Subintervalle angeben, etwa: zwischen 1 und 4 liegen 80% der Ergebnisse, oder 50% der Ergbenisse liegen unter 3 etc. Die Darstellung einer solchen Variable graphisch nennt man auch Dichtefunktion.

### Die Standardnormalverteilung

Die Normalverteilung ist die wichtigste Dichtefunktion der schließenden Statistik. Es gibt unendlich viele Normalverteilungen, die durch [[Lagemaße|Mittelwert]] und [[Streuungsmaße#Standardabweichung|Standardabweichung]] definiert sind. 
Bei der Standardnormalverteilung liegt der Mittelwert bei 0, die Standardabweichung bei 1. Durch [[Transformationen#Z-Transformation/Standardisierung]] aus jeder Normalverteilung entstehen. Sehr viele Variablen verteilen sich annähernd normalverteilt, zum Beispiel und für uns besonders wichtig: Die Mittelwerte von Zufallstichproben.

#### Häufigkeiten für Subintervalle

- -1 bis +1 s: 68,2% der Werte
- -2 bis +2 s: 95,5% der Werte
- -1 bis +1 s: 99,7% der Werte

#### Prüfen auf Normalverteilung

Da viele Berechnungsverfahren von Normalverteilung ausgehen, müssen die Variablen oft auf Normalverteilung überprüft werden, bevor Berechnungen stattfinden.

1. Normalverteilung über Histogramm legen und visuell vergleichen
2. QQ-Diagramm: Die Verteilungen zweier Variablen werden auf X- und Y-Achse abgetragen (vgl [[Einführung Zusammenhangsanalyse#Streudiagramme]]). Wenn sie eine Gerade bilden, haben beide Merkmale die gleiche Verteilung. Dementsprechend ersetzt man die eine Variable durch eine theoretische Normalverteilung und überprüft, ob sich eine Gerade bildet.
3. Shapiro-Wilk-Test. Komplexer, wenn $p\geq0.05$, dann Normalverteilung angenommen.

### Rechenbeispiel Unterschreitungswahrscheinlichkeit

Ist die Deichhöhe ausreichend oder nicht? Sie soll in 95% der Jahre über dem Jahreshöchststand des Wassers liegen.
Der Jahreshöchststand ist 4,4m, Die Standardabweichung 1,1m.

In wie viel Prozent der Fälle reicht der Deich/Unterschreitungswahrscheinlichkeit:
pnorm(6, 4.4, 1.1)
92.7

Wie Hoch müsste der Deich sein:
qnorm(0.95, 4.4, 1.1)
6,21

vgl [[R for basic stats]]