#Hydrogeologie 

Herkunft des Wertes: [[Das Darcy-Gesetz]]. K ist abhängig von Fluid- und Matrixeigenschaften.

# Bestimmung

Die Bestimmung kann über einen Darcy-Versuch mit feststellbarem gradh, Volumenstrom und A erfolgen. Auch in der Natur kann er bestimmt werden, wenn diese drei Faktoren eines [[Aquifere]] bekannt sind.

Aus der Durchführung des Darcy Experiments mit Glaskugelmedium (Radius d) ergeben sich verschiedene Proportionalitäten, die insgesamt folgende Formel ausgeben:

$$
K=\frac{Cd^2\rho g}{\eta}
$$

## Bestimmung über Korngrößen

Empirische Beispielwerte: 

![[{9A39F120-E41D-42B9-9F36-B4ED20E73FF7}.png]]

Wie zu erkennen, gibt es viele Überschneidungen und Uneindeutigkeiten. Sogar reine Kornfraktionen haben noch eine K-Variabilität. In der Natur treten dazu vor allem gemischte Sedimente auf. In diesen spielt vor allem die kleinere Kornfraktion eine Rolle für die Permeabilität, da diese die Großen Poren zusetzt.

Zur Groben Bewertung wird die Ungleichkörigkeit U eingesetzt. Diese Berücksichtigt vvor allem kleinere Körner ([[Korngrößenanalyse mittels dry-sieving]]). 

$$
U=\frac{d{60}}{d{10}}
$$

Für den Zusammenhang von K und Korngrößenverteilung gibt es verschiedene empirische Formeln, die jedoch alle eher ungenau und stark variabel sind.

# Permeabilität

C ist die Bodenkonstante. Fasst man beide Bodeneigenschaften zusammen, erhält man k, die sogenannte Permeabilität. Da die Fluideiegnschaften jedoch nicht ignoriert werden können, wird k eher selten genutzt.

$$
\displaylines{
k=Cd^2 \\
K=k\frac{\rho g}{\eta} \\
\text{Kinematische Viskositaet:}v=\frac{\eta}{\rho}
K=k\frac{g}{v}
}
$$

# Fluideigenschaften

Die Dichte von Wasser ändert sich mit der Temperatur, jedoch eher insignifikant. Die Viskosität ändert sich jedoch massiv: Kinematische und dynamische Viskosität halbieren sich etwa zwischen 0 und 25 Grad. K ist also Temperaturabhängig, der Einfachheit halber wird K deswegen oft für Grundwassertypische Temperaturen um 10° angegeben.

Da K direkt Proportional zu den Viskositäten ist, lässt sich mit bekanntem K bei einer Temperatur leicht jedes K für verschiedene Temperaturen berechnen.

# Transmissivität

Die Transmissivität ist der mittlere K-Wert eines Aquifers multipliziert mit der Mächtigkeit. Dabei wird die Heterogenität des Aquifers vernachlässigt. Die Transmissivität beschreibt die Fähigkeit eines epzifischen Aquifers, Wasser weiterzuleiten und damit die ökonomische Nutzbarkeit des Aquifers. Sie ist verhältnismäßig gut messbar. Für T wird der Durchfluss Q eines 1m breiter Streifen betrachtet, der so hoch ist wie der Aquifer. Für K müsste ein 1 mal 1m großer Streifen betrachtet werden, was de facto unmöglich ist.

$$
\displaylines{
T=\frac=KM=\frac{Q}{\frac{\Delta h}{\Delta x}}b \\
Q=-Tb\frac{\Delta h}{\Delta x}
}
$$

Vgl [[Das Darcy-Gesetz#Das Darcy-Gesetz]]

Sinkt der im Feld gemessene Gradient, ist davon auszugehen, dass die Transmissivität also die Mächtigkeit oder Durchlässigkeit) ansteigt, und andersrum.

Beispiellinsen:

![[{8218A800-C00D-4EAA-966D-50AEA4897281}.png]]

Dunkel sind die Stromlinien, hell die [[Grundwasserfluss#Grundwassergleichen]].

# Heterogenität

Natürliche Medien sind nicht homogen. Sie haben an unterschiedlichen Orten im Raum unterschiedliche K-Werte und andere Eigenschaften. Heterogenität spielt sich auf sehr verschiedenen Skalen ab. Eine hochauflösende Betrachtung ist jedoch in der Regel nicht sinnvoll. Daher werden Mittelungsverfahren eingesetzt.

Beispiele mit undurchlässigen Rändern, eingezeichnet sind die Grundwassergleichen, der Fluss ist rechtwinklig dazu. Zonen hohen Potentials haben "Magnetwirkung":

![[{CD02889D-5371-4462-B221-BF19353980AD}.png]]

## Mittelung bei Fluss entlang der Schichten

Arithmetisches Mittel. Schlecht durchlässige Rollen spielen keine größere Rolle als gut durchlässige:

$$
K_x=\sum_{i=1}^n{\frac{K_id_i}{d_{ges}}}
$$

## Mittelung bei Fluss entgegen der Schichten

Harmonisches Mittel. Dabei spielen schlecht durchlässige Schichten eine weitaus größere Rolle. Ist eine gut durchlässige Schicht von zwei schlechten Umgeben, bringt die gute Durchlässigkeit wenig.

$$
K_z=\frac{d}{\sum_{i=1}^n{\frac{d_i}{K_i}}}
$$

## REV

Das REV (Repräsentative Elementarvolumen) ist das kleinste Volumen, für das eine Messung repäsentativ für den gesamten Aquifer ist. Die Werte verschiedener Eigenschaften schwanken stark, wenn man sich nur kleine Proben anschaut. Ab einer bestimmten Probengröße, dem REV, werden alle genommenen Proben ähnliche Eigenschaften haben. Die Mikroskopiscen Eigenschaftsunterschiede werden so schon bei der Probennahme ausgemittelt. Ist das beprobte Volumen zu groß, kann es sein, dass man beginnt eine neue Schicht zu beproben, und die Proben wieder  anfangen, sich zu unterscheiden.

# Anisotropie

vgl [[Anisotropie]]

Der Durchlässigkeitsbeiwert kann auch Anisotrop, also Richtungsabhängig sein, zumm Beispiel durch die Lagerung von flachen Körnern. Die Durchlässigkeit kann sich dabei um den Faktor 10 unterscheiden.

Beispiel zweier homogener Körper, von denen einer anisotrop ist:

![[{3855F7D5-9531-4F98-92CA-DD3C74F22DEF}.png]]

Alle Kombinationen aus Homogenität oder Hetrogenität und Isotropie oder Anisotropie können natürlich entstehen.

Beispiele:

![[{11224183-1061-42D7-A64E-FE6B3ECCD053}.png]]


