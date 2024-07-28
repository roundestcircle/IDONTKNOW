#Geobotanik 

![[Schema Typen der  Interaktion zwischen Pflanzen.png]]

Neutralismus ist wahrscheinlich sehr häufig aber schlecht untersucht. Konkurrenz ist die mit Abstand am besten untersuchte Interaktion (1000 mal mehr paper als Ammensalismus, Kommensalismus, Neutralismus, 6 mal mehr als Mutualismus). DIeses Ungleichgewicht prägt auch das wissenschaftliche Weltbild. Zu unrecht?

# ++

## Mutualismus

Wechselbeziehung zweier Organismen, aus der beide einen Nutzen ziehen, meist ohne dass sie direkt intergagieren.

Zum Beispiel Festlegung von mobilen Substraten, günstiges Bestandesklima etc.

## Symbiose

Enges Zusammenleben zweier Organismen von der Beide wenigstens zeitweise einen Nutzen haben.

Zum Beispiel Flechten, Stickstoffixierer, Mykorrhiza.

### Mykrrhiza-Typen

![[Schema Mykorrhiza Typen.png]]

VAM ist am weitesten verbreitet und tritt bei etwa 90% (!) der Pflanzenarten auf.

Effekte der Mykorrhiza auf Pflanzen:

1. Pilzhyphen erhöhen das zugängliche Bodenvolumen und dringen in Feinporen ein.
2. Schutz vor Phytopathogenen
3. Austausch von Assimilaten zwischen Pflanzen über Pilze schnell möglich.

Die Photosynthate werden in den Pilz, aber auch einfach in den Boden gepumpt, das ganze Bodenleben profitiert.

Evtl sind verschiedene Symbiosepartner an einer Pflanze vorhanden und werden manchmal in versch. [[Populationsökologie Pflanzen#Lebensstadien]] besonders benötigt. An einer Baumwurzel finden sich bis zu 50 Arten. Der genaue Nutzen ist noch weitgehen unerforscht.

### N2-Fixierung

Die Pflanze versorgt die Knöllchenbakterien mit Energie (bis zu 30% des gesamten Energieverbrauchs der Pflanze!) und Sauerstoff über Leghämoglobin. Dafür erhält ie NH4+ von der Bakterienknolle. Bis zu 100 kg pro Hektar und Jahr Stickstoffixierung ist möglich.

Die Wurzelwucherung, in der die Bakterien sich später einnisten, werden durch Gene des Bakteriums gesteuert und ausgelöst.

### RNE (Relativer Nachbar Effekt)

Über den relativen Nachbar-Effekt lassen sich unspezifische +/+-Interaktionen quantifizieren. Ist er positiv, wächst die Pflanze mit Nachbar besser, ist er negativ eher schlechter.

$RNE=\frac{P_{+N}-P_{-N}}{max({P_{+N},P_{-N}})}$

# 0+

## Kommensalismus

Beziehung zweier Arten, bei der ein Wirt unbeeinflusst bleibt und ein Kommensale einen Nutzen hat. Bekannte Beispiele sind Epiphyten.

# +-

## Parasitismus

Der Wirt wird geschädigt, während der Parasit einen Nutzen aus der Verbindung zieht. Parasiten können obligat (Xylem- und Phloem-Anschluss, Chlorophyllos) oder fakultativ (nur Xylem-Anschluss) sein.

## Antibiose

Eine Pflanze gewinnt, eine verliert, ohne dass sie direkten Kontakt haben, etwa durch das Ausscheiden von chemischen Verbindunge, die Konkurrenten verdrängen.

# 0-

## Ammensalismus

Amensalismus bezeichnet zum Beispiel extreme Konkurrenz, etwa wenn Löwenzahn im Wald wächst, was den Wald kaum stört, den Löwenzahn jedoch schon.

# -- 

## Konkurrenz

Wechselbeziehungen zweier Individuen, einer oder mehrerer Arten, in der sich die Individuen gegenseitig negativ beeinflussen.

Konkurrenz tritt auf wenn zwei Individuen die gleiche begrenzte Ressource nutzen wollen.

Bei symmetrischer Konkurrenz sind beide Individuen gleich betroffen, bei asymmetrischer Konkurrenz leidet ein Individuum stärker.

Konkurrenz kann zwischen Sprossen und/oder Wurzeln bestehen. Ihre Stärke wird bewertet über den relative Competition Index ($RCI=\frac{Biomass(Monokultur)-Biomass (Mischung)}{Biomass(Monokultur)}$, bei keinem Effekt also 0, bei totalem Verlust 1) oder lie log response ratio ($LRR=\ln(\frac{Biomass(Monokultur)}{Biomass(Mischung)}$)

### Selbstausdünnung

Mit zunehmender Dichte sinkt das Gewicht jeder Einzelpflanze.

$log(weight) = b \cdot log(density) + log(a)$

b, also die Steigung, hat relativ konstant den Wert -3/2 (power law of self thinning).

Dies ist in der Landwirtschaft als gesetz des konstanten Ertrags bekannt: Der Ertrag steigt nicht linear mit der Saatgutmenge sondern erreicht ein Plateau.

### Lotka-Volterra-Modell interspezifischer Konkurrenz

Erweiterung der [[Populationsökologie Pflanzen#Populationswachstum|Dichteabhängigen relativen Wachstumsgleichung]] mit dem Konkurrenz-Koeffizienten $\alpha$, der angibt, wie stark die interspezifische Konkurrenz im Vergleich zur intraspezifischen ist, in sogenannten Konkurrenzäquivalenten. Zum Beispiel 0.1: 10 Individuen der anderen Art haben den gleichen Effekt wie ein Individuum derselben Art. Damit ist es einfach wieder ein rein dichteabhängiger Regulierungsmechanismus.

$\frac{dN_1}{dt} = rN_1\frac{K_1-(N_1+\alpha _{12}N_2)}{K_1}$

Die Null-Isoklinen ($\frac{dN_1}{dt} =0$), geben an, wann die Populationsgröße unverändert bleibt.

Null-Isoklinen in Diagrammen: 

![[Schema eine Art im Lotka Volterra Modell.png]]

Zu sehen ist die Selbstausdünnung bzw das Populationswachstum je nach Populationsgrößen der zwei Arten. 

([[Differentialgleichungen]] als Vektorfelder!)

Kombination der Isoklinen für die beiden Arten:

![[Schema zwei Arten in Lotka Volterra Modell.png]]

Die Gleichgewichte sind nur in bestimmten seltenen Fällen möglich, in der Regel wird eine Art die andere verdrängen (a oder b). Bei noch mehr Arten sind Gleichgewichte fast unmöglich. 

#### Konkurrenz-Ausschluss-Prinzip

Zwei Arten mit den selben oder sehr ähnlichen ökologischen Ansprüchen können nicht koexistieren. Es setzt sich nach dem Lotka Volterra Modell immer die Art mit dem höheren Konkurrenz-Koeeffizienten durch. Ein höherer Konkurrenzkoeffizient kann erlangt werden durch:
- Höhere Vermehrung
- Efiizientere Ressourcennutzung
- Wirkungsvollere Verdrängungsmechanismen

Anders formuliert: ([[Standortfaktoren#Ökologische Nischen]], [[Definitionen Ökologie#Ökologische Nische]]) Arten mit der selben Fundamentalnische können nur koexistieren, wenn sie unterschiedliche realisierte Nischen haben ([[Standortfaktoren#Nischendifferenzierung]]).

Offensichtlich existieren jedoch verschiedene Arten mit gleichen realisierten Nischen an einem Ort. Zwei Erklärungen

1. Kleinräumige räumliche Heterogenität: Jedes Mikrohabitat durchläuft Verdrängungsprozesse wie oben, es gibt jedoch so viele, dass das Gesamtbild durchmischt bleibt. Beispiele sind etwa verschiedene Wurzeltiefen oder Mikrohabitate an verrottendem Windwurf.
2. Zeitliche Heterogenität: Störungen verhindern konstant, dass sich ein Gleichgewicht ausbilden kann, indem sich konstant die Standortbedingungen ständig ändern. Der Konkurrenzausschluss wird so nie erreicht.

##### Störungen 

Störungen sind alle externen Prozesse, die außerhalb der natürlichen Physiologie liegen, zu Mortalität führen und auf kleinen Zeitskalen ablaufen. Störungen können unterschiedlich intensiv, häufig und lang sein, nur bestimmte Arten oder ganze Systeme betreffen.

![[Schema zwei konkurrierende Arten mit Störungen.png]]

Beachte, dass sich je nach Störungsregime [[Populationsökologie Pflanzen#r- und K-Strategen]] durchsetzen.

Die Diversität eines Bestandes ist bei mittlerer Störungsintensität und -häufigkeit am höchsten (Intermediate Disturbance Hypothesis):

![[Schema Diversität in Abhängigkeit von Störung.png]]

### Dominante Arten

Betrachtet man den relativen Nachbar Effekt dominanter Arten (sh oben), stellt man fest, dass er auch bei dominanten Arten im adulten Stadium negaitv ist, also die Nachabrn der Pflanze schaden. Der einzige Moment, bei dem dominante ARten stärker sind als nicht dominante ist bei der Keimung trotz Nachbarn. Der relative Nachbareffekt bei der Keimung ist bei dominanten Arten positiv, bei schwächeren negativ.

### Konkurrenz und Produktivität

An produktiven Standorten spielt die Konkurrenz eine größere Rolle. K-Strategen sind im Vorteil ([[Populationsökologie Pflanzen#r- und K-Strategen]]). Konkurrenzschwache Arten werden dementsprechend eher auf die unproduktiven Standorte verdrängt ([[Standortfaktoren#Nischendifferenzierung]]).

Der Effekt geht sogar so weit dass bei Düngung die Artenzahl sinkt, da die Individuen größer und stärker werden, die Konkurrenzintensität steigt und dadurch schwache Arten verdrängt werden. Doch auch bei sehr geringer Produktivität überleben nur wenige Arten, da die Bedingungen starke Anpassungen benötigen. Daher geht man davon aus, dass die Artenzahl bei mittlerer Diversität am höchsten ist. Experimentell lässt sich diese Theorie jedoch kaum bestätigen. Frühe Bestätiigungen (hump-shaped-curve, Al Mufti) ließen sich nicht reproduzieren.

#### Artenreichtum als Funktion von Störung und Produktivität

![[Schema Diversität in Abhängigkeit von Produktivität und Störung.png]]

Diese Darstellung ist stark vereinfacht und trifft nicht immer zu.

Eine Umtriebs-Mähweide hat zum Beispiel hohe Störung und hohe Produktivität, jedoch eine geringe Artenzahl.