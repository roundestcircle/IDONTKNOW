#PC #Thermochemie

Gruppe:: Thermodynamik

## Ziele

Weniger Zwangsbedingungen (isox-Prozesse etc.). Es soll beschrieben werden, ob ein Prozess spontan stattfindet und wenn ja in welche Richtung.

## Reversible und irreversible Prozesse

[[Reversibilität]]

Irreversible Prozesse laufen spontan, selbstständig und in eine Richtung ab. Am Ende eines Irreversiblen Prozesses stellt sich ein Gleichgewicht ein.

## Entropie

### Statistische Entropiedefinition

Systeme wollen gerne alle Möglichkeiten ausprobieren, die ihnen zur Verfügung stehen.

Zahl der Mikrozustände: $\Omega$

Wahrscheinlichkeit, in einem Mikrozustand zu sein: $\frac{1}{\Omega}$

Die Zahl der Mikrozustände ist in der Regel unvorstellbar groß und wächst mit zunehmender Größe und Komplexität des Systems unfassbar schnell an.

Als grobe Vorstellung durchläuft jedes System alle möglichen Mikrozustände. Die Makrozustände, die mehr verschiedene Mikrozustände anbieten können sind ementsprechend wahrscheinlicher, als andere.

Besipiel Gasexpansion: Es gibt wahnsinnig viel mehr Mikrozustände, in denen die Gasteilchen etwa gleich verteilt sind, als solche, in denen sie alle an einem Ort sind. Die Wahrscheinlichkeit auf ungefähre Gleichverteilung ist damit sehr hoch. 

Die Triebkraft der Gasexpansion ist statistisch beschreibbar:

"Triebkraft" $\propto ln(\frac{\Omega_{Ende}}{\Omega_{Anfang}})$

Die Entropie wird demnach definiert als die Triebkraft eines spontanen Prozesses (was der Vergößerung der statistisch besetzbaren Möglichkeiten entspricht).

$S=k_B \cdot ln\Omega$, wobei $k_B$ die Boltzmann-Konstante ist.

$\Delta S= S_{Ende}-S_{Anfang}=k_B \cdot ln(\frac{\Omega_{Ende}}{\Omega_{Anfang}})$

### Thermodynamische Definition der Entropie

Für reversible Prozesse:

$dS=\frac{\delta Q_rev}{T}$

oder makroskopisch:

$\Delta S=\frac{Q_rev}{T}$

#### Clausiussche Ungleichung

Bei irreversiblen Prozessen ist die Entropie größer als $\frac{\delta Q_rev}{T}$.

Formal:

$dS \geq \frac{\delta Q_rev}{T}$, 

wobei = für reversible und > für irreversible Prozesse gilt.

Beispiel Gasexpansion: Die Energie für die Exploration kommt aus dem System (als Wärme). Sie ist dann nicht mehr nutzbar. 
Die Entropieänderung gibt dementsprechend an, wie viel Wärme prinzipiell nicht in Arbeit umgewandelt werden kann. Aus Oben ergibt sich: Bei reversiblen Prozessen ist mehr Energie als Arbeit nutzbar, als bei irreversiblen.

### Beispiel Konformationsentropie in Polymeren

Ungedehnter Naturkautschuk: Hohe Konformationsentropie, also viele Möglichkeiten der Positionen der einzelnen Polymere. Im gedehnten Zustand gibt es weit weniger Positionen, in denen sie liegen können, eigentlich liegen alle Polymere parallel nebeneinander. Die Rückstellkraft zurück in den ungedehnten Zustand ist proportional zum Entropieunterschied der zwei Zustände bzw zum Verhältnis der Mikrozustandanzahlen. 

### Entropie als Zustandsgröße

$dS=\frac{\delta Q_rev}{T}$

Kombiniert mit [[1. Hauptsatz der TD]], nur Volumenarbeit 
und [[Enthalpie]]:

$dH=TdS+Vdp$
H=f(S,p)

$dU=TdS-pdV$
U=f(S,V)

Da U,H,S Zustandsgrößen sind, gilt diese Gleichung auch für irreversible Prozesse.

### Temperaturabhängigkeit der Entropie

1. Isochor (V konstant)
[[1. Hauptsatz der TD#Differentialquotienten von U]]
$(\frac{\partial U}{\partial T})_{p,n,V}dT=C_v$,
daraus folgt: $(dU)_V=C_VdT$
außerdem: $dU=TdS-pdV$, pdV fällt weg da konstantes Volumen.
Gleichsetzen und umstellen: $(dS)_V=\frac{C_V}{T}dt$,
Entspricht: $(\frac {\partial S}{\partial T})_V=\frac{C_V}{T}$

2. Isobar
[[Enthalpie#Wärmekapazität]]
Analog zu oben: $(\frac {\partial S}{\partial T})_p=\frac{C_V}{T}$

Zu erkennen ist, dass $(\frac {\partial S}{\partial T})$, also die Änderung der Entropie mit der Temperatur, immer größer ist, je geringer die Temperatur.

#### Makroskopische Änderungen

$(dS)_p=\frac{C_p}{T}dT$

Integrieren und umstellen:

$S(T_2,p)=S(T_1,p)+ \int_{T_1}^{T_2}\frac{C_p}{T}dT$

Vereinfachung für ideale Gase (Wärmekapazität konstant):

$S(T_2,p)=S(T_1,p)+ C_p \int_{T_1}^{T_2}\frac{1}{T}dT$

Entspricht:

$S(T_1,p)+ C_p ln (\frac{T_2}{T_1})$

Falls $C_p4 nicht konstant ist, vergleiche Kirchhoffsches Gesetz ([[Thermochemie#Kirchhoffsches Gesetz]]):

$\Delta {}_R C_p^\stst = \sum \nu_i C_{p,i}^\stst(T)$