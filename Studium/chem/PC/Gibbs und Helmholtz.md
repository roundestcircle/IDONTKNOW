#PC #Thermodynamik 

Gruppe:: Thermodynamik

vgl [[Gibbs-Energie]]

## Ziele

Prozesse wollen das Energieniveau senken und die Entropie erhöhen. U und H sollen in einem spontanen Prozess also sinken, während S in einem spontanen Prozess steigt. Was passiert nun, wenn sich diese Größen widersprechen? Läuft der Prozess dann ab oder nicht?

Dafür gibt es nun die Schiedsrichtergrößen A und G.

## Helmholtz-Energie A

Auch bezeichnet als freie Energie.

[[1. Hauptsatz der TD]]

$A=U-TS$

Wie oben beschrieben: U und H sind bei spontanem Ablauf negativ, S positiv. Sowohl A als auch G sind damit bei spontanem Ablauf insgesamt negativ. 

Zu beachten ist auch, dass die Entropie bei sehr niedrigen Temperaturen keine Rolle spielt.

A ist der Teil der inneren Energie U der zur Umwandlung in Arbeit zur Verfügung steht und nicht in Entropie umgewandelt wird.

Differentielle Betrachtung:

$dA = dU - d(TS) = dU -TdS - SdT$

Isotherm dementsprechend:

$dA = dU - TdS$

Also: Wenn TdS größer als dU ist, läuft der Prozess spontan ab (wenn T und V konstant sind).

Dies ist aus der Gleichung ersichtlich, lässt sich jedoch auch über die [[Entropie#Clausiussche Ungleichung]] herleiten.

### A-n-Diagramm

Im Laufe einer Reaktion ändern sich die Stoffmengen. In einem A-n-Diagramm abgetragen, ist die Steigung der Kurve $\frac{dA}{dn_i}$. Ist diese negativ, läuft die Reaktion ab. Die Reaktion endet am Tiefpunkt der Kurve. Hier liegt ein Gleichgewicht vor.

[[Chemische Reaktionen#Chemisches Gleichgewicht]]
[[Chemisches Gleichgewicht (PC)]]

$\Delta A$ ist damit bei T, V konst. das Kriterium für spontan ablaufende Prozesse. Da die Volumenkonstanz selten ist, wird sie weniger verwendet als G.

## Gibbs-Energie G

Auch bezeichnet als freie Enthalpie.

[[Enthalpie]]

$G=H-TS$

G ist der Teil der Entropie H der zur Umwandlung in Arbeit zur Verfügung steht und nicht in Entropie umgewandelt wird. G kann keine Volumenarbeit sein.

Analog zu oben, isotherme Betrachtung:

$dG = dH - TdS$

$(dG)_{T,p} \leq 0$ ist die Bedingung für einen spontan ablaufenden Prozess. Spontan ablaufende Prozesse werden auch exergonisch genannt, nicht spontan ablaufende Prozesse ($(dG)_{T,p} > 0$) endergonisch.

Ist $\Delta {}_RG$ gleich 0, befindet sich das System im Gleichgewicht.

Also: Wenn TdS größer als dH ist, läuft der Prozess spontan ab (wenn T und p konstant sind).

Endotherme Prozesse ($\Delta H > 0) können also trotzdem ablaufen, wenn der Entropiegewinn überwiegt. Solche Prozesse werden als Entropiegetrieben bezeichnet.

### Standard-Reaktions-Gibbs-Enthalpie

$\Delta {}_RG^\stst=\Delta {}_RH^\stst-T\Delta {}_RS^\stst$

Das Rechnen verläuft hier analog zur [[Thermochemie#Standard-Reaktionsenthalpie]]. Satz von Hess und Kirchhoffsches Gesetz gelten auch. Tabellierte Standard-Bildungs-Gibbs-Energien sind vorhanden.

$\Delta {}_RG^\stst=\sum \nu_i \Delta {}_fG_i^\stst$

