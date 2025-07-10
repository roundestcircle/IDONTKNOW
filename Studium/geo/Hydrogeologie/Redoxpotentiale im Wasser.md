#Hydrochemie #Hydrogeologie 

Viele Redoxreaktionen im Wasser laufen unter Protonenbeteiligung ab, verändern also den pH-Wert.

## Berechnung

Das Redoxpotential des Wassers ist ein Mischwert der [[Redoxpotential]]e aller Inhaltsstoffe. Es lässt sich mit der Nernstschen Gleichung beschreiben:

$E_h = E_0 + \frac{RT}{nF}\cdot ln\frac{[ox]}{[red]}$
oder
$E_h = E_0 +2,3\cdot \frac{RT}{nF}\cdot log\frac{[ox]}{[red]}$

R ist die Gaskonstante, n die Zahl der umgesetzten Elektronen, F die Faradaykonstante, ox die [[Aktivität]]skonzentration der oxidierten Form des Stoffes, red die der reduzierten Form. Achtung, hier geht es nicht um alle Reaktionspartner, sondern nur um die reduzierten/oxidierten. $E_0$ ist ein Reaktions- und pH-abhängiges Standardpotential.

$2,3 \cdot \frac{RT}{F}$ heißt Nernst-Spannung. Bei 25° beträgt er etwa 0,059V.

Daraus folgt bei Standardbedingungen:

$E_h = E_0 + \frac{0.059}{n}\cdot log\frac{[ox]}{[red]}$

### Beispiel Reduktion von Eisenhydroxid

$\ce{Fe(OH)3 +3H+ +e- <-> Fe^2+ + 3 H2O}$

$E_h = 0,944 + \frac{0.059}{1}\cdot log\frac{[H^+]^3}{[Fe^{2+}]}$

$K=10^{16}= \frac{[Fe^{2+}]}{[H^+]^3[e^-]}$

Bestimmung der Eisenionenkonz durch Messung, Bestimmung der Protonenkonz durch pH-Wert, dann Berechnung. Beachte: Der Logarithmus der Protonenkonz entspricht dem negativen pH. Beachte auch [[Logarithmusgesetze, Potenzgesetze#Logarithmusgesetze|Logarithmusgesetze zur Berechnung von Brüchen]].

Stabilitätsdiagramm Eisen:

![[{6B22A9F6-E348-4598-BA90-84B1507EEDDD}.png]]

Eisen ist im Zweifel gelöst. Am Wasserhahn erhöht sich das Redoxpotential, also die Fähigkeit Elektronen aufzunehmen durch Sauerstoffkontakt. Es kann zur Ausfällung kommen.

### Beispiel Mangan-Reduktion

Analog zu oben, aber diesmal vier Protonen und zwei Elektronen beteiligt, also Exponenten ändern und bei n aufpassen.

Stabilitätsdiagramm Mangan:

![[{B5DDB42C-B31E-4A60-AAA2-5D6BBFC8489D}.png]]

## Redoxintensität

Die Redoxintensität ist $pe = -log[e^-]$, analog zum pH-Wert. 

$pe = \frac{1}{n}log K -\frac{1}{n}log \frac{[red]}{[ox]}$
oder
$pe = \frac{1}{n}log K +\frac{1}{n}log \frac{[ox]}{[red]}$

Es gilt zudem:

$pe_0 =\frac{1}{n}log K$

Daraus folgt:

$pe = pe_0 + \frac{1}{n}\cdot log\frac{[ox]}{[red]}$

Vergleiche mit Eh:

$Eh=pe\cdot 0,059$!

Ausgewählte Redoxintensitäten für n=1

![[{3A3DA709-AF44-4AFD-84F9-4FAD6906AA6B}.png]]

Je höher die Werte, desto aktiver die Elektronen, also desto schneller werden sie abgegeben und übertragen. Die Produktion von Zucker ist negativ. Es ist also Energie nötig, um die Elektronen zu übertragen. In Pflanzen dient dazu die Sonne (Photosynthese).

Als Redoxpotential umgerechnet: hohe Werte wollen Elektronen gerne aufnehmen, niderige würden sie lieber abgeben ([[Redoxpotential]])/können sie nur erschwert aufnehmen.

## Stabilitätsfeld-Diagramme

![[{5A5717FC-4440-492B-A468-113E181227B7}.png]]

siehe auch oben bei den Beispielreaktionen und [[Schwermetalle im Wasser#pH-Eh-Diagramme]]. Die Diagramme geben keine Aufschluss über Geschwindigkeiten der Umwandlung. Im Gw können Spezies außerhalb der Stabilitätsfelder erfasst werden, wenn Eh Messung ungenau, Stabilitätsdiagramm nicht alle Spezies umfassend ist, oder kein GG vorliegt etwa durch schnellen Tranport in verschiedene Redox-Zonen.

## Umweltrelevante Redoxprozesse

- Oxidation von Eisen-2 durch Sauerstoff und Entstehung von [[Goethit]]. Dabei werden Protonen frei. Vgl [[Verwitterung#Oxidationsverwitterung]]
- Pyritoxidation zu Schwefelsäure und Goethit, extrem sauer
- (De)Nitrifikation ([[Stickstoffkreislauf]])

#### Beispiele Mikrobielle Redoxreaktionen

Bakterien spielen bei Redoxprozessen eine wesentliche Rolle. Es gibt kaum unbelebte Zonen auf der Erde. Bakterien reduzieren mithilfe organischen Materials verschiedene Partner. Am besten geht dies mit Sauerstoff, doch auch andere Partner sind denkbar. Es werden also unter Energiegewinn Elektronen auf neue Partner übertragen ([[Redoxpotential#Redoxreihe]]).

Theoretische Abfolge mit sinkendem Redoxpotentials, also zunehmender Schwierigkeit die Elektronen loszuwerden:

![[{C0F170FD-9D85-4DE1-A87D-D5735AFAA4AE}.png]]

Beispielhafte Prozesse währenddessen:

![[{897EFB2D-DAD2-420F-A99C-3A891ECCF8AF}.png]]

#### Beispiel Nitratauswaschung

Nitrat sollte reduziert werden, um es an der Ausspülung zu hindern. Dafür kann zum Beispiel über Kohlenstoffeintrag un die darauf folgende Atmung durch Mikroorganismen ein reduzierendes Milieu geschaffen werden.

#### Beispiel Rollfront

