#Hydrogeologie 

# Basics

Der Niederschlag wird in verschiedene Komponenten aufgeteilt. Dazu gehören Oberflächenabfluss, Zwischenabfluss (im Boden über dem Grundwasser), Bodenfeuchte (Zwischenspeicher) und Grundwasserneubildung. 

[[Bodenwasser]]

Im Humiden Klima ([[Klimaklassifikationen (Makroklima)#Aridität]]) ist die Wasserbewegung netto nach unten gerichtet. Evaporation und Tranpiration können in den oberen Bodenschichten eine nach oben gerichtete Nettobewegung auslösen. Zwischen den Zonen der Bewegung nach oben und der Bewegung nach unten liegt eine Wasserscheide. Diese bewegt sich weiter nach unten, je weniger Wasser vorhanden ist. Je weiter oben sie liegt, desto höher ist der Anteil der GWN am Niederschlag. Im Sommer liegt sie weiterunten, somit wird ein geringerer Anteil des N ins Grundwasser gelangen.

Grundwasserneubildung ist abhängig von Klima, Bodeneigenschaften und Grundwasserflurabstand, also wie weit unter der Oberfläche das Grundwasser liegt. Liegt das Grndwasser näher an der Oberfläche, ist durch kapillaren Aufstieg und Pflanzenwurzeln die GWN verringert. Insbesondere im Wald mit tiefen Wurzeln spielt dies eine Rolle.

## Infiltration

Da Böden nicht homogen sind, fließt das Wasser auch nicht gleichmäßig durch den Boden. Vielmehr bewegt es sich entlang bevorzugter Fließgänge nach unten, etwa Wurmgänge. Je undurchlässiger der Boden, desto stärker konzentriert sich das Wasser auf wenige Gänge.

Die Infiltrationsrate ist zu Beginn eines Regenereignisses am höchsten und sinkt dann ab, bis sie einen Minimalwert erreicht, welcher in der Regel nicht unterschritten wird. Dieser Zusammenhang wurde empirisch modelliert, mithilfe von Doppelringinfiltrometern, Wassergefüllten Ringen, die auf die Erde gestellt werden und deren Wasserstand konstant überprüft werden kann. Trockene Erden können zu Beginn des Regens die hohe Infiltrationsrate länger aufrecht erhalten, da einfach mehr Platz vorhanden ist und Risse und Klüfte einen raschen Abwärtstransport erlauben.

![[Pasted image 20250103131837.png]]

Übersteigt die Regenrate die Infiltrationsgeschwindigkeit des Bodens, fließt das Wasser oberflächlich ab. Man spricht von Infiltrationsüberschuss oder Hortonschem Oberflächenabfluss. Dies kann auch bei kurzen Regenereignissen passieren.

Ist der Boden einfach Wassergesättigt, etwa über stauenden Untergründen und langen Regendauern, fließt das Wasser auch oberflächlich ab. Man spricht dann von Sättigungsüberschuss oder Dunneschem Oberflächenabfluss.

## [[Abfluss]]

### Messung

1. Messgefäß, wie Eimer an Quelle
2. Fließgeschwindigkeit mal Querschnittsfläche. Die Fließges. wird zum Beispiel mit einem hydrometrischen Flügel gemessen, idealerweise an zahlreichen Punkten, da sie sich innerhalb eines Gewässers betraächtlich unterscheidet.
3. Verdünnungsmethode/Tracer, bestimmte Menge Tracer ins Wasser gegeben, Konzentration nach bestimmter Zeit gemessen
4. Wasserstandsmessung an Wehren und Pegeln, dazu muss der Abfluss im Verhältnis zur Höhe vorher festgestellt werden, über eine der anderen Methoden.
5. Berechnung aus Wasserbilanzen, eher selten gemacht, da die anderen Parameter dieser noch schlechter zu messen sind.

### Abflussganglinien

![[{0572F594-404F-45C3-9592-E982DA6A010E}.png]]

Nach einem Niederschlagsereignis verändert sich der Wasserstand eines Flusses. Den Verlauf dieses bezeichnet man als Abflussganglinie. Schnell nach dem Niederschlag erreicht vor allem Oberflächenabfluss und schneller Zwischenabfluss das Gewässer. Der Wasserstand schnellt in die Höhe. Etwas später erreichen dann Grundwasserabfluss und langsamer Zwischenabfluss das Gerinne, während der schnelle Abfluss schon wieder stark zurückgeht. Lange nach dem Niederschlag erreicht das Gewässer nur noch Basisabfluss. GWN verzögert also den Abfluss und reduziert damit Hochwasserspitzen. Dadurch wird auch Pflanzen verbessserte Wasseraufnahme ermöglicht. Während dieses Prozesses schwankt der Grundwasserstand stark. Dies kann die Standfestigkeit von Böden beeinflussen.

Die Leerlaufkurve lässt sich über ein Zerfallsgesetz als exponentieller Zerfall beschreiben ([[Isotopenanalysen#Zerfallskonstante]]). Auf einer Logarithmischen Abflussskala sollte sich somit nach dem Regenereignis eine Gerade zeigen.

Tracer Untersuchungen zeigen, dass auch Grundwasser schnelle Komponenten liefern kann, indem über Druckübertragung altes Wasser aus dem Aquifer gepresst wird, wenn oben Wasser infiltriert.

#### Maillet-Formel

Ohne Grundwasserneubildung ist die Quellschüttung Q proportional zum Grundwasservolumen.

$$
Q(t)=Q_0e^{-\alpha t}
$$

$\alpha$ ist dabei der Leerlaufkoeffizient. Das gesamte Schüttvolumen während einer Zeit ist $\Delta Q/\alpha$

Berechnung von $\alpha$ durch umstellen der Formel:

$$
\alpha=\frac{1}{t}\ln \frac{Q_0}{Q(t)}
$$

# Grundwasserneubildung

[[Wasserhaushalt#Wasserbilanzgleichung]]

![[{29578E53-87B5-484A-8D08-953070A6D3AB}.png]]

Schaubild komplexer GWN-Systeme mit DIN-Benennungen.

Die GWN ist die berechnete Grundlage für die Bewirtschaftung eines Grundwasserleiters. Die Werte sollten Flächendifferenziert angegeben werden, ein Wert für ein ganzes Einzugsgebiet oder ähnliches reicht nicht aus. 

$GWN=N-ET-A_O-A_{IF}\pm \Delta S$

IF steht für Interflow.

## Bestimmung

1. Lysimeter ([[Evapotranspiration#Verdunstungsmessung]])
2. Ganglinienseparation über Abflussmessung, oft ungenau und vereinfachend
3. empirische Modelle, hoher Datenhunger und Komplexität und doch oft nicht ausreichend differenziert (Landnutzungs- Boden-, Flurabstands- und Morphologieunterschiede)
4. Über die Potentialdifferenzen des Bodens (Zeit- und Kostenaufwändig) ([[Wasserhaushalt der Pflanze#Wasserpotential]],[[Bodenwasser#Im Boden wirkende Potentiale]])
5. Chlorid-Methode: Chlorid ist vor allem in Küstengebieten im Regen enthalten. Während dem Transport durch den Boden steigt seine Konzentration, da Teile des Niederschlags verdunsten. Über den Vergleich des Cl-Gehalts frischen Niederschlags im Boden und im Grundwasser, lässt sich berechnen, wie viel Wasser verdunstet ist, und wie viel das Grundwasser erreicht hat. Formel:
$$
GWN=\frac{(N-A_0)Cl_N}{Cl_{GW}}
$$
