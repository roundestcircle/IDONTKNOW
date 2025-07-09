#Hydrogeologie 

# Der Darcy-Versuch

Henry Darcy wollte im 19. Jahrhunder herausfinden, wie groß Wasserfilter sein müssen, um einen gewissen Durchfluss zu ermöglichen. Dafür entwickelte er den folgenden Versuch:

![[{AE9F40AC-0027-43DC-AC95-B6DBA8C0BA3E}.png]]

# Das Darcy-Gesetz

Er stellte dabei fest, dass der Durchfluss/[[Hydrodynamik#Volumenstrom]] direkt proportional zum [[Grundwasserfluss#Hydraulischer Gradient]] und direkt poportional zur Querschnittsfläche des Filters war. Dazu führte er eine konstante ein, die sich aus den Materialeigenschaften des Filters ergab, um folgende Formel zu erstellen:

$$
Q=-KA\frac{\Delta h}{\Delta x}
$$

Aus dieser Formel ergibt sich, dass bei Gleichbleibendem Querschnitt und Volumenstrom K und gradh umgekehrt proportional sind, also je höher der Gradient, desto geringer muss K sein, und andersrum. FIndet man in der Landschaft einen steileren Gradienten als in der Umgebung, muss der Querschnitt oder K gesunken sein.  

## Durchlässigkeitsbeiwert

Hauptartikel: [[Hydraulische Durchlässigkeit]]

Gradient und Durchmesser waren im Versuch einstellbar, sodass K sich für verschiedene Materialien berechnen lässt. K hat die Einheit m/s, ist aber keine echte Geschwindigkeit. Die Einheit ergibt sich aus den anderen Einheiten der Formel. K bezeichnet man als Hydraulische Durchlässigkeit, hydraulische Leitfähigkeit oder Durchlässigkeitsbeiwert.

## Filtergeschwindigkeit

Nutzt man die Filtergeschwindigkeit q (Volumenstrom pro Fläche, m/s), vereinfacht sich die Formel noch etwas:

$$
\displaylines{
q=\frac{Q}{A} \\
q=-K\frac{\Delta h}{\Delta x}
}
$$

## Abstandsgeschwindigkeit

Da nur der Porenraum drainiert, und nicht die gesamte Querschnittsfläche, ist die Abstandsgeschwindigkeit v, also die mittlere reale Fließgeschwindigkeit signifikant höher.

[[Porosität#Porosität und Textur]]

$$
v=\frac{q}{n_e}=K\frac{gradh}{n_e}=\frac{Q}{An_e}
$$

Da das Wasser nicht gerade durch die Poren fließt, sondern oft "Umwege" gehen muss, ist tatsächliche mikroskopische Geschwindigkeit des Wassers noch höher. Diese sogenannte Bahnliniengeschwindigkeit wird jedoch praktisch nie verwendet.

## Gültigkeit des Darcy-Gesetzes

Das Darcy-Gesetz gilt in [[Grundwasser Basics#Grundwasserleiter]]n. Diese können homogen und inhomogen, isotrop und anisotrop, gesättigt odes ungesättigt sein. 

Vorraussetzungen für die Anwendbarkeit sind:
1. Laminarer Fluss
2. Mittlung auf einen Raum
3. keine Kompimierbarkeit des Fluids
4. keine sehr hohen Druckdifferenzen.

Für [[Aquifere#Kluftgrundwasserleiter]] (aufgrund hoher Geschwindigkeiten und damit 
oft turbulentem Fluss) und Geringleiter (da Oberflächenkräfte ([[Porosität#Adsorptions- und Kapillarwasser]] über die Schwerkraft dominieren) ist das Darcy-Gesetz weniger anwendbar.

### Reynolds-Number

[[Transport und Sedimentation#Flow Types]]

Das Darcy-Gesetz ist bei einer Reynolds-Zahl von unter 1 uneingeschränkt gültig, bis 10 eingeschränkt. Darüber ist es ungültig.

Reynolds-Zahl, bezogen auf einen Rohrdurchmesser d:

$$
R_e=\frac{\rho vd}{\eta}
$$

$\eta$ ist die dynamische Viskosität des Fluids.

