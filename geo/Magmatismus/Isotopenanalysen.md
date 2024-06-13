#Geo #Magmatismus 

## Grundlagen

Isotope eines Elements haben die gleiche Protonen, aber nicht die gleiche Neutronenzahl. Stabile Isotope existieren ewig, radioaktive Isotope zerfallen in ein Tochterisotop, indem sie ein Nuklid, Strahlung und Elektronen abgeben. Sowohl stabile, als auch radioaktive Isotopensystem werden genutzt.

### Zerfallskonstante

Die Zerfallskonstante beschreibt den Anteil eines Radioaktiven Isotops, der pro Jahr zerfällt. 

Zerfallskonstante = $\frac{ln2}{Halbwertszeit}$

Die Zerfallskonstanten werden konstant nachadjustiert und deswegen eigentlich immer angegeben, damit klar ist, welche "Version" verwendet wurde.

Nach der Halbwertszeit, die für ein Element konstant und nicht Konzentrationsabhängig ist, ist die Hälfte der Teilchen zerfallen.
Die absolute Menge des Mutterisotops fällt also zunächst schneller ab und sinkt dann langsamer (mit jedem Zeitschritt halbiert).

## Isotopenanalyse zur Altersbestimmung

Anhand der Konzentrationen von Mutter- und Tochterisotopen zum Beispiel in [[Zirkon]] und bekannten Halbwertszeiten, lässt sich das Alter der Kristalle absolut bestimmen.

## Isotopenanalyse zur Identifikation von Magmenquellen 

In magmatischen Prozessen wird nicht oder kaum zwischen Isotopen eines Elements diskriminiert: das Verhältnis der Isotope verändert sich also im Verlauf der Differenzierung nicht. Es bildet also auch im Endgestein die Verhältnisse an der Quelle ab.

## Rb-Sr-System

Sowohl Rb als auch Sr haben verschiedene Isotope, besonders wichtig sind $\displaylines{^{87}Rb,\ ^{87}Sr$ und $^{86}Sr}$. Die zwei Strontium-Isotope sind stabil, während das Rb-Isotop in $^{87}Sr$ zerfällt.

### Geochronologie

Im Laufe des Zerfalls von Rubidium ändert sich das Verhältnis der zwei Strontium-Isotope. Als Funktion ist es abhängig vom Initialen Verhältnis beim Kristallisieren, Der Rb-Konzentration, der Zerfallskonstante und der Zeit. Hier werden ausschließlich Isotopenverhältnisse und keine absoluten Werte genutzt, da diese mit einem Massenspektrometer gemessen werden können.

$$
\begin{align*}
& \frac{^{87}Sr}{^{86}Sr} &=&(\frac{^{87}Sr}{^{86}Sr})_i &+& \frac{^{87}Rb}{^{86}Sr} & \cdot &(e^{\lambda t}-1) \\
& y &=& b &+& x & \cdot & m 
\end{align*}
$$
(Geradengleichung!)

#### Isochronendiagramm

Beispiel: 
![[th-3694470078.jpg]]

Zu jedem Zeitpunkt ergibt sich also für ein analysiertes Gestein eine Gerade, auf der die Minerale mit verschiedenen intialen Rb/Sr Verhältnissen liegen. Sie haben alle den gleichen Y-Achsenabschnitt, nämlich das Initiale Sr/Sr Verhältnis. Das Sr/Sr-Verhältnis verändert sich mit der Zeit ausschließlich aufgrund des Rb Zerfalls (je mehr RB zu Beginn, desto mehr $^{87}Sr$). Die Steigung der Gerade verändert sich deswegen mit der Zeit: bei t=0 beträgt sie 0, bei hohen t-Werten mehr. Sie bleibt jedoch eine Gerade: Die Minerale, die mit mehr Rb begonnen, erfahren eine stärkere Veränderung als die, die mit weniger Rb begonnen haben.

Hat man also mehrere Proben, kann man eine Linie durch sie legen und so das Ursprungs-Sr/Sr- Verhältnis feststellen, indem der Y-Achsenabschnitt betrachtet wird. Über die Steigung lässt sich dann auch t feststellen:

$t=\frac{1}{\lambda}ln(m+1)$

Das Initiale Sr/Sr-Verhältnis kann anschließend zur Feststellung der Magmenquelle genutzt werden.

### Magmenquellenidentifizierung

Das Sr/Sr-Verhältnis aus Chondriten wird als das der Gesamterde vor 4,5 Ga betrachtet. Auch hier wurde das Initialverhältnis über die Isochrone bestimmt. Da ab etwa vor 3 Ga (angenommen) vermehrt Rubidium in die Kruste eingebuat wurde, steigt dort mit der Zeit das Sr/Sr- Verhältnis deutlich schneller an als im Mantel. Dementsprechend haben Magmequellen in der Kruste ein höheres Verhältnis als Magmenquellen im Mantel

![[Pasted image 20240612185158.png]]

Beachte: Zur Quellenidentifikation müssen immer die Initialwerte betrachtet werden!

## Sm-Nd-System

Im Prinzip sehr ähnlich wie oben: $^{147}Sm$ zerfällt zu $^{143}Nd$. Dazu kommt das stabile Isotop $^{144}Nd$. Auch mithilfe dieses Systems lassen sich genau wie oben Isochronen-Diagramme zeichnen und Alter und Initiales Nd/Nd-Verhältnis bestimmen.

Da Nd jedoch inkompatibler als Sm ist, wird es in der Kruste im Vergleich zu Sm angereichert. Damit steigt das Nd/Nd Verhältnis dieses Mal in der Kruste langsamer als im Mantel, da weniger des Radioaktiven Isotops vorhanden ist. Dementsprechend sind die Nd/Nd- und Sr/Sr- Verhältnisse in der Regel negativ korrelliert. 

### Kombination der Systeme

![[Pasted image 20240612190327.png]]

Viele Proben liegen grob auf einer Linie zwischen der oberen linken Ecke und der unteren Rechten. So lassen sich recht eindeutig Magmenquellen identifizieren. Mittige Proben sind sowohl von Mantel-, als auch Krustengesteinen beeinflusst.

## Sauerstoff-System

Sauerstoff hat drei Isotope, die alle nicht radioaktiv sind. Besonders wichtig sind dabei $^{16}O$ und $^{18}O$. Die Isotopendaten werden im Bezug auf das sogenannte SMOW: Standard Mean Ocean Water angegeben. Dabei wird der $\delta^{18}O$ Wert genutzt, der beschreibt, wie sich das O/O-Verhältnisim Vergleich zum Standard verhält. Ist er positiv, hat sich das schwere Isotop im Verglich zum Standard angereichert, ist er negativ, abgereichert.

Insbesondere in Biogenen und anderen Sedimenten reichert sich das schwere Isotop an.