#Hydrochemie #Hydrogeologie

[[Grundwasserprobennahme]]

# Anorganische Analytik

## Übersicht

| Methode             | Anwendung                                                       |
| ------------------- | --------------------------------------------------------------- |
| Elektroden          | pH, Eh, Temp, Sauerstoff                                                                |
| Titrationen         | m-Wert, s-Wert                                                  |
| IR-Spektroskopie    | TOC, TIC, DOC, DIC                                              |
| Total-Analysatoren  | C, N, P                                                         |
| Photometrie         | Nitrat, Nitrit, Ammonium, Phosphat, Silizium, Eisen-2, Gesamt-N |
| IC                  | Na, K, Ca, Mg, F, C, Sulfat                                     |
| F-AAS               | Na, K, Ca, Mg, Fe, A                                            |
| GF/CV/FI-Hybrid-AAS | PB, Cd, Hg, Se, Sb, Te, ...                                     |
| ICP-OES             | Na, K, Ca, Mg, Fe, Al, Mn, Zn, ...                              |
| ICP-MS              | Cd, Co, Cu, Cr, Ni, Zn, Pb, SEE, U, Th, ...                     |

## Elektroden

Anwendung: pH, Eh, Temperatur, Sauerstoff, Ionenselektive Sonden.

Sehr schnell, einfach und meist mit ausreichender Genauigkeit im Standardeinsatz.

## Titrationen

Anwendung: m-Wert, s-Wert
[[Kalk-Kohlensäure-Gleichgewicht#Titration]], [[Säure-Base-Reaktionen#Titration]]

## IR-Spektroskopie

Anwendung: TOC, TIC, DOC, DIC ([[Organische Bodensubstanz]])

Mittels Infrarotwellen wird nach der Verbrennung der CO2-Gehalt der Abluft gemessen. Die einzelnen Bestandteile werden vorher durch Aufbereitungschritte getrennt oder als Differenz berechnet.

## Colorimetrische Methoden

Zum Beispiel automatische Titration mit sehr feinen Titrierspitzen, basierend auf Farb-  oder pH-Wert-Reaktionen. Farbänderungen können automatisch festgestellt werden.
Schnell, günstig, geringer Aufwand und sehr zuverlässig, aber mit geringer Genauigkeit.

Automatik-Titrierer:
![[{B89210F9-88AF-40B7-9C1D-40CD0EF94DF0}.png]]

## Total-Analysatoren

Anwendung: C, N, P

## Photometrie

Anwendung: Nitrat, Nitrit, Ammonium, Phosphat, Silizium, Eisen-2, Gesamt-N

Zugabe von Komplexbildnern oder anderen Reagenzien bewirkt Farbreaktion mit spezifischen Inhaltsstoffen. Danach wird die Extinktion von bestimmten Wellenlängen gemessen. Je mehr Inhalt, desto mehr Extinktion. In der Regel wird dafür zunächst eine Kalibrierreihe mit bekannten Konzentrationen gemessen. Relativ schnell, genau und einfach, Jedoch teuer aufgrund hohem Reagenzien- und Entsorgungsbedarf.

Aufbau eines Photometers: 

![[{05EB1772-CC4A-46E8-8710-C3440EFD657F}.png]]

Schema:

![[{E17AFE32-77CD-4645-8291-5EB52337C127}.png]]

Transmission: $T= \frac{I}{I_0}$

Lambert-Beersches Gesetz:

Extinktion: $E=-\lg T =lg\frac{I_0}{I}= \epsilon cd$

c ist die Konzentration, d die Dicke der Probe, $\epsilon$ ist ein stoffabhängiger molarer Absorptionkoeffizient, der etwa über eine Kalibrierreihe gemessen werden kann.

Zur Berechnung dient dann:

$c=\frac{E}{\epsilon \cdot d}$

Beispielhafte Eichgerade:

![[{79261AFA-E4BB-4326-AB11-59FEA282A6F5}.png]]

Für sehr viele Proben kann ein segmented Flow Analyser genutzt werden, der Proben und Reagenzien automatisch durch das Photometer führt.

Ein Flammenphotometer misst die Abgabe bestimmter Wellenlängen durch eine Flamme. Vor allem für Erdalkalien und Alkalien geeignet. Der operative Aufwand ist aufgrund von Störlicht und störender Gaszufuhr von außen in die Flamme recht hoch.

## IC

Anwendung: Na, K, Ca, Mg, F, C, Sulfat

Ionenchromatographie. Eine wässrige Probe wird durch eine Säule aus Material geleitet, dass unterschiedliche Ionen unterschiedlich lang zurückhält. Die Ionen erreichen den nachgeschalteten Detektor also nacheinander. Der Detektor kann somit simpel aufgebaut sein, etwa als Letfähigkeitsdetektor. Wenn der Eluent, der die Probe durch die Säule trägt, leitend ist (etwa Natriumcarbonatlösung) wird ein Kationentauscher eingesetzt um durch Protonen als Austauschion die Leitfähigkeit zu reduzieren. Sehr genaue Ergebnisse. Nicht geeignet für Carbonat und Hydrogencarbonat. Das Gerät und der Eluent sind jedoch empfindlich und teuer.

## AAS

Atomabsorptionsspektroskopie.
Eine wässrige Probe wird zerstäubt und in ein Plasma überführt. Bei Anregung durch Licht wird dieses in einer bestimmten Wellenlänge absorbiert. Der Detektor misst die Lichtintensität und bemerkt so Absorptionen. Jedes Ion absorbiert bei spezifischen Wellenlängen am meisten (Absorptionsmaximum). In der Regel werden Lampen genutzt, die sehr spezifiesch Wellenlängen ausstrahlen können, die genau dem Absorptionsmaximum des zu untersuchenden Elements entspricht.

Die Zeeman-AAS-Technik nutzt dazu noch verschieden polarisiertes Licht zur Erhöhung der Genauigkeit.

### F-AAS

Anwendung: PB, Cd, Hg, Se, Sb, Te, ..., sehr genau, aber keine Spezies bestimmbar, nur Gesamtmenge.

Anwendung: Na, K, Ca, Mg, Fe, Al, sehr genau, aber keine Spezies bestimmbar, nur Gesamtmenge.

### GF/CV/FI-Hybrid-AAS

Weiter erhöhte Genauigkeit durch extreme Temperaturen: GraphitrohrAAS. Extrem geringe Nachweisgrenzen.

Blick in ein Graphitrohr:

![[{CE17C2D7-0290-40A6-9C5F-27619919222A}.png]]

Die winzige Probe liegt in der Schale in der Mitte.

## ICP-AES

Anwendung: Na, K, Ca, Mg, Fe, Al, Mn, Zn, ... sehr genau, aber keine Spezies bestimmbar, nur Gesamtmenge.

Inductively Coupled Plasma - Atomic Emission Spectroscopy

Prinzipiell ähnlich wie AAs, unter noch weit höheren Temperaturen und speziellem Detektor- und Ioniserungssetup, dass die Aufnahme mehrerer Spektrallinien auf einmal erlaubt. Das Plasma wird durch einen Argon-Strom stabilisiert. Emissionen der Elemente werden gemssen.

Schema:

![[{4909843A-A012-44D6-8181-49DBA7FC6C2B}.png]]

## ICP-MS

Anwendung: Cd, Co, Cu, Cr, Ni, Zn, Pb, SEE, U, Th, ... sehr genau, aber keine Spezies bestimmbar, nur Gesamtmenge

Inductively Coupled Plasma - Mass Spectroscopy

Die im Plasma entstehenden Ionen werden im Massenspektrometer nach ihrem Masse/Ladungsverhältnis aufgeteilt und sequentiell detektiert. Dies gechieht durch ein Magnetfeld, dass die Ionen unterschiedlich stark ablenkt. Sie werden mehr abgelenkt, je schwerer sie sind, und je stärker sie geladen sind. Sehr schnelles Verfahren um sehr viele Bestandteile gleichzeitig zu messen. Sehr niedrige Nachweisgrenzen, jedoch sehr teuer.

Quadrupol-MS: Die Ionen werden an vier geladenen Stangen vorbeigeleitet. Diese sind mit entgegengesetzen Wechselspannungen versehen. Die Ionen bewegen sich spiralförmigzwischen den Stäben hin und her, der Ladung folgend. Nur sehr spezifische M/L Verhältnisse erreichen das Ende, ohne an den Stäben hängenzubleiben. Die Spannungen werden sehr schnell geändert, um nacheinander alle Ionen durchzulassen.

Bild:

![[{192399DC-72FA-4127-9237-8D9007E886B1}.png]]

# Organische Analytik

Drei Schritte:

1. Aufkonzentration/Extraktion der organischen Stoffe
2. Trennung der organischen Substanzen
3. Detektion

## 1. Extraktion

1. Headspace: Erhitzen des Materials, Gas in den Detektor. Niedrige Siedepunkte werden genutzt. Bei wässrigen Proben logischerweise nur bis 100° nutzbar.
2. SPME: Solid Phase Microextraction: Ein unpolarer Faden wird in die Probe gehalten, er sorbiert minimale Mengen der unpolaren Inhaltsstoffe, welche dann abgelöste und analysiert werden können. Der Faden ist wiederverwendbar.
3. Fest-Flüssig-/Flüssig Flüssig-Extraktion: Extraktion durch ein organisches Lösungsmittel welches dann abgeschöpft werden kann. Die geeignete Wahl des Mittels ist essentiell.
4. Flüssig-Fest-Extraktion: Probe wird über ein festes Adsorbens wie Aktivkohle geleitet. Die sorbierten Stoffe sind schwer wieder vom Adsorbens zu entfernen, deswegen eher für Sanierung als für Analyse genutzt.

Typische Extraktionsmittel:
- Hexan/cyclohexan (unpolar)
- Benzol/Dichlormethan (mittelpolar)
- Ether und Alkohole (polar)
- - ...

Typisches Steup der Lösungsmittelextraktion: 

![[{D43300FD-B85E-4BB0-8D8F-27451C4B71CA}.png]]

Das Lösungsmittel ist im Kolben unten, die Probe in der Mitte.
Das Lösungmittel verdampft, kondensiert oben, tropft in die Probe und läuft dann durch den Überlauf mit den gelösten Stoffen wieder in den großen Kolben unten. Dort verdampft es wieder und lässt die gelösten Stoffe dabei unten zurück.

## 2. Trennung der Substanzen

Die Trennung der Substanzen erfolgt durch Chromatographie (vgl IC oben).

### Dünnschichtchromatographie

Probe wird auf mit Sorbens belegte Platte geleitet, mit Lösungsmittel nach unten gewaschen (Stoffe kommen unterschiedlich weit). Dann wird die Probe getrocknte und die einzelnen Plattenbereiche werden getrennt analysiert. Alte Methode mit schlechter Trennleistung, aber sehr einfach und Kostengünstig, eigentlich alles ist recyclingfähig.

Aufbau mit über die Platte aufsteigendem Lösungsmittel:

![[{300A3A58-638E-48AB-B159-7A6FD059E18D}.png]]

Vergleichbar mit dem Grundschulexperiment "Edding auf Kaffefilter mit Wasser beträufeln".

### Säulenchromatographie

Säule gefüllt mit Gemisch aus Lösungsmittel und Sorbens. Lösungsmittel mit Probe läuft durch. Einzelne Probenbestandteile erreichen nach ihren Eigenschaften sortiert das Ende der Säule nacheinander und können dann separat analysiert werden. Einfach und günstig, aber schlechte Trennwirkung, Quantifizierung kaum möglich. Die Analyse erfolgt oft über UV-/Lichtmesser aufgrund verschiedener Absorptionen der Stoffe in der Glassäule.

Aufbau: 

![[{C6C90232-8DB9-46C3-85AE-11C847FD4960}.png]]

### HPLC 

High Pressure Liquid Chromatography. Ähnlich wie Säulenchromatographie.
Die Säule wird jedoch unter hohen Druck gesetzt werden, es werden Stahlsäulen benutzt. Die Trennsäule kann zudem erhitzt werden. Die Stofftrennung ist erheblich verbessert, die Säule oft direkt mit einem Detektor (Leitfähigkeit oder UV-VIS) verbunden. Der aparative Aufwand wird dadurch deutlich erhöht.

Schema mit der Möglichkeit des Lösungsmittelgradienten:

![[{76ED54ED-5388-4F9B-B6E4-43E8E1790A4B}.png]]

Bild einer solchen Stahlsäule:

![[{86A7E6D3-4B21-4E89-9ECA-D7576288409F}.png]]

Beispiel eines Ergebnisses einer Photodioden-Array-Detektion:

![[{246B3C4B-9177-4066-B94D-F942BDB2B49C}.png]]

X-Achse ist die Zeit, Y die Wellenlänge, Z (aus dem Bild heraus) die Intensität/Menge.

### GC

Gaschromatographie. Die Probe wird verdampft und dann durch die Säule geleitet statt als Flüssigkeit. Verschiedene Gase werden als Trägergase genutzt. Die Säule wird erhitzt, um die Stoffe in der Gasphase zu halten. Sie ist innen belegt mit einer Sorbensschicht. Die Gaschromatographie trennt extrem effektiv auch bei sehr geringen Probenmengen, aber der aparative Aufwand ist sehr hoch, Kosten für Gase ebenso.

Schema:

![[{718464AD-626A-40EE-AC1E-E1A86CA9D4D7}.png]]

Die Säule kann extrem dünn und mehrere 10er-Meter lang sein.

## 3. Detektion

1. UV-VIS (Elektronenabsorptionspektroskopie, ähnlich wie AAS)
2. WLD (Wärmeleitfähigkeitdetektor des durchströmenden Gases, geringe Sensitivitä, aber günstig)
3. FID (Flammenionistaionsdetektor, ankommendes Gas wird verbrannt und Ionisiert, Elektrode detektiert Ionen)

# Grenzen

## Nachweisgrenze

Die Nachweisgrenze ist der kleinste Wert, der mit einer vorgegebenen Sicherheit vom Blindwert zu unterscheiden ist. Damit ist die Schwankung des Messignals bei Nullmessung oder Leermessung gemeint (dreifache Standardabweichung über dem Untergrundsignal.

## Bestimmungsgrenze

Ab der Bestimmungsgrenze können quantitative Werte mit einer festgelegten Präzision bestimmt werden (neunfache Standardabweichung über dem Untergrundsignal). Nach DIN liegt die Bestimmungsgrenze im Bereich der dreifachen Nachweisgrenze.

Überblick nach DIN:

![[{140A4C39-2113-4F5F-AC55-A8E1313E9C27}.png]]