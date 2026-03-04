#Boden #Hydrogeologie #Geobotanik 

## Kapillarität

Beim Kapillaren Aufstieg wirken Schwerkraft und Adhäsionskräfte gegeneinander. Da die Adhäsion höher ist als die Kohäsion, ist der Aufstieg energetisch günstig. Die Lagenergie steigt jedoch mit dem Aufstieg an, solange, bis sie mit dem Energiegewinn durch Adhäsion identisch ist. Je dünner eine Kapillare, desto mehr Fläche im Verhältnis zum gehobenen Gewicht wird benetzt, deswegen steigt das Wasser weiter auf. Die Adhäsion ist stärker.

Formel:

$$
h_c=\frac{p_c}{\rho gr}
$$

p ist der Kapillardruck bzw die Saugspannung, erzeugt durch die Kohäsion der Flüssigkeit, berechnet als $p=2\sigma \cos \alpha$, wobei $\sigma$ die Oberflächenspannung ist.

In einem porösen Medium mit Kugeln von Durchmesser D:

$$
h_c=\frac{2\sigma}{\rho g \frac{D}{8}}
$$

![[{D8D99CBE-292E-4402-9878-7C736D16DF8D}.png]]

Bei steigendem Wasserstand entscheidet das untere Ende der Kapillare, wo sich der Kapillarsaum einstellt, bei fallendem Wasserstand das obere.

Kapillaren haben je nach Größe verschiedene Eigenschaften: größere Kapillaren (also etwa zwischen größeren Teilchen) können mehr Wasser transportieren, dafür jedoch nicht so hoch, während kleinere weniger Wasser transportieren können, dafür jedoch höher. Kleine Kapillaren binden das Wasser fester.

![[{56357698-C6E0-455C-A014-20B3F0B204C8}.png]]

Beachte, dass auch sehr kleine Kapillaren nur wenig Aufstieg zulassen, da sie das aufsteigende Wasser sehr stark binden.

### Adsorptions- und Kapillarwasser

Adsorptionswasser ist über elektrostatische Kräfte so fest an die Bodenpartikel gebunden, dass es kaum entfernt werden kann. Der adsorbierte Zustand ist energetisch sehr günstig, bei der Adsorption wird Wärme frei. Es bilden sich keine Mensiken aus.

Kapillarwasser benetzt die Oberflächen von Kapillaren. Auch Kapillarwasser hat einen im Vergleich zu freiem Wasser reduzierten Dampfdruck, sodass es weniger schnell verdunstet. Es bilden sich Menisken aus.

## Wasserbewegung 

Große Kapillaren können das Wasser schlechter halten, kleinere besser. 

Durch Poren, die so groß sind, dass sie das Wasser nicht halten können, versickert das Wasser weiter nach unten. Oben anstehendes Wasser kann dabei durch die Auflast helfen.

[[Wasserpotential im Boden]]

Wasser bewegt sich immer entlang des Potentialgradienten, vom höheren zum niedrigeren Potential. je stärker der Gradient, desto schneller fließt es ([[Grundwasserfluss]]).

Ist der Gradient positiv, fließt Wasser abwärts, ist es negativ, fließt Wasser aufwärts.

Beispiel: 

![[{4770BE24-6D5E-412B-8ADB-19F22F1E0BF7}.png]]
![[{37E3F306-5475-4553-93DB-546016848EBD}.png]]

Um die Geschwindigkeit zu berechnen, kann man eine angepasste Form des [[Das Darcy-Gesetz]] nutzen, dass statt kf (gilt nur für gesättigte Böden) ku nutzt ([[Hydraulische Durchlässigkeit]]).

ku ist abhängig von der Wasserspannung ([[Wasserpotential im Boden]]), aber auch vom [[Bodengefüge]]:

![[{61416495-7910-44E1-8BF9-01BFE779DB85}.png]]

Beachte die weit höhere Leitfähigkeit aggregierten Tons (Große Poren zwischen den Aggregaten). Die Unterschiedlichen ku-Werte ergebn sich dadurch, dass die Grobporen leerlaufen, dadurch der Fließquerschnitt sinkt und der Transportweg (zickzack durch kleinere Poren) länger wird.

Alternativ kann das Hagen poiseuille-Gesetz genutzt werden, das Radius r und Porenlänge l sowie die Viskosität der Flüssigkeit $\eta$ mit einbezieht:

$Q=\Pi r^4 \Delta \Psi / (8 \eta l)$

Die hohe Wasserleitfähigkeit der Grobporen bei Sättigung führt zu einer Kanalisierung des Wasserflusses, was andere Bereiche entlastet, diese bleiben im Zweifel trocken.

## Infiltration

Wasser gelangt nur bei sehr großporigen Böden durch die Schwerkraft in den Boden, ansonsten wird es eher über Kapillar und Haftkräfte in die Bodenporen hineingezogen. Dabei muss es gegen die Luft, die diese Kapillaren füllt, anarbeiten. Diese Kapillarkräfte erlauben Wasser auch, sich von unten nach oben durch den Boden zu bewegen. Dementsprechend bewegt sich Wasser im Boden seitlich und nach unten gleich schnell.

Dieser Prozess kann zu seltsamen Artefakten führen, etwa, dass eine Sandschicht unter einer Schluffschicht trocken bleibt, bis diese vollständig wassergesättigt ist, da die Kapillarkräfte des Sands aufgrund der höheren Porengröße zu schwach sind, um dem Schluff das Wasser zu entziehen, beziehungsweise die Kapillarkräfte des Schluffs stark genug sind, das Wasser zu halten.

![[{2AD67FAF-A4A4-4DE0-AA17-BEC2E32014EA}.png]]

Die Infiltrationsgeschwindigkeit wird als kf-Wert, der eine bestimmte Wasserleitfähigkeit in cm/Tag beschreibt,  angegeben und wird ebenfalls durch Korngrößen und Kapillardurchmesser bestimmt.

([[Grundwasserfluss]])


| kf  | cm/d    | Beispiele                                                                                |
| --- | ------- | ---------------------------------------------------------------------------------------- |
| 1   | <1      | [[Pseudogley]]                                                                           |
| 2   | 1-10    | stark zersetzte [[Moorböden]], Pseudogley                                                    |
| 3   | 10-40   | [[Parabraunerde]], mittel zersetzte Torfe                                                |
| 4   | 40-100  | fein bis mittelkörnige Sande, Horizonte mit guter Gefügeentwicklung                      |
| 5   | 100-300 | Horizonte mit sehr guter Gefügeentwicklung, mittelkörnige Sande, schwach zersetzte Torfe |
| 6   | >300    | Grobsande, Kiese, Schilfdurchwurzelte Tone                                                                                         |

## Räumliche Variabilität der Wasserflüsse

Die Wasserflüsse in einem Boden unterscheiden sich auch kleinräumig beträchtlich. 

Beispiele aus einem deutschen Buchenwald, Segmente etwa 15*15cm:

![[{BC3D1FED-0713-48F1-A774-0CA7E608EC56}.png]]

Damit unterscheiden sich auch die Stofflüsse stark, wie etwa hier Dissolved organic Carbon:

![[{2F3CB0EF-DA83-4CA5-A53F-4AFC69134CF7}.png]]