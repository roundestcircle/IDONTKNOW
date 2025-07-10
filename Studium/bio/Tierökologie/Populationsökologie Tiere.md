#Tieröko 

[[Populationsökologie Pflanzen]]

## Konzept

Die Population ist die Summe der Individuen einer Art, die in einem bestimmten Gebiet leben. Wie groß diese bestimmten Gebiete sind, ist schwierig festzulegen, außer es handelt sich um klare, natürliche Grenzen.

[[Populationsökologie Pflanzen#Population]]

Metriken der Populationsgröße:
- Populationsdichte/Absolute Abundanz
- Populationsgröße/einfache Individuenzahl
- Relative Abundanz (verschiedene Indizes wie Anzahl bewohnter Habitate)

## Methoden

### Tiere Zählen

In der Regel Citizen Science oder Jagdberichte der Jäger. Fangmethoden für schwierig zu zählende Organismen beinhalten Stichproben (Linienkartierung, Fang-Wiederfang, Zeitsammelmethode) und besondere Lockmittel wie Netze, Lampen und Lockstoffe.
Oft kommen auch indirekte Messungen dazu, zum Beispiel über Gesänge, Geräusche und 
Schadbilder.

### Monitoring von Geburts-und Sterberaten

- Kohorten (Verfolgen einzelner Individuen bis zum Tod)
- Stationär (Eine Aufnahme aller gefundenen Tiere und ihrer Alter)

### Lebenstafeln

Aus den erhobenen Daten lassen sich Lebenstafeln erstellen. Für die Erstellung sind nur die Individuen pro Altersgruppe und die Nachkommenzahl nötig, der Rest wird berechnet.

1. Stadium und Zahl der Individuen a erfassen und eintragen.
2. Überlebensraten l vom ersten Stadium in die weiteren berechnen.
3. Mortalität d je Stadium berechnen (Im Verhältnis zur Startpopulation)
4. Alterspezifische Mortalitätsrate q berechnen (Im Verhältnis zur Individuenzahl des betrachteten Stadiums)
5. Killing Power k berechnen ([[Intraspezifische Konkurrenz (Tiere)#Quantifizierung intraspezifischer Konkurrenz]])
6. Nachkommenzahl F je Altersgruppe erfassen und eintragen
7. Fekundität m für jedes Stadium berechnen (Nachkommen pro Individuum)
8. Überlebensrate l mit Fekundität m für alle Stadien multiplizieren, alle resultierenden Werte addieren, das Ergebnis ist die Reproduktionsrate R (siehe unten)

| Stadium | Zahl  | Überlebensrate | Mortalität je Stadium | Altersspezifische Mortalitätsrate | killing power | ... |
| ------- | ----- | -------------- | --------------------- | --------------------------------- | ------------- | --- |
| 1       | 44000 | 1              | 0.92                  | 0.92                              | 1.099         |     |
| 2       | 3500  | 0.08           | 0.023                 | 0.286                             | 0.146         |     |
| 3       | 2500  | 0.057          | 0.014                 | 0.240                             | 0.119         |     |
| 4       | 1900  | 0.043          | ...                   | ...                               | ...           |     |
| ...     | ...   | ...            |                       |                                   |               |     |

Beispiel für Seepocken:

![[Pasted image 20240722152520.png]]

### Überlebenskurven

Ebenso lassen sich Überlebenskurven erstellen, in der die Abnahme der Individuenzahl mit dem Alter abgetragen wird. Diese kann sowohl aus einer stationären Erhebung erstellt werden, in der alle Altergruppen erhoben werden, als auch aus einer Kohortenerhebung, in der die Überlebenden einer Generation zu jedem Zeitpunkt erhoben werden.

Der schwierigste Teil dieser Erhebung ist tatsächlich die genaue Altersbestimmung bei Überlappenden Generationen, dafür wird Zahnabrieb, Beringung oder ähnliches eingesetzt. Bei Schildkröten lassen Wachstumsringe feststellen.

Der Verlauf der Überlebenskurve unterscheidet sich je nach Art. Grob lassen sich drei Typen unterscheiden, doch die Variationen sind gigantisch, fast jede vorstellbare Kurve auch mit mehrfachen Hochpunkten etc lässt sich finden.

Drei Typen:
![[Pasted image 20240722153239.png]]

## Populationswachstum

### Individuenzahl

$N(t+\delta t)=N(t)+Geburten-Sterbefälle+Zuwanderung-Abwanderung

### Unbegrenztes Modell

Zu und Abwanderung werden zunächst ausgeklammert.

Der Reproduktionskoeeffizient oder die individuelle Wachstumsrate setzt sich zusammen aus der individuellen Geburten und Sterberate (s.o.).

$R=g-s=\frac{Geburten}{N(t)}-\frac{Sterbefaelle}{N(t)}$

Andere Berechnung: 

$RN(t)=N(t+1)-N(t)$

Im Unbegrenzten Modell ist dieser Koeffizient unabhängig von der Populationsgröße.

Daraus ergibt sich:

$N(t+1)=N(t)+gN(t)-sN(t)$

Bzw:

$N(t+1)=N(t)+RN(t)$

Beispiele:

![[Pasted image 20240722153354.png]]

Achtung: Die individuelle Wachstumsrate ist nicht identisch mit der Wachstumsrate der  Population! Diese ist auch abhängig von der Populationsgröße.

### Logistisches Modell

Führt man [[Intraspezifische Konkurrenz (Tiere)]] in das Model ein, sinkt die individuelle Wachstumsrate mit der Dichte und unterschreitet bei K 0.

Daraus ergibt sich ein logistisches Populationswachstum. Die individuelle Wachstumsrate ist zwar ganz zu Beginn am höchsten, durch die höhere Anzahl an Tieren ist das absolute Wachstum in der Mitte am größten.

Es lassen sich komplexe Gleichungen aufstellen, in Abhängigkeit von N, $R_{max}$ und K.

Zum Beispiel:

Keine überlappenden Generationen:

$N(t+1)=(1+R_{max}-\frac{R_{max}N(t)}{K})N(t)$

Bzw 

$\frac{dN}{dt}=r\frac{K-N}{K}N$

Überlappende Generationen (Kontinuierliches Populationswachstumsmodell):

[[Populationsökologie Pflanzen#Populationswachstum]]

r ist die Differenz der Geburten und Sterberate.

$\frac{dN}{dt}=rN(t)$

Integriert:

$N(t)=N(0)e^{rt}$,

wobei r die Wachstumsrate ist.

[[Differentialgleichungen]]

Aus den Gleichungen ergeben sich folgende einfache Schlussfolgerungen:

N << K: exponentielles Wachstum
N = K: kein Wachstum
N >> K: Rückgang der Population

Diese Wachstumsmodelle können zur Planung der Nutzung von Naturressourcen genutzt werden, etwa um Überfischung zu vermeiden. Dafür sind jedoch genaue Daten zu den Altersstrukturen der Fischbestände nötig, die oft ihrerseits nur von Fischern kommen.

### Zu und Abwanderung

Die Menge der zu und abwandernden Individuen hängt von der Distanz zwischen den Populationen und der Mobilität ab. Zu- und Abwanderung erlauben genetischen Austausch.

[[Metapopulationstheorie]]

Populationen, die netto Individuen abgeben, bezeichnet man als source-Populationen. Sie befinden sich oft in sehr günstigen Gebieten. So kann Abwanderung auch in ungünstige Gebiete stattfinden. In diesen Gebieten liegen oft Populationen, die netto Individuen aufnehmen, sogenannte sink-Populationen. Daraus folgt, dass das Vorhandensein einer Art nicht direkt auf eine stabile Population in dem Gebiet hindeutet oder gar auf Populationswachstum.

## [[Populationsökologie Pflanzen#r- und K-Strategen]]

Es gibt ein Kontinuum zwischen den r und K-Extremen. Sogar einzelne Arten können je nach Zet und Umgebung die Strategie wechseln.

## Populationsschwankungen

Modelle sagen eine große Stabilität der Populationen voruas, die es in der Regel nicht gibt. 

In der Regel ist K abhängig von der Mortalitätsrate. Diese schwankt in einem gewissen Bereich, wewegen auch K und damit das Populationswachstum schwankt (es kann s auch schnell negativ werden). Viele verschiedene Faktoren beeinflussen die Mortalitätsrate, etwa Nahrungsverfügbarkeit, Raum oder [[Biotische Interaktionen (Tiere)]]. Je größer diese Umweltschwankungen, desto größer ist dann logischerweise auch die Schwankung der Populationsgröße.

Oszillationen sind schwache und unregelmäßige Schwankungen.

Fluktuationen sind stark und oft regelmäßig. 

Erklärungen für diese Fluktuationen könnten zum Beispiel sein, dass dichteregulierende Faktoren zeitverzögert einsetzen. So schießt die Population erst über K hinaus, fällt dann wieder darunter zurück und durchläuft so Zyklen.

[[Intraspezifische Konkurrenz (Tiere)]]

Auch die Jahrezeiten oder unvorhersagbare Umweltschwankungen können Populationsschwankungen auslösen. 

In Experimenten wurde gezeigt, dass allein schon stochastische Effekte große Schwankungen hervorrufen. Aus vielen Populationen ähnlicher Größe wird innerhalb weniger Zeitschritte eine sehr breite Verteilung verschiedener Populationsgrößen. Stochastische Effekte können, insbesondere bei kleinen Populationen, auch bei positivem Populationswachtsum Aussterbereignisse hervorrufen.

## Life-History-Theorie

Nach der Life-History-Theorie beeinflusst der Lebensverlauf der Individuen bedeutsam auch die Populationsentwicklung.

Verschiedene Arten haben ganz verschiedene Lebensverläufe und Strategien. Sie setzen sich zusammen aus sich abwechselnden Phasen und Strategien des Überlebens, des Wachstums und der Fortpflanzung. Sie können nur einmal ablaufen oder sich zyklisch oder asymmetrisch wiederholen. Die Abfolge ist arttypisch, aber nicht festgesetzt und können durch Umwelteinflüsse beeinflusst werden. 

Faktoren sind etwa das Alter beim ersten Nachwuchs, Alterungsprozesse, Immunantwort, Wachstumsrate, Größe bei der Geburt, Brutpflege etc.

Arten mit einer Fortpflanzungsphase bezeichnet man als semelpar, Arten mit mehreren Fortpflanzungsphasen als iteropar.

![[Pasted image 20240722151102.png]]

Verschiedene Life Histories schlagen sich in uterschiedlichen Lebenstafeln nieder.

### Trade Offs

Sachzwänge erfordern Kompromisse beim Energieeinsatz. So ist etwa die Elterntiersterblichkeit oft deutlich höher als die Sterblichkeit adulter Tiere ohne Nachwuchs. Trade Offs sind ein essentieller Bestandteil der Unterschiedlichkeit der Lebensstrategien.