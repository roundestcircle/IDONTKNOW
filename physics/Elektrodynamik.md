#Physik 

[[Elektrostatik]]

## Strom 

Strom ist bewegte Ladung. 

### Stromstärke

Die Stromstärke I ist die transportierte Ladung pro Zeit.

$I=\frac{q}{t}$

Die Einheit der Stromstärke ist Ampere. 

### Stromrichtung

Die technische Stromrichtung ist definiert vom Plus zum Minuspol, also umgekehrt des tatsächlichen Elektronenflusses.

## Widerstand

Der Widerstand R ist die Reibung, die die Bewegung von Ladungsträgern behindert. Diese wird durch Zusammenstöße der Elektronen mit unbewegten Teilchen verursacht, wobei diese Energie als Wärme verlieren.

$R=\rho\frac{l}{A}$

A ist der Leiterquerschnitt, l die Leiterlänge und $\rho$ der spezifische Widerstand des Leitermaterials.

### Ohmsches Gesetz

$I=\frac{U}{R}$

Die Stromstärke ist also proportional zur anliegenden [[Elektrostatik#Potential/Spannung]].

## Arbeit im Gleichstromkreis

$W=UIt$

## Leistung im Gleichstromkreis

$P=UI=\frac{U^2}{R}=I^2R$

## Netzwerke

Komplexe Schaltungen werden durch Schaltbilder angegeben.

![[{80D54066-5239-4596-A255-7350F6D9439A}.png]]

### Kirchhoffsche Gesetze

1. Knotenregel: An jedem Knotenpunkt ist die Summe der zufließenden Stromstärken I gleich den abfließenden. ($\sum I_n=0$)
2. Maschenregel: In jedem Stromkreis/Masche ist die Summe aller Spannungsquellen gleich der Summe aller Spannungsabfälle in Bauteilen. ($\sum U_m=I_mR_m=0$)

Beispiele: 

1. Parallelschaltung von WIderständen:
Aus den obigen Gleichungen ergibt sich: $R=\frac{R_1R_2}{R_1+R_2}$
2. Reihenschaltung von Widerständen: $R=R_1+R_2$

## Stromleitung

1. Stromleitung im Vakuum: geladene Teilchen bewegen sich frei.
2. Stromleitung in Gasen: Elektronen bewegen sich, stoßen an Teilchen, welche Ionisiert werden und darauf selbst Elektronen abgeben. Durch Übergänge von Elektronen in den Hüllen kann dabei Licht entstehen. Leuchtstoffröhren funktionieren auf diese Art und Weise.

### Halbleiter

Halbleiter haben nur wenige frei bewgliche Elektronen. Wenn sich diese Elektronen bewegen, bleiben Löcher zurück (die ebenfalls frei beweglich sind). Durch den Einbau spezifischer Fremdatome (Dotierung) können verschiedene Gebiete kreiert werden: n-Gebiete mit einem Ladungsüberschuss, p-Gebiete mit einem Lochüberschuss.

Dort, wo sich die zwei Gebiete treffen, kommt es zum angsamen Konzentrationsausgleich durch Diffusion. Dadurch bildet sich ein elektrisches Feld E (Ableitung des Potentials $\Phi$), das eine weitere Difuusion verhindert.

![[{7F771831-AD21-444F-BE8A-053F6901F2C3}.png]]

#### Halbleiterdioden

Halbleiterdioden nutzen die zwei Gebiete, um nur in eine Richtung durchlässig zu sein. 

#### Transistoren

Transistoren nutzen drei unterschiedlich dotierte Schichten zur Signalverstärkung: Mithilfe von Emitter, Basis und Kollektor wird mit Halbleitern der Kollektorstrom verstärkt.

#### Solarzellen

Solarzellen sind ebenfalls Dioden. In ihnen wird ein Elektronen-Loch-Paar erzeugt, dass über das elektrische Feld zwischen n- und p getrennt wird. Wird diesem Paar nun ermöglicht, über ein Kabel wieder zueinander zu finden, fließt Strom.

## Induktion

Durch Veränderung des magnetischen Flusses ([[Magnetostatik]]) lässt sich ein elektrisches Fekld und eine Spannung erzeugen.

Die Spannung ist abhängig von der Änderung des magnetischen Flusses $\Phi$.

$U_{Ind}=-\frac{d\Phi}{dt}$

### Lenzsche Regel

Induzierter Strom baut ein Magnetfeld auf, dass dem äußeren entgegengesetzt ist. Er wirkt also der Ursache seiner Entstehung entgegen.

### Selbstinduktion

Fließt durch eine Leiterschleife ein zeitlich veränderlicher Strom, variiert damit das Magnetfeld und erzeugt eine Gegenspannung. L ist die Induktivität, eine Proportionalistätskonstante. sie steigt mit erhöhter Windungszahl, Querschnittsfläche und Permeablerem Kernmaterial, und sinkt mit der Länge des Leiters. 

$U_{Ind}=-L\frac{dI}{dt}$

### Generatoren

1. Eine Spule bewegt sich durch ein stationäres Magnetfeld, Spannung wird induziert.
2. Ein sich drehendes Magnetfeld erzeugt in einer stationären Spule eine Spannung.

### Transformatoren

Zwei Spulen in einem Magnetfeld: Wechselstrom in einer Spule erzeugt Spannung in der anderen. Der Spannungsunterschied entspricht dann genau dem Verhältnis der Windungszahlen der zwei Spulen. So kann jede beliebige Spannung erzeugt werden. Ist die Windungszahl sehr gering, sinkt die Spannung stark, dadurch steigt jedoch die Stromstärke stark an (Ohmsches Gesetz).
