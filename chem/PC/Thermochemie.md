#PC #Thermodynamik 

## Ziele

Anwendung der [[1. Hauptsatz der TD]] auf physikalische Umwandlungen (Änderungen des Aggregatzustandes) und auf chemische Reaktionen. Quantifizierung der Umgesetzten Wärmemengen. Die Gesamtenthalpie spielt dabei keine Rolle, lediglich die Änderung der [[Enthalpie]].

## Standardbedingungen

Standardbedingungen erlauben die Vergleiche von Prozessen. Nur so kann die Messung von reaktiven Änderungen möglich sein.

Der Standardzustand eines Stoffs ist die Reinform (100%), in einem einphasigen Zustand. Für Gase ist der Standardzustand das ideale Gas.

Dementsprechend muss für Untersuchungen ein Gas möglichst nah an die Idealform gebracht werden. Dafür werden Gase mit sehr wenigen Teilchen genutzt, wodurch das Gas weniger Eigenvolumen und weniger Interaktionen aufweist.

Standarddruck:

$p^\stst=10^5Pa=1Bar$

Standardtemperatur:

$T^\stst=298,15K (25°C)$

Standardenthalpieänderung:

$\Delta H^\stst=H^\stst_{Ende}-H^\stst_{Anfang}$

In der Regel wird hier nur der Standarddruck angenommen, die Temperatur wird angegeben.

### Phasenübergänge

Schmelzenthalpie:

$\Delta {}_mH^\stst=H^\stst_{flüssig}-H^\stst_{fest}$

Das Vorsubskript m steht für melting.

Verdampfungsenthalpie:

$\Delta {}_vH^\stst=H^\stst_{gas}-H^\stst_{flüssig}$

Sublimationsenthalpie:

$\Delta {}_sH^\stst=H^\stst_{gas}-H^\stst_{fest}$

wenn dT=0: $\Delta {}_sH^\stst=\Delta {}_vH^\stst+\Delta {}_mH^\stst$

Die Enthalpieänderung beruht dann wirklich nur auf der Phasenänderung, es findet kein Temperaturanstieg statt! Trotzdem muss Energie/Enthalpie zugeführt werden, um den Phasenübergang durchzuführen. Die dafür benötigte Energie ist $\Delta H^\stst$.

Da H eine Zustandsgröße ist, sind die Standardenthalpien für die entgegengesetzten Prozesse identisch, nur mit negativem Vorzeichen. Das bedeutet dass das System dabei Enthalpie verliert/Energie abgibt.

### Standard-Reaktionsenthalpie

Der Aggregatzustand der Stoffe während der Reaktion muss beachtet werden. Die Standardreaktionsenthalpie bezieht sich immer auf eine spezifische Reaktionsgleichung. Je nach stöchiometrischen Faktoren kann so die gleiche Reaktion verschiedene Standardreaktionsenthalpien aufweisen.

Daher werden die stöchiometrischen Faktoren essentiell für die spätere Berechnung. Sie werden mit dem Formelzeichen $\nu$ gekennzeichnet. Produkte erhalten dabei ein positives Vorzeichen (Sie entstehen), Edukte ein negatives (sie verschwinden).

Im allgemeinen ist die Summe der stöchiometrischen Faktoren nicht 0. Die Molekülzahl ändert sich in der Regel im Laufe der Reaktion.

#### Standard-Bildungsenthalpie

(absolute) molare Enthalpie: $H^\stst_m(i)=\frac{H^\stst(i)}{n_i}$

Die molare Enthalpie kann angesehen werden als die Bildungsenthalpie der Stoffe aus den Elementen ($\Delta{}_f H^\stst_m$, f steht für Formation). Die reinen Elemente (falls es mehrere Modifikationen gibt die stabile) haben per Definition eine Bildungsenthalpie von 0. Diese Standardbildungsenthalpien der Stoffe sind oft tabelliert (bei Standardbedingungen).

Bildungsenthalpien können unter 0 liegen

molare Standardreaktionsenthalpie: $\Delta {}_RH^\stst=\sum \nu_iH^\stst_m(i)$,

also die Summe aller molaren Enthalpien verrechnet mit den stöchiometrischen Faktoren.

### Satz von Hess

Die Enthalpie ist eine Zustandsgröße. Der Weg ist dementsprechend irrelevant. Um unbekannte Enthalpien zu berechnen, kann man also zahlreiche Umwege über bekannte Reaktionen gehen, und muss sich nicht strikt an die Reaktion halten.

A -> B -> C statt A -> C.

Die Reaktionsfolge kann beliebig lang sein.

### Temperaturabhängigkeit der Standard-Reaktionsenthalpie

#### Kirchhoffsches Gesetz

In der Regel finden im Laufe der Reaktion Temperatur-Änderungen statt.

[[Enthalpie#Wärmekapazität]]

$(dH)_p (= (\delta Q)_p =(\frac{\partial H}{\partial T})_p dT) =CpdT$

Integrieren und umstellen:

$H_m^\stst(T_2)=H_m^\stst(T_1)\int_{T_1}^{T_2} C^\stst _{p,m} dT$

$T_1$ ist in der Regel die Standardtemperatur um die Berechnung zu ermöglichen. 

Dies ist jedoch die Formel für den Absolutwert, nicht die Standardreaktionsenthalpie. Mit dem Satz von Hess und den Standardbildungsenthalpen kann Abhilfe geschaffen werden.

$\Delta {}_R H_m^\stst(T_2)=\sum \nu_i\Delta {}_fH^\stst_{m,i}(T_1)+\int_{T_1}^{T_2}\sum \nu_i C^\stst _{p,m,i} dT$

In Worten: Die Standardreaktionsenthalpie einer Reaktion bei $T_2$ ist die Summe der Bildungenthalpien aller beteiligten Stoffe plus die Summe der Änderungen der Wärmekapazitäten bei konstantem Druck der beteiligten Stoffe.

In Reinform als Formel:

$\Delta {}_R H_m^\stst(T_2)=\Delta {}_RH^\stst_{m}(T_1)+\int_{T_1}^{T_2}\Delta {}_RC^\stst _{p,m} dT$

Aber Achtung beim integrieren:  $\Delta {}_RC^\stst _{p,m}$ (Summe der Wärmekapazitäten) kann Wärmeabhängig sein. Für Gase ist die Summe der Wärmekapazitäten grob konstant und verändert sich nicht mit der Temperatur. 

Daraus folgt:

$\Delta {}_R H_m^\stst(T_2)=\Delta {}_RH^\stst_{m}(T_1)+\Delta {}_RC^\stst _{p,m} (T_2-T_1)$

Wenn Wärmeabhängig:

