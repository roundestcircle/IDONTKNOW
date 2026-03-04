#Bodenschutz

vgl [[Transport und Sedimentation#Particle Transport Fundamentals]]!

Bodenerosion ist die verbreitetste Form der Bodendegradation. Bodenerosion durch Wasser macht mehr als die Häfte aller geschädigten Bodenfllächen aus, Erosion durch Wind etwa ein Viertel. Jedes Jahr gehen in Europa etwa eine Milliarde Tonnen Boden durch Erosion verloren. 16% der Gesamtfläche sind betroffen.

Die Schäden enstehen durch stoffliche (Nährstoffe und Pestizide) Transportprozesse und durch Sedimentverfrachtung, etwa in Stauseen. Dabei geht es nicht nur um Abtrag an einem, sondern auch um Ablagerung an einem andern Ort.

## Erosionsformen

Es werden verschiedene Erosionsformen und Schadbilder unterschieden. Wichtig ist der Unterschied zwischen Flächenabtrag (gleichmäßig, flächig, leicht vorzustellen bei Winderosion, bildet Dünen) und Flächenspülung (das Wasser konzentriert sich in Abflussrinnen, gewinnt an kinetischer Energie, frisst Rinnen, Rillen, Gräben und bildet an der Ablagerungsstätte Kolluvien und Schwemmfächer). Beide Formen können Profilverkürzungen, freie Wurzelteller und Grenzsteine und Waldrandstufen verursachen.

## Prozess

### Wasserosion

![[{84991A93-BD99-4084-903A-407715270F4F}.png]]

Beachte die drei wichtigen Prozesse:
- Aggregatzerstörung
- Partikelablösung durch Splash
- Partikelablösung durch Oberflächenabfluss
- (Transport und Deposition)

Besonders gefährdet sind ackerbaulich genutzte Hügelländer, wie das sächsische und unterbayrische Hügelland. 1/3 aller ackerbaulich genutzten Flächen in Deutschland sind stark gefährdet. 

Übersichtskarte der gefährdeten Gebiete:

![[{5FD23B35-5796-45B7-8B16-BF37E58A6376}.png]]

### Winderosion

Feinsand und Grobschluss lassen sich am besten von Wind erodieren. Sie sind noch leicht, aber nicht stark aggregiert wie feinerer Schluff oder Ton. Windstärken, die auch größere oder kleinere Körner bewegen können, kommen in Deutschland kaum vor. Besonders gefährdet ist Norddeutschland aufgrund der höheren Windgeschwindigkeiten in Küstennähe, und Böden mit hohen Gehalten der genannten Korngrößen, wie Geest, Lössböden ([[Mergelserie]]). Feinere Böden Süddeutschlands sind eher weniger gefährdet.

Übersichtskarte der gefährdeten Gebiete:

![[{EC15D421-BBC1-40BB-AB2F-855157C58A70}.png]]

Eine rauhe Bodenoberfläche, etwa mit Weizenstroh, Furchen, verringert die Windgeschwindigkeit in Bodennähe stark, sodass durch diese ackerbaulichen Maßnahmen das Erosionsrisiko stark gesenkt werden kann. Auch Hecken und Bäume reduzieren die Windgeschwindigkeiten.

## Universal Soil Loss Equation

Bodenabtrag = Erosivität des Mediums/Niederschlags R * Erodierbarkeit des Standorts K

### Erodierbarkeit

Der Erodierbarkeit des Standorts ist von verschiedenen Faktoren abhängig:
- Boden (K)
- Hangneigung (S)
- Hanglänge (L)
- Bewirtschaftung 
	- Bodenbedeckung (C)
	- Bearbeitung (P)

#### L

$L=(0,046 \cdot I)^m$ wobei I die Hanglänge in m und m ein dimensionsloser Hanglängenexponent ist, der abhängig von der Hangneigung tabelliert ist:

| Hangneigung % | m     |
| ------------- | ----- |
| <0.5          | 0.150 |
| 0,6-1         | 0.2   |
| 1.1-3.4       | 0.3   |
| 3.5-4.9       | 0.4   |
| >5            | 0.5      |

#### S

$S=-1,5+\frac{17}{1+e^{2.3-6.1\sin\alpha}}$ wobei alpha die Hangneigung in  Prozent ist.

Abschätzung LS-Faktor:

![[{87005B51-EFF1-4FE1-9658-83EF7837F27D}.png]]

In der Praxis tabellierte Werte nutzen.

#### C

C-Faktor nach Frucht:

| Vegetation            | C       |
| --------------------- | ------- |
| Wald nat              | <0.005  |
| Wald deg              | <0.1    |
| unbeweidetes Grünland | <0,01   |
| beweidetes Grünland   | <0.1    |
| Getreide              | 0.2-0.4 |
| Hackfrüchte           | 0.3-0.8        |

Zwischenfruchtanbau, Mulchsaat, Spurlockerung senken C. Tabellen füllen ganze Bücher.

#### P

P-Faktoren dienen als Korrekturfaktoren, etwa als Querbewirtschaftungsfaktor, der unter 1 liegt und so die geamte Erodierbarkeit senkt.

#### K

Abschätzung der gesamten Erodierbarkeit:

![[{70085577-4E5D-47EE-8BB5-9DA2EAFFBE4C}.png]]

1. Humusgehalt (! Skala an den Balken, nicht am Rand)
2. Gefügestabilität
3. Permeabilität ([[Hydraulische Durchlässigkeit]])

In der Praxis wieder tabellierte Werte nach Bodenart, Zustandsstufe und Ausgangsgestein genutzt.
Die Einordnungen der [[Zustandsstufen]] stammen aus der [[Böden in Deutschland#Geschichte der deutschen Bodenwissenschaften|Bodenschätzung]]. 

### Erosivität

Die Erosivität steigt mit der Tropfengröße des Regens (beachte square cube: Masse steigt weit schneller als Durchmesser) und der Intensität (mm/h). In der Regel werden Niederschläge ab 10mm/h erosiv. Hohe Niederschlagsintensitäten sind in den Tropen häufiger, damit ist dort auch die Erosionsgefahr erhöht.

$$
R=\sum (E_{kin}*I_{max30})
$$

(Summe aller Erosionswiirksamen Ereignisse) wobei empirisch gezeigt wurde dass:

$$
E_{kin}=1.213+0,98 \log I
$$

$I_{max30}$ bezeichnet die maximale Niederschlagsintensität während eines 30-minütigen Niederschlagsereignisses.

In Deutschland gilt die empirische Vereinfachung

$$
R=0,0788 \cdot \text{mittlerer Jahresniederschlag} -2,82
$$

In der Praxis werden oft auch tabellierte, von Regenmenge abhängige R genutzt.

## Toleranzgrenzen

Um das Ertragspotential langfristig nicht zu verschlechtern, wurden verschiedene Toleranzgrenzen festgelegt:

| Bodenmächtigkeit (dm)    | 0-3   | 3-6    | 6-10 | <10       |
| ------------------------ | ----- | ------ | ---- | --------- |
| Gründigkeit              | flach | mittel | tief | sehr tief |
| Tolerenzgrenzen (t/ha/a) | 1     | 3      | 7    | 10          |

## Entkopplung von Stoffkreisläufen

Beispiel Kohlenstoffkreislauf:

Am Erosionsstandort steigt die C-Mineralisierung aufgrund der Lösung orgnaischen Materials, der Freilegung tieferer Bodenschichten und der Zerstörung von Aggregaten. Auch während dem Transport wird vermehrt C mineralisiert. Am Ablagerungsort wird der ursprünglivhe Boden überdeckt, in diesem wird kaum mehr C mineralisiert, während in der neuen, C-reichen Auflage verstärkt  Organisches Material zersetzt wird. Die Stoffkreisläufe beider Böden wurden so gestört.

Beispiel:

![[{82D4540A-CC20-4AEE-85A3-68C6EBE8B1E5}.png]]

Beachte die C-Amsammlung in tieferen Schichten der Kolluvisols.

## Rechtliches

Um EU-Direktzahlungen zu erhateln, gelten verschiedene verschärfte Regeln zur Erosionsprävention auf CC (Cross-Compliance) Flächen. Dazu zählen etwa zeitlich geregelte Pflugverbote oder Vorschriften zur Pflugrichtung. Dies gilt sowohl für Wind- als auch für Wassererosionsgefährdete Flächen.

## Erosionsschutz

Wirksamkeit verschiedener Maßnahmen:

![[{4A057CFA-A96D-4698-9228-205229EB412A}.png]]

Besonders wichtig: Mulchbedeckung, Direktsaat,

Erosionsrisiken lassen sich heute mit Gis räumlich berechnen (mithilfe der oben genannten USLE).