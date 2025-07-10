#Hydrogeologie 

[[Grundwasser Basics]]

Grundwasserleiter sind dynamische Systeme die nach einem niedrigen Energiezustand streben. Unterschiedliche Energiezustände bewirken Bewegungen. Essentiell sind dabei vor allem horizontale Potentialunterschiede.

# Potentialmessung

[[Hydrodynamik#Bernoulli im Grundwasser]]
[[Grundwasserprobennahme]]

In der Regel wird einfach der Wasserstand in einem Piezometer, im Prinzip einem Rohr das ins Grundwasser reicht gemessen. Dafür ist eine Referenzhöhe erforderlich, zum Beispiel Normalnull.

Standrohrspiegelhöhe = Piezometerhöhe = Grundwasserspiegel h.

- Druckhöhe: Höhendifferenz Wassereinlass ins Rohr und Wasserstand (pressure head)
- Piezometerhöhe: Wasserstand über Normalnull (hydraulic head)
- Lagepotential: Höhe des Wassereinlasses über Normalnull (elevation head)

# Hydraulischer Gradient

Der hydraulische Gradient ist der Potentialunterschied über eine Strecke.

$$
gradh= \frac{\Delta h}{\Delta x}
$$

Mit Strecke ist dabei nicht der Horizontale Abstand zweier Messpunkte gemeint, sondern tatsächlich die exakte Distanz der Wassereinlässe in den Piezometern. Sie hat also eine horizontale und eine vertikale Komponente. Auch ist der Luftlinienabstand nicht ausreichend, vielmehr muss die Strecke entlang der Fließrichtung, also im Zweifel auch um die Kurve, falls der Aquifer eine Kurve macht, gemessen werden.

In der Regel ist der vertikale Potentialunterschied weit geringer als der Horizontale, aber nicht immer.

Grundwasser fließt immer in Richtung des absteigenden Gradienten.

# Grundwassergleichen

Grundwassergleichen sind die Isolinien gleichen Potentials. Um sie zwischen verschiedenen Messpunkten einzuzeichnen und zu interpolieren, wird das hydraulische Dreieck genutzt. Dazu werden die Punkte über Linien verbunden, diese in Abschnitte eingeteilt und mit den erwarteten Potentialen beschriftet. Gleiche erwartete Potentiale auf diesen Linien lassen sich nun verbinden, um die Grundwassergleichen zu erhalten.

![[{D1C692C3-23F7-4BEC-AD9B-B8A8BC99A9EA}.png]]

Grundwassergleichen sind natürlich eigentlich Flächen und keine Linien, werden aber der Einfachheit halber als Linien projeziert.

## Grundwasserstromlinien

Die Fließrichtung des Wassers ist immer senkrecht zu den Grundwassergleichen. Die Abbildung der Fließrichtung des Wassers bezeichnet man als Grundwasserstromlinien.

# [[Das Darcy-Gesetz]]

# Regionaler Grundwasserfluss

## Grundwasserfluss um Gewässer

Gewässer verbiegen die Grundwassergleichen. Die Wasseroberfläche/Uferlinie lässt sich bei Seen auch als Äquipotentiallinie betrachten. Ein Gewässer liegt in der Regel etwas tiefer oder höher als der umgebende Aquifer, sodass Wasser entweder radial in das Gewässer ein- oder ausfließt.  Meist erfolgt der Fluss nicht direkt gerade, sondern schräg, da das Grundwasser sich auch entlang der größeren, und nicht nur der lokalen Potentialunterschiede bewegt. 

Je steiler der Potentialgradient um ein Gewässer, desto mehr Wasser In- oder Exfiltriert. Dementsprechend kann bei feuchter Witterung, wenn Der Wasserspiegel des Aquifers steigt, mehr Wasser exfiltrieren ([[Grundwasserneubildung#Abflussganglinien]]).

Ein Gewässer kann in manchen Bereichen Wasser aufnehmen und in anderen Abgeben. Flüsse infiltrieren (also liegen über dem Grundwasserspiegel) vor allem in Gebirgen und bei großen Schwemmfächern. In unseren breiten exfiltriert das Grundwasser eher in die Flüsse.

Die Isolinien müssen dann senkrecht zum ein- oder ausströmenden Wasser (also zu den Stromlinien) verlaufen.

Beispiele für einen infiltrierenden und einen exfiltrierenden Fluss:

![[{E08DB4CE-A150-4052-8B7D-DBCCC02E8DF1}.png]]

Beispiele für Seen:

![[{ED7D97C0-79C4-44B1-90E4-0A15E58DFDDD}.png]]
![[{F2477379-AD78-41EC-BA84-EE36A2026673}.png]]

Seen mit oberirdischem Zufluss aber ohne Abfluss infiltrieren ins Grundwasser, bei Seen die Oberirdische Abflüsse aber keine Zuflüsse haben, exfiltriert Grundwasser in den See. Seen ohne Zu- und Abflüsse bilden ein Fenster in das natürliche Fließfeld des Aquifers.

Seen können auch völlig vom Grundwasser abgeschnitten sein, etwa auf massiven Graniten in Skandinavien.

## Grundwasserfluss um Brunnen

Das Grundwasser strömt radial von allen Richtungen in den Brunnen ein. es bildet sich eine Vertiefung im Potentialnetz.
Beispiel für das Zeichnen eines Fließnetzes um einen Brunnen. Dafür werden Hintergrung- und Radialströmung kombiniert. Diese Addition der Fließnetze bezeichnet man als Superpositionsprinzip.

![[{1C6906FF-7501-41BD-BD17-1EFED998AC43}.png]]

## Topographie

Topographische Erhöhungen sind in der Regel eher Orte der Grundwasserneubildung, in Senken exfiltriert das Wasser eher. Der Grundwasserspiegel folgt also grob der Geländeoberfläche.

![[{DA9ED8D5-71C6-40E9-A7CF-9866EA6EEEEA}.png]]

## Verweildauer

Grundwasser in einem Gebiet unterteilt sich oft in Gebiete in verschiedenen Tiefen und mit verschiedenen Flussdistanzen, die dementsprechend auch verschiedene Verweildauern haben.

![[{F664A030-A1BF-40D4-AD93-EABE06A0E9EE}.png]]

## Wasserscheiden und Stagnationspunkte

[[Hydrologisches Einzugsgebiet#Wasserscheide]]

## Störungen

An Störungen ist der Wasserfluss entweder erhöht oder verringert. Grundwasserfließnetze werden also durch die Störungen stark beeinflusst. Über Störungen kann nicht einfach hinweginterpoliert werden.

## Fließnetze zeichnen

1. Grenzen und Ränder des Aquifers bestimmen (numerisch über [[Differentialgleichungen]] auch möglich)
2. Bekannte Potentiale markieren
3. Stromlinien einzeichnen
4. Grundwassergleichen senkrecht zu Stromlinien ziehen
5. (Computerbasiert) 3 und 4 iterieren

Beispielhaftes Aquifer-Fluss-System. Beachte die starke vertikale Flusskomponente und die deswegen irritierenden Piezometermessungen in unterschiedlichen Tiefen. Pure Interpolation ohne diese Komponente würde zu falschen Interpretationen führen.

![[{8B637CA7-4AB9-4C65-8D27-635FC56CBBFA}.png]]

### Randbedingungen

Aquifere können vor allem drei verschiedene Ränder haben: einen undurchlässigen Rand, wie die GW-Oberfläche oder Geringleiter, einen Festpotentialrand wie Oberflächengewässer, oder einen Rand mit konstantem Zufluss, wie eine Grundwasseroberfläche mit  [[Grundwasserneubildung]].

