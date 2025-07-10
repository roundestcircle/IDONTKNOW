#Stat #Geostat #Hydrochemie 

Zeitreihen sind Daten, die entsprechend ihrer zeitlichen Abfolge geordnet sind. Sie lassen sich auswerten im Bezug auf:

- Trendanteil
- Periodischen Anteil
- Autokorrelativen Anteil

Ablauf einer Zeitreihenanalyse:

![[{F4B61D11-7173-45DC-B9E7-DEB269DE6BEE} 1.png]]

Inhomogenitäten beziehen sich etwa auf Messposition oder Messgerätewechsel, Laborwechsel oä.

Beispielprojekt:

![[{178AB060-A27F-44B3-A7AB-5C336D042EF8}.png]]

a: Ursprungsmessung
b: identifizierte Trends und Periodizität
c: um Trends und Periodizität bereinigte Zeitreihe
d: um Autokorrelation bereinigte Messreihe

## Beispiele:

- Anthropogene Trends: 
	- Klimawandel
	- Nitratanstieg
- Anthropogene Periodizitäten
	- Streusalz (jährlich)
	- Nitrat (jährlich, Düngephase)
	- Wasserverbrauch (Badbenutzung morgens)


## Fast Fourier Transform

Alle Muster sind aus überlagerten Wellen aufgebaut. Man kann dadurch alle Schwingungen harmonischer Ordnungen (Wellenlänge 1/X der Gesamtlänge) über die Zeitreihe legen und die Signifikanz der Übereinstimmung überprüfen.

Beispiel als Wavelet (Niederschlagsreihe in Berlin):

![[{4C8F5529-577F-49DB-AEBA-39CCD19DF140}.png]]

Y-Achse Periodendauer in Monaten (log2), X-Achse die Zeitreihe. Rot sind signifikante Bereiche. 
Bei etwa Y=3,5 (2^3,5~12): oft signifkant, Jahreperiode. Bei 5,6 (3-5 Jahre): Oft signifikant, El Nino.
