#Biogeochemie 

Gruppe:: Grundlagen

## Biogeographie

vgl #Biogeo 

Die Diversität des Bodenlebens ist vielleicht geringer als bei Pflanzen und Tieren. Es gibt zahlreiche ubiquitäre, aber vermutlich auch sehr viele endemische oder stark eingeschränkte Arten. Der Einfluss der geographischen Lage ist also auch bei Bodenleben nicht zu vernachlässigen.

Im Prinzip gibt es kaum Standorte, wenn überhaupt, die kein Mikrobenleben zulassen.

## Bodeneigenschaften

In China wurden großflächig verschiedene Böden und das Leben darin analysiert. Dabei wurde festgestellt, dass die Biomasse vor allem vom Kohlenstoffgehalt des Bodens, Huminsäuregehalt und amorphem Eisen bestimmt wird. Die Struktur der Lebensgemeinschaft dagegen hängt vor allem von der geographischen Breite ab. Bei höheren Niederschlägen werden Pilze begünstigt ([[Edaphon#Quantität]]).

In einer Studie in Nord- und Südamerika wurde festgestellt, das die Biodiversität vor allem mit dem pH-Wert zusammenhängt. Sie ist zwischen pH 6 und 8 maximal:

![[{DBB244A6-F2C6-4A42-9F7E-B2AB3A7D848E}.png]]

Andere wichtige Bodenvariablen sind jedoch auch die Lagerungsdichte, Aggregierung, Textur, Tonmineral-Gehalt, Temperatur, Bodenwasergehalt und Sauerstoffkonzentration.

[[Boden als Standortfaktor]], [[Boden als Habitat]]

## Nutzung

In den Tropen hat eine Studie gezeigt, dass mit zunehmender Nutzungsintensität die Mikrobendiversität leicht abnimmt:

![[{4720A522-EB17-41F7-8746-A55ADE4902A8}.png]]

## Zeit

Die Quantität der Mos schwankt mit den Jahreszeiten. Sie ist im Sommer tendeziell am höchsten. 

## Stochastik

- Variabilität: Änderung einer Größe über Zeit oder Rahmenbedingungsänderungen. Quantifizierung mit #Stat 
- Heterogenität: Räumliche Variation einer Größe. Quantifizierung mit #Geostat 
- Autokorrellation: Gegenseitige Abhängigkeit räumlich verteilter Daten. Quantifizierung der Ähnlichkeit in Abstandsabhängigkeit.

- Gewissheit: Eintretenswahrscheinlichkeit ist 100%.
- Risiko: Eintretenswahrscheinlichkeit ist kleiner als 100%, aber die Wahrscheinlichkeit lässt sich statistisch berechnen
- Ungewissheit: Eintretenswahrscheinlichkeit ist kleiner als 100%, und sie lässt sich nicht berechnen.

## Raum

### Mikroheterogenität

Bakterien besiedeln nur Poren in einer Größe von 2,5 bis 9 Mikrometer. Damit sind 20 bis 50% des gesamten Porenraums nicht besiedelbar. Dazu leben sie nur auf den Oberflächen der Festphasen und nur in Wasserfilmen oder wassergefüllten Poren.

### Heterogenität auf Ökosystemskala

Die räumlichen Verteilungen etwa von Pilzen sehen oft chaotisch aus.

### Vertikale Verteilung

Die mikrobielle Biomasse ist am größten in den oberen 10 Bodenzentimetern und nimmt darunter exponentiell ab. 65% aller Biomasse befindet sich in den oberen 25 Bodenzentimetern.

### Skalenproblematik

[[Dimensionen der Geoökologie#Skalenfrage]]

Je nach betrachteter Skala fallen kleinräumige Heterogenitäten raus, oder großräumige werden nicht beachtet. Die Skalenfrage ist daher immer Fragestellungsabhängig.

### Interpolation

- Kriging: Berechnung der Autokorrelation mit Variogrammen
- Natürlicher Nachbar: Triangulation, Gewichtung, Thiessen-Polygone ([[Niederschlag#Regionalisierung]])
- Inverse Distance: Effekt eines Datenpunktes sinkt mit zunehmendem Abstand zum Datenpunkt
- Computerprogramme

#### Variogramme

In Variogrammen wird die [[Streuungsmaße#Varianz]] eines Datenpaars in Abhängigkeit von deren Distanz abgetragen. Sobald die Kurve abflacht, ist die Distanz groß genug, und die gesamte natürliche Varianz in der Strecke repräsentiert. Vgl [[Hydraulische Durchlässigkeit#REV]]. Ab dieser Distanz sind die Werte völlig unabhängig voneinander. Diese obere Distanzgrenze der Abhängigkeit wird auch als sill bezeichnet. Ein Nugget ist die Beprobungseinheit und Berechnungsbasis. Die Kleinsträumige Varianz geht schon bei der Probennahme verloren.

Eventuell endet der flache Kurvenabschnitt, sobal die Distanz bis in einen benachbarten größeren Abschnitt reicht.

![[{57C811E1-5F91-4629-A1C9-2173A1B02690}.png]]

![[{294A5724-44EE-4F0C-823C-5BD995CCC42D}.png]]

#### Kriging vs inverse Distance

![[{71673384-53C0-46B7-9F7F-5842AC2ABA2A}.png]]

Die Verläufe sind prinzipiell ähnlich, aber Kriging glättet bestimmte Bereiche stärker. Bei Inverse Distance sind die Probennahmestellen deutlich erkennbar.