#Hydrochemie #Hydrogeologie

# Erfassung von Bohrungs- und Schichtdaten

## Din-Aufnahmebogen

Zwei verschiedene Beispielbögen:
![[{08F945D2-4162-4DA5-8B00-B08705C4F25C}.png]] 

Der Bogen muss nach jeder Bohrung ans Landesamt gehen.
Beachte die Felderbezeichnungen, die teilweise viel Raum zur Interpretation lassen, was eingetragen werden soll, und wie.

## Symbolschlüssel Geologie

Einheitlicher Symbolschlüssel, um geologische Daten zu kodieren. Dies verhindert ungenaue, verwirrende oder widersprüchliche Bezeichnungen, wie sie mit dem Papierbogen vorkommen, und eine einfachere Datenrecherche.

zu finden unter: https://nibis.lbeg.de/Symbolschluessel/

## Umsetzung als Software

- Schichtenerfassungsprogramm (sehr alt, erster Versuch)
- GGU
- Profiltec
- GeoDin

Alle diese Umsetzungen wandeln eingegebene Daten in korrekt kodierte Datensätze um. In der Regel handelt es sich um verschiedene, zu verknüpfende Tabellen. Die Zeilen, die zum gleichen Ort gehören werden über identische Ort-IDs identifiziert. Für Querys müssen daher immer Ort-Ids genutzt werden.

### GeoDin

- Shuttle: Kostenlos und unbegrenzt nutzbar, zur Datenaufnahme, Datensatz dann an Landesamt lieferbar. Mehrere Eingabemasken zur vereinfachten Dateneingabe sind vorhanden.
- GeoDin Kompakt, Standard, Professional, ...: ArcGis-Anbindung, Zeichen- und Druckfunktionen, Übernahmemmöglichkeit der Daten in andere Modellierungssysteme

Eingabemaske in GeoDin:

![[{9343F774-6C44-406F-AAA8-529C5ECB4447}.png]]

Schichtdateneditor in GeoDin:

![[{71F1A20D-679C-4E22-A25A-3398666CB020}.png]]

Angaben nach dem Symbolschlüssel in folgender Form:
Schichtunterkante/Stratigraphie/Petrographie/Genese/Farbe/Sonstiges
Auch die Zusatzangaben haben Vorschriften

Blick auf GeoDin-Tabellen in MS-Access (Datenbank):

![[{7AF24B61-B7C2-41E5-A33C-6D5C1CB81EA7}.png]]
![[{D99185C0-B94B-4BF3-9B26-D70BF7B5F348}.png]]

Bildliche Ausgabe der eingegebenen Daten einer Bohrung durch GeoDin:

![[{71935E09-AEFC-4EE2-A5E3-D7915E52F370}.png]]

Bildliche Ausgabe bei zusätzlichen Angaben zum Ausbau der Bohrung:

![[{0B02FCF4-819A-4319-BC56-2EC805E97165}.png]]

Bildliche Ausgabe als Profilschnitt mehrerer Bohrungen:

![[{7DA6C26F-596F-4553-AA0E-74F7647FA5AB}.png]]

# Erfassung von Analyseergebnissen

- Tabellenkalkulationsprogramme: Ermöglichen schnelle Berechnungen, Formatierungen, Diagramme, sind jedoch Größenbegrenzt (Tabellenblätter und Spalten haben Maximalzahl)
- Eigene kleine Datenbank: Keine Größenbegrenzung, schnelle Recherche, weniger Umrechnungsfunktionen
- Kombination/Schnittstelle der Beiden
- GeoDin: Gute Datenbanksysteme und Analysemöglichkeiten in Standarddiagrammen, jedoch teuer, schwierig zu verstehende Datenstruktur, schwierige Gis-Anbindung

Erfassung in GeoDin-Shuttle:

![[{7D66213C-0AC7-4F7C-B00F-0DE51224A09A}.png]]

![[{76FF19D4-1D47-4D8B-AE00-93176E4E3570}.png]]

![[{8D793044-4A7C-4EC5-9CA5-5225E97E42C4}.png]]