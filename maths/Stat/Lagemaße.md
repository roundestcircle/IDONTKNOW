#Stat #Beschreibend

Lagemaße beschreiben das typische einer Verteilung, zentrale, mittlere oder Häufigste Werte.

Die unterschiedlichen Lagemaße können sehr verschiedene Geschichten erzählen, die alle legitim sind, sich in Nachrichten oä, in denen alles als Mittel oder Durchschnitt bezeichnet wird jedoch schwer unterscheidbar sind. Dazu muss beachtet werden, dass mit Begriffen wie der Mitte oft "Norm" oder "Normalität" assoziiert wird, was falsch und gefährlich ist.

## Arithmetisches Mittel

Das arithmetische Mittel heißt umgengssprachlich auch Durchschnitt.
Es lässt sich nur bei metrischen Daten anwenden und ist Extremwertanfällig.

$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n} = \frac{x_1+x_2+...+x_n}{n}$

## Median

Der Median ist der Merkmalswert, der genau in der Mitte der Verteilung liegt. Der Median lässt sich bei ordinal und metrisch skalierten Daten anwenden. Er ist nicht Extremwertanfällig. Am Median überschreitet die kumulierte Häufigkeit 50%.

Ungerade Wertanzahl: Merkmalswert genau in der Mitte

$\tilde{x}=x_{\frac{n+1}{2}}$

Gerade Wertanzahl: Arithmetisches Mittel der zwei mittleren Werte

$\tilde{x}=\frac{x_{\frac{n}{2}}+x_{\frac{n}{2}+1}}{2}$

## Modus

$x_{MD}$

Der Modus ist der häufigste Wert einer Verteilung. Er existiert auf allen Skalenniveaus, ist aber nicht immer eindeutig und enthält keine Verteilungsinformationen. 

## Geometrisches Mittel

Das geometrsiceh Mittel wird für Änderungs- oder Wachstumsraten genutzt. Es ist keine Summe, sondern ein Produkt. Es geht nicht um absolute Abstände der Werte, sondern um Abstände um einen Faktor x.

## Mittelwerte klassierter Daten

Für klassierte Daten müssen bestimmte Annahmen getroffen werden:
Innerhalb der Klassen werden die Daten als gleichverteilt betrachtet. Dann wird die mittlere Ausprägung (Arithmetisches Mittel aus Ober- und Untergrenze) für die weiteren Berechnungen genutzt.

### Klassifiziertes Arithmetisches Mittel

Gleich wie das arithmetische Mittel aber mit Klassenmitteln statt Einzelwerten.

$h_j=\text{ Häufigkeit der j. Klasse}$
$\bar{x}_j=\text{ Mittelwert der j. Klasse}$
$\bar{x} = \frac{\sum_{i=1}^{n} \bar{x}_j \cdot h_j}{n}$

### Klassifizierter Median

Medianklasse: In der Medianklasse überschreitet die kumulierte Häufigkeit 50%.

Medianwert: Der Medianwert ist das arithmetische Mittel der Ober-und Untergrenze der Medianklasse.

Medianklasse und Wert können bei gerader Wertanzahl genau auf der Grenze zwischen zwei Klassen liegen.

### Klasifizierter Modus

Modusklasse: Häufigste Klasse

Moduswert: Der Moduswert ist das arithmetische Mittel der Ober-und Untergrenze der Modusklasse.

## Quantile

Quantile sind die Werte, an denen eine bestimmte kumulierte Häufigkeit überschritten wird. Beliebte Quantile sind zum Beispiel der Median oder Quartile, an denen 25% und 75% kumulierte Häufigkeiten übertroffen werden. Sie werden auch q%-Quantile genannt, wobei q eine beliebige Zahl zwischen 1 und 99 ist.

Die Berechnung läuft dementsprechend ähnlich wie beim Median, nur dass zuerst der Rang berechnet werden muss.

$r=\frac{n \cdot q}{100}$

Berechnung wenn r ganzzahlig ist:

$\tilde{x}_q=\frac{x_r + x_{r+1}}{2}$

Berechnung wenn r nicht ganzzahlig ist:

$\tilde{x}_q = x_{\lceil{r}\rceil}$

### Boxplot

Die graphische Darsstellung der Quantile ist der Boxplot
Die Box umfasst dabei den [[Streuungsmaße#Interquartilsabstand IQR|IQR]], die Whisker reichen bis zu den Maximal- und Minimalwerten, oft ist ihre Länge durch den 1.5-Fachen IQR beschränkt. Die restlichen Werte werden als Ausreißer markiert. In der Mitte der Box wird der Median als Linie dargestellt.

