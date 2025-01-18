#Physik 

## Kräfte

Die Dynamik beschäftigt sich mit Kräften. Kräfte erkennt man an ihren Wirkungen. Die Wirkungen können statisch sein, wie bei Gleichgewichten und Federn, oder Dynamisch, bei Beschleunigung und Verzögerung von Körpern. Auch die Masseanziehung und versch. chemische Kräfte wie Oberflächenspannung zählen dazu.

Kräfte sind Vektoren.

# Newtonsche Axiome

## 1. Axiom

Ein kräftefreier Massepunkt in einem Inertialsystem verbleibt in Ruhe oder gleichförmig geradliniger Bewegung. Ein Initialsystem ist dabei ein ruhendes oder sich mit konstanter Geschwindigkeit bewegendes Fixsystem.

In der Praxis bremsen in der Regel Reibungskräfte die Bewegung ab.

## 2. Axiom

Die auf einen Massepunkt wirkende Kraft ist gleich dem Produkt aus Masse und Beschleunigung des Körpers.

$$
\vec{F}=m\vec{a}
$$

Kraft lässt sich auch als Ableitung des Impulses ($\vec{p}=m\vec{v}$) verstehen:

$$
\vec{F}=\dot{\vec{p}}=\dot{m}\vec{v}+m\dot{\vec{v}}
$$

[[Partielle Ableitungen und totales Differential]]

### Gravitation

Die Gravitationskraft ist eine Sonderform, mit der Erdbeschleunigung als a.

## 3. Axiom

Kräfte, die zwei Körper aufeinander ausüben sind betragsgleich aber in entgegengesetzter Richtung.

$$
\vec{F_1}=-\vec{F_2}=m_1\vec{a_1}
$$

# Kräfteparallelogramm

Die Gesamtkraft ergibt sich als Summe der wirkenden Kräfte. Diese lässt sich zum Beispiel über das Kräfteparallelogramm händisch bilden, dessen Diagonale die Gesamtkraft ist.

![[{D0F58F86-82ED-4E8E-A35B-2B58DD0A1995}.png]]

Kräfte lassen sich jedoch so nicht nur addieren, sondern auch in Teilkräfte zerlegen.

![[{C891C3EA-9985-43BF-9CFD-A95C033FD713}.png]]

In diesem Beispiel wurden die Kräfte zunächst zerlegt, und dann wieder addiert, um eine neue Gesamtkraft graphisch zu bestimmen.

### Schiefe Ebene

An einer schiefen Ebene lässt sicht die Gewichtskraft $\vec{F_G}$ in Hangabtriebskraft und Normalkraft zerlegen. Die Normalkraft drückt das Objekt auf die schiefe Ebene, die Hangabtriebskraft treibt es abwärts. Die Normalkraft wird durch die Gegenkraft der schiefen Ebene kompensiert. $\alpha$ ist der Neigungswinkel der Ebene, h die Höhe, l die Länge der Fahrbahn und b die horizontale Breite.

Normalkraft: $|F_N|=|F_G|\cos \alpha=|F_G|\frac{b}{l}$

Hangabtriebskraft: $|F_H|=|F_G|\sin \alpha=|F_G|\frac{h}{l}$

Bei einem Winkel von 30° ist der Sinus 0,5, die Hangabtriebskraft beträgt also genau die Hälfte der Gewichtskraft. Darüber ist ihr Anteil größer, darunter kleiner.

# Federkraft

Die Federkraft wirkt der Auslenkung durch die Gewichtskraft entgegen. Im GG sind Federkraft und Gewichtskraft dementsprechend identisch. Die Federkraft ist proportional zur Dehnung/Stauchung/Auslenkung z. k ist eine Federspezifische Federkonstante.

$$
\vec{F_E}=-kz
$$

# Reibungskräfte

Es gibt verschiedene Reibungskräfte, wie Haftreibung, Gleitreibung und Rollreibung. Um die Reibungskraft zu bestimmen, wird einfach die angelegte Kraft mit einer spezifischen Reibungszahl multipliziert. Die berechnete Reibungskraft geht im Prozess "verloren".

Die Haftreibungszahl (also die Reibung relativ zueinander ruhender Körper) von Stahl auf Stahl ist etwa 0,15, es gehen also etwa 15% der Kraft verloren. Fangen die Stoffe an zu gleiten, wirkt die Gleitreibungszahl, sie ist immer deutlich geringer als die Haftreibungszahl. Deswegen ist es etwa so schwierig, wieder Kontrolle über ein Auto zu gewinnen, das die Haftreibung verloren hat.

Der Rollwiderstand ist nochmal signifikant niedriger. Der Punkt des Rades der den Boden berührt, bewegt sich jdeoch relativ zum Boden nicht. Auf ihn wirkt die Haftreibungskraft, wenn Kräfte von außen auf das Rad einwirken.

# Beschleunigte Bezugssysteme

In beschleunigten Systemen wirken Trägheitskräfte. Diese werden nur vom mitbewegten Beobachter wahrgenommen. Sie sind sozusagen ein widersetzen gegen die Beschleunigung des Objekts.

$$
F_T=-ma
$$

Bewegt sich etwa ein Aufzug nach oben, wirkt diese Trägheitskraft zusammen mit der Gewichtskraft nach unten. Das momentane Gewicht eines Objekts ist dann die Addition aus der Gewichts- und der Trägheitskraft. 

# Kreisbewegung

[[Kinematik von Massepunkten#Radialbeschleunigung]]

In einer Kreisbewegung wirkt die Zentripetalkraft zum Mittelpunkt, um das Objekt auf der Kreisbahn zu halten.

$$
\vec{F_r}=m\vac{a_r}=-m\omega^2\vec{r}
$$

Die Zentrifugalkraft ist die Trägheitskraft im kreisförmigen System, die sich konstant der Radialbeschleunigung widersetzt. Sie hat den gleichen Betrag wie die Zentripetalkraft, wikt aber in die entgegengesetzte Richtung.

Die Trägheitskraft bewirkt auch andere Effekte, wie den [[Planetarische Zirkulation#Corioliseffekt]].