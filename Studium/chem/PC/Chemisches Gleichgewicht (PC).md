#PC #Thermodynamik 

Gruppe:: Thermodynamik

[[Gibbs und Helmholtz]]

[[Chemische Reaktionen#Chemisches Gleichgewicht]]

## Reaktionslaufzahl Ksi

$\Delta {}_RG$ ist ein Maß für das Fortschreiten einer Reaktion.

Es wird jetzt definiert als 

$\Delta {}_RG=(\frac{dG}{d\xi})_{p,T}$, wobei die Reaktionslaufzahl $\xi$ den Zeitpunkt im Reaktionsverlauf repräsentiert. Dieser wird definiert als die normierte Stoffmengenänderung:

$d\xi = \frac{dn_i}{\nu_i}$

Damit ist $\Delta {}_RG$ die Steigung einer Funktion im G-$\xi$-Diagramm.

Ist diese Steigung negativ, findet die Reaktion statt, ist sie positiv, findet sie nicht statt.

## Gleichgewichtsarten

1. Statisches Gleichgewicht: Geschlossenes System, weder makro- noch mikroskopische Veränderungen.
2. Dynamisches Gleichgewicht: Keine makroskopischen Änderungen, konstant gleich viele hin- und Rückreaktionen auf mikroskopischer Ebene.
3. Fließgleichgewichte: Zum Beispiel bei konstanter Zufuhr von Reaktanten. Vor allem in Produktionen genutzt. Zu- und Abtransport von Substanzen halten sich die Waage. Die Reaktion schreitet netto voran, bwohl sich die Zusammensetzung im Reaktor nicht ändert.

## Quantifizierung von Gleichgewichten

Herleitungsschritte übersprungen:

$\Delta {}_RG =\Delta{}_RG^\stst +RT\sum \nu_i \ln(x_i)$

Im Gleichgewicht dementsprechend ($\Delta {}_RG=0$):

$\Delta {}_RG^\stst =-RT\sum \nu_i \ln(x_i)$

Umformungen, [[Logarithmusgesetze, Potenzgesetze]]:

$e^{(- \frac {\Delta {}_RG^\stst}{RT})} = \prod x_i^{\nu_i}$

Das unbekannte Zeichen ist das Zeichen für Produkt, ähnlich wie das Summenzeichen.
Durch die Potenzierung landen die Edukte (negatives Vorzeichen de stöchiometrischen Koeffizienten) im Nenner und die Produkte im Zähler.

Diese Terme werden definiert als $K_C$, die Gleichgewichtskonstante. Sie ist Einheitenlos.

Entspricht dem [[Reaktionsgeschwindigkeit#Massenwirkungsgesetz]] aus der Schule:

$\frac{\prod x_i^{\nu_i}(Produkte)}{\prod x_i^{|\nu_i|}(Edukte)}=K_X$

Lässt sich auch umschreiben mit Partialdrücken statt $x_i$ ($\frac{p_i}{p^\stst}$). Ergebnis ist dann $K_p$.

Achtung: Die Gleichgewichtskonstanten sind p und T-Abhängig.

Beachte: Die Konstante ist größer, je höher der Anteil der Produkte im Gleichgewicht.

### pH-Wert

Der pH-Wert ist die Manifestation einer Gleichgewichtskonstante ([[Säure-Base-Reaktionen#pH-Wert]]).

Dazu wird eine neue Gleichgewichtskonstante eingeführt:

$K_W=K_X\cdot c^2_{\ce{H2O}}=c_{\ce{H3O+}} \cdot  c_{\ce{OH-}}$

Dies ist die Konstante der Eigendissoziation des Wassers. 

Bei reinem Wasser dementsprechend: $K_W= c^2_{\ce{H3O+}}$

Bei Standardbedingungen: $K_W= c^2_{\ce{H3O+}}=10^{-14}\frac{mol^2}{l^2}$

Also $c_{\ce{H3O+}}=10^{-7}\frac{mol}{l}$.

Die Iegendissoziation des Wassers ist jedoch Temperaturabhängig. Damit ist der pH-Wert am Neutralpunkt auch Temperaturabhängig!

![[{0D1682A3-69DC-4FAE-AB3A-AE61982DD912}.png]]

### Temperaturabhängigkeit von Kx

Ohne Herleitung:

$(\frac{\partial}{\partial T}\ln K_X(T))_p = \frac{\Delta{}_RH^\stst}{RT^2}$

Diese Gleichung beschreibt die sogenannte vant-Hoffsche Reaktionsisobare, also den Verlauf der Konstante bei konstantem Druck und wechselnder Temperatur. Achtung: Die Gleichung beschreibt die Ableitung dieser Funktion.

Darstellung der Ursprungsfuntion:

![[Pasted image 20240728125152.png]]

Vgl. [[Thermochemie#Standard-Reaktionsenthalpie]]

Wenn diese negativ ist (Hier im Bruch oben, entspricht negativer Steigung der Ursprungsfuntion/negativen Werten der Ableitung), ist die Reaktion endotherm, ist sie positiv ist die Reaktion exotherm.

Schlussfolgerung: Mit steigender Temperatur bei exothermen Prozessen sinkt $K_X$, also die Ausbeute verringert sich, bei endothermen Prozessen Andersrum. Bei Exothermen Prozessen verschiebt abkühlen das GG auf die Produktseite.