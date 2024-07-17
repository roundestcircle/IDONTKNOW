#Geobotanik

## Definitionen

### Populationsbiologie

Wissenschaft, die sich mit der Anzahl der Individuen und ihrer zeitlichen und räumlichen Änderung befasst. Sie umfasst Populationsökologie und Populationsgenetik. Populationsökologie befasst sich mit den Wechselwirkungen der Populationen und ihrer Umwelt.

### Individuum

genetische Definition: Ein Individuum ist ein Produkt einer einzigen Zygote. Damit sind Klone als ein Individuum zu betrachten.

strukturelle Definition: Ein Individuum ist ein strukturell einheitlicher, physiolog. Selbstständiger Organismus sexueller (Genet) oder asexueller Herkunft (Ramet).

### Population

genetische Definition: Eine Population ist eine Gruppe von Organismen derselben Art, die ein begrenztes geographisches Gebiet besiedeln, so dass jeder Organismus sich potentiell it jedem anderen paaren kann.

strukturelle Definition: Eine Population ist eine Gruppe von Individuen, die der gleichen taxonomischen Einheit angehören und sowohl im gleichen Raum als auch im gleichen Zeitraum gemeinsam vorkommen.

#### Populationsgröße

Die Anzahl der diese Population aufbauenden Individuen. Kann als Dichte oder als absolute Zahl angegeben werden.

## Populationswachstum

Die grundlegende Gleichung der Populationsdynamik:

$N_{t+1}=N_t+B-D+I-E$

B: Births
D: Deaths
I: Immigration
E: Emigration

Oder zusammengefasst zur diskreten Wachstumsrate R:

$N_{t+1}=N_t\cdot R$
 
 Für mehrere Timesteps:

$N_{t}=N_0\cdot R^t$

Diskrete Wachstumsraten gelten für Populationen ohne Generationenmischung. t entspricht einer Generationsdauer.

Mischen sich die Generationen müssen [[Differentialgleichungen]] genutzt werden.

kontinuierliche Wachstumsrate r:

$r=ln(R)$

$\frac{dN}{dt} = rN$

R>1/r>0: Populationswachstum
R=1/r=0: konstante Populationsgröße
R<1/r<0: Populationsgröße geht gegen 0

Erweiterung mit der Dichteabhängigkeit, dafür wird die Tragekapazität K des Systems eingeführt, welche die maximal mögliche Individuenzahl darstellt.

$\frac{dN}{dt} = rN(1-N/K)$

Tendiert N gegen 0 gilt also:

$\frac{dN}{dt} = rN$, die Population wächst also exponentiell.

Tendiert N gegen K, so gilt: 

$\frac{dN}{dt} = 0$, die Population wächst nicht.

Umstellen der Differentialgleichung zur Bestimmung der Populationsgröße:

$N(t)=\frac{N_0e^{rt}}{1+N_0(e^{rt})/K}$

### Regulation der Populationsgröße

Die Populationsgröße kann durch dichteabhängige Faktoren, wie Ressourcenmangel, Konkurrenz und Pathogene limitiert werden, oder durch dichteunabhängige Faktoren wie Wetter oder Katastrophen.

#### r- und K-Strategen

K-Strategen: Angepasst an Bedingungen nahe Tragekapazität. Geringes Populationswachstum. Kommen an Standorten vor, an denen die Mortalität Dichteabhängig ist, also bei relativ konstanten/vorhersagbaren Bedingungen.

r-Strategen: Hohe Reproduktionsrate. Kommen an Standorten vor, an denen die Mortalität eher dichteunabhängig ist, also vor allem an Orten mit fluktuierenden oder unvorhersagbaren Bedingungen.

#### CSR-Strategietypen

![[Pasted image 20240717170511.png]]

Zu den C/K- (Competitors) und r/R-Strategen (Ruderals) kommen hier noch die Stress Tolerators S hinzu

Sie haben im Vergleich zu C- und R-Strategen weitaus geringere RGR (sh unten).

### Relative Wachstumsrate

Die relative Wachstumsrate RGR ist ähnlich zur Wachstumsrate (s.o.), betrachtet jedoch das Trockengewicht der Pflanzen statt der Individuenzahl.

$W(t_2)=W(t_1)e^{RGR(t_2-t_1)}$

$RGR= \frac{lnW(t_2)-lnW(t_1)}{t_2-t_1}$

Die Formeln gelten für die mittlere RGR über eine beliebig kleinen oder großen Zeitraum.

Experimentelle Ergebnisse: Die RGR von Gehölzen und Leguminosen ist unterdurchschnitllich, die von einjährigen überdurchschnittlich. Dies liegt vermutlich an der Versorgung von Symbionten und der energieintensiven Holzproduktion.

### Lebensstadien

Je nach Art, durchläuft eine Art verschiedene Lebensstadien, zum Beispiel seeds, seedlings, juvenile, immature, vegetative, generative, subsenile, senile. Weniger und andere Stadien sind möglich. Zwischen den Stadien lassen sich nun Übergangswahrscheinlichkeiten feststellen, zum Beispiel 15% der Juveniles treten pro Jahr über ins generative Stadium. Auch rückwärtige Übergangswahrscheinlichkeiten sind möglich.

Diese Übergangsstadien lassen sich als Matrix darstellen, mit einem Vektor der ursprünglichen Individuenzahlen multiplizieren um die Populationsentwicklung vorherzusagen.

Die Abfolge der verschiedenen Lebensstadien bezeichnet man als Lebenszyklus.

Iteropare Organismen reproduzieren sich mehrfach in ihrem Lebenszyklus, semelpare Organismen nur einmal.

### Fitness

Die Fitness ist der Fortpflanzungserfolg eines Genotyps, oft einfach an der Zahl der Nachkommen gemessen. Die Fitness eines einzelnen Individuum nimmt in großen Populationen ab (negative Dichte-Effekte), doch auch zu kleine Populationen senken die Fitness einzelner Individuen, zum Beispiel durch inbreeding depression, Anstieg der Homozygotie, erhöhter Fraßdruck, verringerter Bestäubungserfolg etc.

Oft gibt es einen gewissen Trade-off zwischen Reproduktion/fitness und generatitvem Wachstum, Semelpare Organismen stecken besonders viel Energie in die Fortpflanzung.