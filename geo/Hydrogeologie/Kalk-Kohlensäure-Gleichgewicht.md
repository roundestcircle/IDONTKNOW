#Hydrogeologie #Boden

[[Säure-Base-Reaktionen]], [[Reaktionsgeschwindigkeit#Massenwirkungsgesetz]]
[[Chemisches Gleichgewicht (PC)]]

## Lösung von CO2 in Wasser

### Freie/Zusammengesetzte Kohlensäure

Gelöste Kohlensäure ist analytisch schwer bestimmbar. Daher Definition der besser bestimmbaren freien Kohlensäure:

$\ce{H2CO3° = H2CO3(aq) + CO2(aq)}$

### Lösungsprozess

[[Wasser als Lösungmittel#Gaslösung]]

1. Schritt: Gaslösung nach dem Henry-Gesetz
Da die Partialdrücke von CO2 (auch im Boden, 100fach höherer Partialdruck als in der Luft, immer noch nur 0,04 Bar) nicht allzu hoch sind, wird darüber eigentlich nie Übersättigung erreicht. Mikroorganismen im Wasser können die CO2-Menge über den durch den Partialdruck möglichen Wert erhöhen.
2. Schritt: Reaktion mit Wasser zu gelöster Kohlensäure
$\ce{CO2(aq) +H2O <-> H2CO3(aq)}$
Die Gleichgewichtskonstante K (Produkt- durch Eduktkonz.) ist $K_0=2.6\cdot 10^{-3}$ bei 25°C, also sehr gering. Sie ist wie alle GG-Konstanten temp-abh. Es wird nur wenig umgesetzt.
3. Schritt: Dissoziation der Kohlensäure, Hydrogenkarbonatbildung
$\ce{H2CO3(aq) + H2O <-> HCO3- + H3O+}$
$K_{true}=10^{-3,8}$

Schritt zwei und drei Zusammengenommen, scheinbare Dissoziation der freien Kohlensäure:
$\ce{H2CO3° + H2O <-> HCO3- + H3O+}$, entspricht grob
$\ce{CO2 + H2O <-> HCO3- + H3O+}$, da H2CO3-Konz sehr gering.
$K_1=10^{-6,36}$

Übersicht:

![[{AD6D3383-5351-4BEA-AB2A-7FF32AB0A578}.png]]

4. Schritt: Dissoziation zum Carbonat Ion 
$\ce{HCO3- + H2O <-> CO3^2- + H3O+}$
$K_2=10^{-10,33}$

### pH-Abhängigkeit

Beachte, dass K fast immer die Protonenkonzentration miteinbezieht (als H3O+). Diese stehen auf der Produktseite. Mehr Protonen verschieben das Gleichgewicht also auf die Eduktseite. Über umstellen der Gleichungen für K und die Gesamtkonzentration lassen sich folgende Gleichungen aufstellen:

![[{B262444A-4BB7-4CA9-927B-3AB96F122054}.png]]

In ein Diagramm geplottet ergibt sich folgendes Bild:

![[{97615424-ADDC-42DF-8DF0-14437102E09C}.png]]

Bei etwa pH 8,2 befindet sich also fast nur Hydrogencarbonat im Wasser, unter 4,3 nur CO2, über 12 nur Carbonat.

Bei pH 6,36 (=pK1!) gibt es gleich viel CO2 und Hydrogencarbonat, Bei pH 10,33 (=pK2!) gleich viel Carbonat und Hydrogencarbonat.

#### Titration

Man kann mit Säure bis zum pH 4,3 titrieren, also bis alles Hydrogencarbonat weg ist. Damit wird die Alkalinitität, also der Carbonatpuffer ([[Puffersysteme im Boden]]) oder die Carbonathärte bestimmt. Das Ergebnis wird auch als m-Wert bezeichnet. Der m-Wert ist die molare Konz. der zugefügten Säure also auch die molare Konz. des Hydrogencarbonats (mmol/l). Vorraussetzung dafür ist, dass nur der Carbonatpuffer aktiv ist. Die exakte Bestimmung von Hydrogencarbonat geht nur bei pH <8,2. Darüber werden auch andere Spezies erfasst. Der sich ergebende Wert wird auch darüber als Alkalinität bezeichnet.

Theoretisch kann man auch mit einer Base bis pH 8,2 titrieren, um die Menge an gelösten CO2  zu bestimmen. Das Ergebnis ist die sogenannte Acidität, auch als p-Wert bezeichnet.

Beispiele verschieden hoher Aciditäten/Basenpuffer in Tagebaurestlöchern:

![[{00516A66-C554-4968-9193-0F98C0490006}.png]]

Berechnung der Hydrogencarbonatkonzentration bei Säuretitration:

m-Wert = [HCO3-] = Titrationsvolumen * Molare Konz. der Säure / Probenvolumen

## Kalk-Kohlensäure-Gleichgewicht

Wird CO2, Wasser und Kalk gleichzeitig betrachtet, ergibt sich folgende Reaktion: 

$\ce{CaCO3 +H2O + CO2 <-> Ca^2+ + 2HCO3-}$

Die Gleichung setzt sich zusammen aus den oben beschriebenen Gleichungen zur CO2-Lösung und 

$\ce{CaCO3 <-> CA^2+ +CO3^2-}$
$K_L= 10^{-8,48}$ (entspricht LP, [[Wasser als Lösungmittel#Löslichkeitsprodukt]]).

Die bei der Carbonatlösung entstehenden Carbonat-Ionen dienen also gewissermaßen als Akzeptor für die bie der Kohlensäurebildung anfallenden Elektronen. Dadurch verhindern sie ein zu starkes absinken des pH-Werts. Die Kalklösung ist also vom CO2 und der Temperatur abhängig (Eduktseite).

Es kann also zu Ausfällungen kommen, wenn CO2 aus dem Wasser austritt, etwa aufgrund von Temperaturerhöhung oder durch die Entfernung von CO2 durch Pflanzen.

Mit den verschiedenen Gleichgewichtskoeffizienten ergibt sich nach Umstellung folgende Formel:

$\ce{CO2(aq)}=\frac{K_2}{K_L K_1}\cdot [\ce{HCO3-}]^2 [\ce{Ca^2+}$]

Die verschiedenen Koeffizienten können zur Temperaturabhängigen Tillmanns-Konstante zusammengefasst werden:

$\ce{CO2(aq)}=K_T\cdot [\ce{HCO3-}]^2 [\ce{Ca^2+}$]

Werte:

| t   | lg $K_T$ |
| --- | -------- |
| 5   | 4,388    |
| 10  | 1,405    |
| 15  | 4,431    |
| 20  | 4,466    |
| 25  | 4,508    |
| 30  | 4,558    |

## Wasserhärte

Die Wasserhärte beschreibt die Konzentration von Mg un Ca-Ionen im Wasser.

$°dH =\frac{(CaO+1,4MgO)[mg/l]}{10}$
oder
$°dH=(\ce{Ca^2+ +Mg^2+})[mmoleq/l]\cdot 2,8$

Lässt sich auch in Karbonathärte und Nichtkarbonathärte zerlegen.

Bereiche:

![[{A6B8AFDF-DD18-4A36-A819-AEA370E5E8CF}.png]]

## Mischungskorrosion

Wenn sich zwei Wässer mischen, kommt es zur Mischungskorrosion, da die Mischung immer untersättigt ist. Dies liegt am Verlauf der Kohlensäure zu Hydrogencarbonat-Verhältnisse.

![[{7DB8F63E-D358-44AB-AEC4-1A2376DD9E0B}.png]]

## Karbonatlöslichkeit in Böden

Die Karbonatlöslichkeit ist maßgeblich vom CO2-Gehalt des Wassers abhängig. Mit zunehmender Temperatur sinkt die Löslichkeit von CO2 und damit auch die Löslichkeit von Kalk. Andere Salze lösen sich mit zunhemender Temperatur besser. Der CO2-Gehalt des Bodenwassers und der Bodenluft wird durch Mikrobenaktivität bestimmt. Da diese in warmen Regionen vermehrt aktiv sind, werden die Temperaturbedingten Änderungen der Löslichkeit durch einen erhöhten CO2-Partialdruck ausgeglichen. 