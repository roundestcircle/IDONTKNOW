#Hydrochemie #Hydrogeologie 

Die Aktivität ist das Maß der thermodynamisch wirksamen Konzentration eines Reaktionsteilnehmers oder Ions.

## Berechnung

Die molare Konzentration wird mit einem Aktivitätskoeffizienten f multipliziert, um die Aktivität zu erhalten. 

$a=f\cdot c$

Die Aktivitätskoeffizienten reiner Feststoffe und Flüssigkeiten liegen nahe 1. In höher konzentrierten Lösungen und Elektrolytlösungen liegen sie darunter, da sich die Ionen gegenseitig "aus dem Verkehr ziehen". Bei sehr hoch konzentrierten Lösungen können sie über 1 steigen, die Ionen wollen sozusagen unbedingt aus der Lösung ausreagieren. 
Wie stark sie dies tun, ist von ihrer Konzentration und Ladung, erfasst über die Ionenstärke I bestimmbar. Nicht geladene gelöste Moleküle werden nicht berücksichtigt.

Je nach Ionenstärke werden verschiedene Formeln zur Bestimmung der Aktivitätskoeffizienten genutzt:

$I<5\cdot 10^{-3} mol/l$: Debye-Hückel-Gleichung:
$log(f)=-A\cdot z_i^2\cdot \sqrt{I}$

$5\cdot 10^{-3}<I<0.1 mol/l$: modifizierte Debye-Hückel-Gleichung:
$log(f)=\frac{-A\cdot z_i^2\cdot \sqrt{I}}{1+a\cdot B\cdot \sqrt{I}}$

$0,1<I<0,5 mol/l$: Davis Gleichung:
$log(f)=-A\cdot z_i^2\cdot [\frac{\sqrt{I}}{1+\sqrt{I}}]-0,3\cot I$

a ist der Ionendurchmesser in Metern, A und B Temperaturabhängige Faktoren. Achtung: Der Ionendurchmesser ist nicht die eigentliche Ionengröße, sondern eher die Anzahl umgebender Moleküle. z ist die Wertigkeit.

Tabellierte Ionendurchmesser (Einheit $10^{-10}m$):

![[{7FCE8243-810E-4F79-8AA3-42560711192B}.png]]

Beispielwerte für A:

| °C  | A    |
| --- | ---- |
| 25  | .509 |
| 30  | .514 |
| 35  | .519 |
| 40  | .524 |
| 50  | .535 |
| 60  | .547 |
| 70  | .560 |

Vergleich der berechneten Werte verschiedener Formeln:

![[{12EE370A-3425-48B1-86D0-E9476219E2F5}.png]]

Bei höheren Ionenstärken werden weit komplexere Annäherungsverfahren genutzt.

## Berechnung der Ionenstärke

$I=0.5\cdot \sum c_iz_i^2$

Richtwerte:
Normal mineralisierte Süßwässer: 0,01 mol/l
hochmineralisierte Mineralwässer: 0,1 mol/l
Meerwasser: 1 mol/l