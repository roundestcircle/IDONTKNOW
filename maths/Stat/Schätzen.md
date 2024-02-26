#Stat #Schließend 

vgl. [[Deskriptiv vs Schließend]]

### Konfidenzintervall

$\mu = \bar{x} \pm z \cdot \frac{s}{\sqrt{n}}$

Diese Gleichung gibt die Ober-und Untergrenze des Konfidenzintervalls an. Dabei wird zunächst angenommen, dass $\mu$ und $\bar{x}$ identisch sind, und dann mit dem Stichprobenfehler und einem Wert z, der sich aus der gewünschten Wahrscheinlichkeit, dass der Wert innerhalb des Konfidenzintervalls liegt, ergibt.

#### Stichprobenfehler

Der Stichprobenfehler ist, wie abzulesen, kleiner, je größer die Stichprobe ist, und größer, je größer die [[Streuungsmaße#Standardabweichung|Standardabweichung]].

#### Z-Wert

Die [[Stichprobe]]nwerte sind idealerweise normalverteilt. Bestimmte Prozentsätze der Werte liegen also in Intervallen von:

1. 90%: $\pm$ 1.65 s
2. 95% $\pm$ 1.96 s
3. 99% $\pm$ 2.58 s

Beziehungsweise Einseitig:

1. 90%: +1.28 s
2. 95%: +1.65 s
3. 99%: +2.32 s

Spezielle Z-Werte lassen sich über qnorm herausfinden:
qnorm(P, 0, 1)
Achtung, hier wird immer nur die [[Wahrscheinlichkeit#Rechenbeispiel Unterschreitungswahrscheinlichkeit|Unterschreitungswahrscheinlichkeit]] berechnet, das heißt für ein beidseitiges Intervall muss die Wahrscheinlichkeit angepasstt werden!
Beispiel: 95% liegen im Intervall: qnorm(0.975, 0, 1) oder 50% liegen im Intervall: qnorm(0.75, 0, 1)

##### Irrtumswahrscheinlichkeit und Konfidenzniveau

Über die Auswahl des Z-Wertes legt man die Irrtumswahrscheinlichkeit fest: Wie wahrscheinlich soll es sein, dass der tatsächliche Wert außerhalb des Intervalls liegt? Das Konfidenzniveau bezeichnet dann die Wahrscheinlichkeit, dass der Wert innerhalb des Bereichs liegt.

#### Konfidenzintervalle für Anteile

$\pi = p \pm z \cdot \sqrt{\frac{p(1-p)}{n}}$

Aus der Gleichung lässt sich ableiten, dass das Konfidenzintervall bei einem Anteil von 50%/0.5 am größten ist. 

### Stichprobengröße berechnen

$n = \frac{z^2 \cdot (p(1-p))}{e^2}$

Da man den Anteil oft nicht kennt, wird 0,5 oft gewählt, da er sozusagen den Worst Case darstellt.  

e bezeichnet hier die gewünschte Größe des Konfidenzintervalls, zum Beispiel 0,05 für $\pm$ 5% Anteil. e liegt bei n=1000 und z=1,96 etwa bei 0.031. z ist der Z-Wert für das gewünschte Konfidenzniveau.

