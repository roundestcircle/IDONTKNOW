#Mathe 

### Differenzierbarkeit

Eine Funktion ist an einem bestimmten Punkt differenzierbar, falls ihre Ableitung existiert (also sh unten: Ableitung bilden für diesen Punkt, ist dies nicht möglich, ist die Funktion an diesem Punkt nicht differenzierbar).

### Ableitungen

Die Ableitung an einem Punkt ist die Steigung der Funktion an genau diesem Punkt. Berechnet wird diese sehr einfach mit dem Quotient von x und y an zwei Punkten, also Steigungsdreieck. Nun berechnet man den Grenzwert, wenn man den zweiten Punkt gegen den abzuleitenden Punkt laufen lässt, das Steigungsdreieck wird also immer kleiner. 

Die gesamte Ableitungsfunktion zeigt dementsprechend als Funktionswerte die Steigungen aller Punkte der Ursprungsfunktion. 

### Ableitungsregeln

Differenzierbarkeit wird vorausgesetzt.

1. Summenregel
2. Produktregel
3. Quotientenregel
4. Kettenregel

Allgemeines Ableiten:
$$
(x^n)'=nx^{n-1}
$$
Der konstante Faktor verändert sich dabei nicht. eine addierte Zahl fällt einfach weg.
Zudem (nicht abgeleitet, nur Rechenregel nach dem Ableiten):
$$
x^{-n}=\frac{1}{x^n}
$$

1. Summenregel
$$
(f(x)+g(x))'=(f(x))'+(g(x))'
$$
Gliedweises ableiten/differenzieren ist erlaubt.

2. Produktregel

$$
(f(x)\cdot g(x))'=f(x)' \cdot g(x)+f(x)\cdot g(x)'
$$

3. Quotientenregel

$$
f(x) = \frac{g(x)}{h(x)}\quad \rightarrow \quad f'(x)=\frac{h(x) \cdot g'(x) - g(x) \cdot h'(x)}{[h(x)]^2}
$$

4. Kettenregel
Genutzt für verkettete Funktionen, also zwei Abbildungen die nacheinander ausgeführt werden. In diesem Beispeil zuerst 2x+3 und dann der sinus von den Werten, die dabei entstehen. Äußere Ableitung Mal innere Ableitung!
$$
\begin{align*}
\text{verkettete Funktion: } f(x) =& \sin(2x+3)\\
\text{allgemeine Form: } f(g(x))' =& f'(g(x))\cdot g'(x)\\
\text{Beispiel: } ((sin(x)+1)^3) =& 3(sin(x)+1)\cdot cos(x)\\
(e^{-3x})' =& e^{-3x} \cdot (-3)
\end{align*}
$$

5. Kombinationen aus den Regeln (Produkt und Kettenregel)
Einfach die Produktregel anwenden, und für die einzelnen Glieder die Kettenregel.

### Ableitungen von trigonometrischen Funktionen

$$
\displaylines{
sin(x)' = -cos(x)\\
cos(x)' = sin(x)
}
$$