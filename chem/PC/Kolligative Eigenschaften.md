#PC #Thermodynamik 

Gruppe:: Grundlagen

[[Phasengleichgewichte]]

## Definiton

Kolligative Eigenschaften treten in Mehrkomponentensystemen auf.
Kolligative Eigenschaften hängen ausschließlich von der Teilchenzahl der gemischten Stoffe ab. Chemische Interaktionen spielen keine Rolle.

Beispiele:
- Schmelzpunkterniedrigung von Wasser durch Salz.
- Siedepunktserhöhung
- Osmotischer Druck.

Eine Komponente ist immer im großen Überschuss vorhanden (Lösemittel), ein anderer weit weniger (gelöster Stoff). Das Lösemittel erhält Index 1, der gelösten Stoff Index 2.

## Chemisches Potential von Mischungen

[[Das chemische Potential#Chemisches Potential von Mischungen]]

in stark verdünnten Lösungen, in idealen Systemen gilt:

$\mu_i=\mu_i^\ast+RTln(x_i)$

Setzt man einen Molenbruch ein, stellt man fest, dass sich das chemische Potential allein durch die Anwesenheit des anderen Stoffes verringert. Chemische Interaktionen sind noch nicht beachtet.

## Siedepunktserhöhung

Herleitung übersprungen:

Annahmem:
1. p ist konstant
2. Dampfdruck des gelösten Stoffes ist vernachlässigbar klein

$T_S$ ist der Siedepunkt
$$
x_2=\frac{\Delta {}_VH_m}{R}(\frac{\Delta T_S}{(T_S^\ast)^2})
$$
bzw
$$
\Delta T_S=x_2 \frac{R(T_S^\ast)^2}{\Delta{}_VH_m}
$$
Dies ist eine sehr schöne Gleichung, die außer $x_2$ nur tabellierte Größen enthält.

Statt des Molenbruchs wird oft die Molalität aus praktischen Gründen genutzt. Die Molalität m ist die Stoffmenge n pro kg.

$$
\Delta T_S=m_2 \frac{R(T_S^\ast)^2\cdot M_1}{\Delta{}_VH_m}
$$
Oder einfach alle tabellierten Größen zur ebullioskopischen Konstante $K_b$ zusammengefasst:
$$
\Delta T_S=m_2\cdot K_b
$$

Daraus folgt, dass die ebullisokopische Konstante von den chemischen Eigenschaften des Lösemittels abhängt. Damit hängt auch $T_S$ von diesen ab. Aber remember: Die chemischen Eigenschaften des gelösten Stoffes spielen keine Rolle, einzig die Teilchenzahl.

[[Thermochemie#Phasenübergänge]]

Die Siedetemperatur erhöht sich immer, wenn ein weiterer Stoff hinzugefügt wird. Die Verdampfungsenthalpie ist immer positiv, es muss immer Energie zugeführt werden, um den Phasenübergang zu ermöglichen. 

## Gefrierpunktserniedrigung

Herleitung analog zu oben.

$\Delta T_G = T_G - T_G^\ast = (\frac{R(T_G^\ast)^2}{\Delta {}_GH_m})x_2=(\frac{R(T_G^\ast)^2 M_1}{\Delta {}_GH_m})m_2$

Zusammengefasst zu Kryoskopischer Konstante:

$\Delta T_G = K_f \cdot m_2$

Da $\Delta{}_GH_m$ immer negativ ist, wird der Gefrierpunkt immer erniedrigt.

## Gesamte Kolligative Effekte

Insgesamt wird durch kolligative Effekte allso die Bedingungsbreite, in der flüssiges Wasser vorliegt vergrößert.

## Osmose

Lösemittelfluss durch eine semipermeable Membran zum Ort der höheren Konzentrationen gelöster Stoffe.

Dies geschieht durch um den Ausgleich [[Das chemische Potential|chemischer Potentiale]] zu erreichen.

$\mu_1=\mu_1^\ast>\mu_2=\mu_1^\ast-RT\ln x_2$

Wasser fließt von $\mu_1$ nach $\mu_2$. Dadurch steigt $\mu_2$ an ($x_2$ sinkt), kann jedoch nie $\mu_1$ erreichen.

Den zusätzlichen Druck, den man dafür zum Außendruck dazu aufwenden muss, bezeichnet man als Osmotischen Druck $\Pi$. Um zu erklären, warum das funktioniert, muss gezeigt werden, dass $\mu$ druckabhängig ist.

[[Fundamentalgleichungen]]:

$d\mu =V_mdp-S_mdT$

Isotherm, Herleitung übersprungen:

$\Pi \cdot V_{m,1}^\ast=-RT\ln x_2$

Der osmotische Druck ist also eine Funktion von $x_2$. Je höher der Molenbruch, desto höher der osmotische Druck. Vergleiche auch oben die Potentialunterschiede.

Vereinfacht:

$\Pi V=n_{\text{gelöster Stoff}}RT$

Beachte die Ähnlichkeit zu [[Ideale Gase]]! Gelöste Teilchen verhalten sich in Lösemitteln wie Gasteilchen.