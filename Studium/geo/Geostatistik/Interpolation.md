#Hydrochemie #Stat #Geostat 

- Kriging: Berechnung der Autokorrelation mit Variogrammen
- Triangular Irregular Network: Triangulation ([[Grundwasserfluss#Grundwassergleichen]])
- Thiessen-Polygone ([[Niederschlag#Regionalisierung]])
- Inverse Distance Weighing (IDW): Effekt eines Datenpunktes sinkt mit zunehmendem Abstand zum Datenpunkt (1/Distanz Gewicht)
- Computerprogramme

#### Variogramme

In Variogrammen wird die [[Streuungsmaße#Varianz]] eines Datenpaars in Abhängigkeit von deren Distanz abgetragen. Sobald die Kurve abflacht, ist die Distanz groß genug, und die gesamte natürliche Varianz in der Strecke repräsentiert. Vgl [[Hydraulische Durchlässigkeit#REV]]. Ab dieser Distanz sind die Werte völlig unabhängig voneinander. Diese obere Distanzgrenze der Abhängigkeit wird auch als sill bezeichnet. Ein Nugget ist die Beprobungseinheit und Berechnungsbasis. Die Kleinsträumige Varianz geht schon bei der Probennahme verloren.

Eventuell endet der flache Kurvenabschnitt, sobal die Distanz bis in einen benachbarten größeren Abschnitt reicht.

![[{57C811E1-5F91-4629-A1C9-2173A1B02690}.png]]

![[{294A5724-44EE-4F0C-823C-5BD995CCC42D}.png]]

![[{8689D39A-10D9-4A21-AF02-8198C2273D06}.png]]

#### Kriging vs inverse Distance

![[{71673384-53C0-46B7-9F7F-5842AC2ABA2A}.png]]

Die Verläufe sind prinzipiell ähnlich, aber Kriging glättet bestimmte Bereiche stärker. Bei Inverse Distance sind die Probennahmestellen deutlich erkennbar.