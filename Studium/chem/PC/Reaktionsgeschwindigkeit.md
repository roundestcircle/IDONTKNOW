#PC #Kinetik

Gruppe:: Kinetik

Die Thermodynamik beschäftigt sich maßgeblich damit, ob, und in welche Richtung eine Reaktion abläuft. Die Kinetik beschäftigt sich jetzt noch dazu mit der Geschwindigkeit und den Umsätzen einer Reaktion.

## Massenwirkungsgesetz

Das Massenwirkungsgesetz beschreibt die Produkt-Edukt-Verteilung bei der Geschwindigkeit 0, also im Gleichgewicht.

$MWG= K_x = \frac{\prod_Px_P^{|\nu_P|}}{\prod_Ex_E^{|\nu_E|}}$,

in Worten: Das Produkt der Produkte durch das Produkt der Edukte.

## Reaktionsgeschwindigkeit

Das MWG beschreibt die Reaktionsgeschwindigkeit an einem Punkt. Nun versuchen wir, sie an jedem Punkt zu bestimmen. Die Reaktionsgeschwindigkeit ist der Stoffumsatz je Zeiteinheit.

Für jeden beteiligten Stoff einer Reaktion gilt dann (Nebenreaktionen und stöchiometrie müssen bekannt sein):

$V_R=\frac{1}{\nu_A}\frac{d[A]}{dt}=\frac{1}{\nu_B}\frac{d[B]}{dt}=...$

Achtung: Hierbei wird die Momentangeschwindigkeit berechnet! Die Formel definiert die Ableitung der Funktion des Konzentrationsverlaufs mit der Zeit.

Das bedeutet auch, dass nur ein Stoff beobachtet werden muss, aus ihm lassen sich alle anderen Stoffkonzentrationsveränderungen ableiten.

### Einteilung von Reaktionsgeschwindigkeiten

1. Sehr schnell, instantan: etwa Säure-Base-Reaktionen
2. Mittelschnell, Sekunden bis Tage: etwa Gasphasenreaktionen
3. Sehr Langsame Reaktionen, Tage bis Jahrhunderte: etwa kernchemische Zerfallsprozesse.

### Geschwindigkeitsgesetze

Die Geschwindigkeitsgesetze sind empirisch aufgestellte Gleichungen für die Geschwindigkeit von Gesamtreaktionen (unbekannte Molekularität).

Für 
$\ce{A->B}$:

$V_R=k[A]^{|\nu_A|}$

k ist die Reaktionsgeschwindigkeitskonstante. [[Geschwindigkeitskonstante]]

Für 
$\ce{A+B->C}$:

$V_R=k[A]^{|\nu_A|}[B]^{|\nu_B|}$

#### Integrierte Geschwindigkeitsgesetze

Integrierte Geschwindigkeitsgesetze erlauben die Berechnung der Konzentrationen der beteiligten Stoffe nach einer bestimmten Zeit. Siehe oben: Die Reaktionsgeschwindigkeit ist die Ableitung der C(t)-Funktion.

##### Reaktion erster Ordnung:

$V_R=\frac{d[A]}{dt}=k[A]^1$

Integrieren, Vereinfachen:

$[A]=[A]_0e^{\nu_Akt}$

Ein bekanntes Besipiel für diesen Reaktionstyp ist Radioaktiver Zerfall ($\nu_A=-1$). Der Zerfall ist exponentiell.

Halbwertszeit:

$t_{\frac{1}{2}}=\frac{1}{k}\ln 2$

Die Halbwertszeit ist unabhängig von der Konzentration des Ausgansgsstoffes.

$[k]=\frac{1}{s}$, k ist also eine Frequenz.

##### Reaktion zweiter Ordnung:

$V_R=-\frac{1}{2}\frac{d[A]}{dt}=k[A]^2$

Integriert:

$[A]=\frac{[A]_0}{[A]_0k^`t+1}$

Halbwertszeit:

$t_{\frac{1}{2}}=\frac{1}{k^`[A]_0}$

Die Halbwertszeit ist jetzt abhängig von der Startkonzentration des Ausgangsstoffes. Dies liegt daran, dass die Wahrscheinlichkeit des Aufeinandertreffens zweier Teilchen mit der Konzentration steigt. Der Zerfall ist weniger steil als bei Reaktionen erster Ordnung.

$[k^`]=\frac{l}{mol\cdot s}$

##### Reaktion nullter Ordnung:

Reaktionen nullter Ordnung haben eine konstante Reaktionsgeschwindikeit.

$V_R=-\frac{d[A]}{dt}=k[A]^0=k$

Integriert:

$[A]=-kt+[A]_0$

Der Abfall ist linear.

Halbwertszeit:

$t_{\frac{1}{2}}=\frac{[A]_0}{2k}$

Die Halbwertszeit ist wieder von der Ausgangskonzentration abhängig. Von dort an fällt die Konzentration linear ab.

Reaktionen nullter Ordnung treten auf, wenn die Geschwindigkeit nicht wesentlich von den Reaktionspartnern, sondern von externen Einflüssen bestimmt wird. Dies ist etwa bei Elektrodenreaktionen, Katalysatorreaktionen und photochemischen Reaktionen der Fall.

##### Reaktionen dritter Ordnung:

Reaktionen dritter Ordnung haben kein allgemeingültiges Geschwindigkeitsgesetz, da sie sich stark unterscheiden können. Einzelfälle müssen betrachtet werden.

### Abfolgen von Elementarreaktionen

Um komplizierte Reaktionen einfacher zu beschreiben, kann man sie zerlegen.

#### Reaktion mit Zwischenprodukt:

$\ce{A->[k_a]Z->[k_b]P}$

Relativ einfach:

$\frac{d[A]}{dt}=-k_a[A]$

$\frac{d[P]}{dt}=k_b[Z]$

Z ist komplizierte, da es konstant von A her zunimmt und nach P abnimmt:

$V_R= \frac{d[P]}{dt} =-k_b[Z]+k_a[A]$

$[A]=[A]_0e^{\nu_Akt}$ einsetzen und umstellen:

$\frac{d[Z]}{dt} +k_b[Z]=k_a[A]_0e^{\nu_Akt}$

Dies ist eine sogenannte [[Differentialgleichungen]] in Standardform, die mathematisch lösbar ist (für $[Z]_0=0$). Lösungen lassen sich in mathematischen Formelsammlungen nachschauen.

Nachgeschaute Lösung:

$[Z]=\frac{k_a}{k_b-k_a}(e^{-k_at}-e^{-k_bt})[A]_0$

Unter der Randbedingung, dass $[A]+[Z]+[P]=[A]_0$ ([[1. Hauptsatz der TD]]), lässt sich für P herleiten:

$[P]=[A]_0(1+\frac{k_ae^{-k_at}-k_be^{-k_bt}}{k_b-k_a})$

Bei längeren Reaktionsabfolgen steigt die Komplexität rapide an.

Graphischer Verlauf der Konzentrationen:

- A fällt exponentiell ab.
- Z durchläuft einen Höhepunkt, der sich durch das Verhältnis von $k_b$ zu $k_a$ einstellen lässt. Je höher $k_b$ im Verhältnis, desto flacher der Höhepunkt.
- P steigt gleichmäßig an nach langsamerem Anstieg zu Beginn (noch wenig Z gebildet.)

Vereinfachung:

Wenn Z eine Quasistationäre Konzentration hätte, wäre das System weit leichter zu beschreiben. Anzunehmen wäre also eine realtiv konstante Konzentration von Z nach kurzer "Inkubationsperiode". In dieser Periode gilt: $\frac{d[Z]}{dt}=0$. Dazu muss dei Reaktion so eingestellt werden, dass die Konzentration von Z im Vergleich zu Edukt und Produkt verschwindend gering bleibt (sehr hohe $k_b$, niedrige $k_a$, alles Zwischenprodukt reagiert mehr oder weniger sofort ab gbs ist $\ce{A->Z}$).

Dadurch wird aus der zweistufigen Quasi eine einstufige Reaktion.

$\frac{d[Z]}{dt}= k_a[A]-k_b[Z]\approx0$

Daraus folgt:

$[Z]\approx \frac{k_a}{k_b}[A]$

Aus dieser Gleichung ist leicht ersichtlich, was zu tun ist um $[Z]$ zu senken.

Herleitung übersprungen:

$\frac{d[P]}{dt}=k_a[A]$

$k_b$ ist so schnell, dass sie für die Gesamtreaktion irrelevant wird. Stattdessen bestimmt jetzt nur noch $k_a$ die Reaktionsgeschwindigkeit. Vergleiche oben: [[Reaktionsgeschwindigkeit#Reaktion erster Ordnung]]. 

Integriertes Geschwindigkeitsgesetz erster Ordnung einsetzen:

$[P]=[A]_0(-e^{-k_at})$

Die Konzentration von P folgt also einem invertierten exponentiellen Zerfall.

$[P]$ ist jetzt näherungsweise nur noch von zu A gehörenden Werten abhängig.

#### Vorgelagertes Gleichgewicht

$\ce{A<=>[k_a][k_a^`]Z->[k_b]P}$

Ein solches Gleichgewicht zwischen Edukt und Zwischenprodukt kann nur bestehen wenn $k_a^`>>k_b$, sonst reagiert das Zwischenprodukt ab, bevor es zur Rückreaktion kommen kann.

[[Kinetik von Reaktionen nahe dem Gleichgewicht]]

$\frac{d[P]}{dt}=k_b[Z]$

Herleitung übersprungen, im GG:

$\frac{d[P]}{dt}=k_b[Z]$

$\frac{d[P]}{dt}= k_b \frac{k_a}{k_a+k_a^`}[A]$

Oder zu einer neuen Konstante Zusammengefasst:

$\frac{d[P]}{dt}= k_{GG}[A]$

Wieder Runtergebrochen auf Reaktion erster Ordnung!


