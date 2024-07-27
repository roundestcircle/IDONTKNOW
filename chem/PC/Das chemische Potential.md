#PC #Thermodynamik 

[[Gibbs und Helmholtz]]

## Ziele

Die Stoffmengen $n_i$ verändern sich im Laufe von Reaktionen. Eventuell ändert sich dadurch auch G. Führ dies irgendwann zu einem Ende der Reaktion? Wie lässt sich dieses Berechnen?

## Chemisches Potential

Jetzt neu, totales Differential mit der Stoffmenge:

$G=f(p,T,n_i)$

$dG=(\frac{\partial G}{\partial p})_{T,n}dp+(\frac{\partial G}{\partial T})_{P,n}dT+(\frac{\partial G}{\partial n})_{P,T}dT$

Die ersten zwei Differentiale sind schon beschrieben ([[Fundamentalgleichungen]]), das letzte noch nicht. 

Es wird chemisches Potential $\mu$ genannt.

$\mu_i=(\frac{\partial G}{\partial n_i})_{p,T}$



Das chemische Potential beschreibt die Fähigkeit eines Systems, bei Änderung der Zusammensetzung Arbeit zu verrichten. Erreicht es 0, kann keine weitere Arbeit verrichtet werden, die Reaktion stoppt.

Für reine Stoffe:

$\mu= G_m = \frac{G}{n}$

### Chemisches Potential von Mischungen

$dG=Vdp-SdT+\sum \mu_idn_i$

Im realen Labor sind dp und dT oft 0, also:

$(dG)_{p,T}=\sum \mu_idn_i$

Bei anderen Konstanten:

$\mu=(\frac{\partial H}{\partial n_i})_{p,S}$ ([[Enthalpie]])

$\mu=(\frac{\partial U}{\partial n})_{V,S}$ ([[1. Hauptsatz der TD]])

$\mu=(\frac{\partial A}{\partial n})_{V,T}$ ([[Gibbs und Helmholtz]])

## Konkretisierungen

1. Ideale Gasmischungen ([[Ideale Gase]]): 

bisher ohne $\mu$:

$dG = Vdp-SdT$

T konstant gehalten und ideale Gasgleichung eingesetzt:

$(dG)_T = \frac{nRT}{p} dp$

Integriert:

$(\Delta G)_T =nRT ln(\frac{p_1}{p_2})$

$p_1$ sei $p^\stst$, $\Delta G$ aufgeteilt in Anfangs- und Endzustand und die Gleichung umgestellt:

$G(p,T)=G(p^\stst,T)+nRT ln(\frac{p}{p^\stst})$

Diese Gleichung gilt sowohl für ein ideales Gas, als auch für alle Komponenten eines Gasgemischs. Dafür muss für p der Partialdruck eingesetzt werden (Molenbruch mal Gesamtdruck, [[Ideale Gase#Mischungen idealer Gase]]).

Die gesamte Gibbs-Energie ist dann die Summe aller partiellen Gibbs-Energien:

$G = \sum G_i = \sum G^\stst_i+n_iRT ln(\frac{p_i}{p^\stst})$

Wenn der Enddruck der Standarddruck ist (kürzt sich raus): 

$G = \sum G^\stst_i+n_iRT ln(x_i)$

Durch $\sum n_i$ teilen:

$\frac{G}{\sum n_i} = \mu^\stst_i+RT ln(\frac{p_i}{p^\stst})=\mu$

Beachte dass dies nun die Definition des gesamten chemischen Potentials ist. $\mu^\stst_i$ ist in der Regel tabelliert.

2. Ideale Lösungen

Ideale Lösungen sind idealen Gasen ähnlich. Es gibt keine WWs zwischen gelösten Teilchen und gelösten Teilchen und Lösungsmittel.

$c_i =\frac{n_i}{V}$, daraus folgt $x_i=\frac{c_i}{c_{ges}}$. Dies gilt nur, wenn alle Teilchen gleich aktiv sind.

Per Definition ist $c^\stst$ 1 mol pro Liter.

Jetzt analog zu oben:

$G = \sum G^\stst_i+n_iRT ln(\frac{c_i}{c^\stst})$

und:

$\frac{G}{\sum n_i} = \mu^\stst_i+RT ln(\frac{c_i}{c^\stst})=\mu$

3. Reale Lösungen

Die Aktivität realer Lösungen ist oft deutlich kleiner als idealerweise betrachtet. Die Reaktivität wird durch Interaktionen verringert. Also wird $x_i$ durch die Aktivität/aktive Konzentration $a_i$ ersetzt.

$a_i=f_i \cdot x_i$, wobei $f_i$ der sogenannte Aktivitätskoeffizient ist. Er liegt zwischen 1 und 0.

Einsetzen oben:

$\mu_i = \mu_i^\ast + RTln(a_i)$

Der Stern steht für den Reinstoff.
Das entspricht: ([[Logarithmusgesetze, Potenzgesetze]])

$\mu_i = \mu_i^\ast + RTln(f_i) + RTln(x_i)$

Das chemische Potenzial wird verringert durch $RTln(f_i)$, das immer kleiner als 0 ist.

4. Reale Gase

Analog zu realen Lösungen, aber statt Aktivität Fugazität mit Fugazitätskoeffizient $\phi$ verwendet.