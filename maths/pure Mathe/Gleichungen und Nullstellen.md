#Mathe 

### Äquivalenzumformungen

1. Addition oder Subtraktion einer beliebigen Zahl auf beiden Seiten
2. Multiplikation oder Division mit einer Zahl ($\neq 0$) auf beiden Seiten
3. Nulladdition: auf einer Seite etwas addieren und direkt wieder subtrahieren

Diese Äquivalenzumformungen lassen die Lösungsmenge der Gleichungen unverändert.

### Nullstellenproblem

Eine Seite der Gleichung ist gleich null. Für welche/wie viele x hat sie eine Lösung?
Jede Gleichung lässt sich in ein Nullstellenproblem umwandeln. 
$$
\displaylines{
0 = x^2+2x+3 \\
allgemein:0=x^2+px+q
}
$$
Nullstellenprobleme werden immer mit dem Leitkoeffizienten 1 betrachtet. Jedes [[Funktionen#Polynome]] lässt sich durch Division auf den Leitkoeffizient 1 bringen.

Lösungsansätze
1. einfache Äquivalenzumformungen (wenn p=0)
2. ausklammern von x (wenn q=0), dann Faktoren einzeln Nullsetzen
3. p-q-Formel (verallgemeinerte quadratische Ergänzung)
4. Quadratische Ergänzung (Nulladdition mit $(\frac{p}{2})^2$)

$$
\begin{align*}
0 =& x^2+1x-2 \\
0 =& (x^2+1x+(\frac{1}{2})^2)-(\frac{1}{2})^2)-2\text{ |binomische Formel} \\
0 =& (x+\frac{1}{2})^2 - \frac{9}{4}\text{|jetzt nur noch lösen}
\end{align*}
$$

Falls der Grad des Polynoms über drei ist, muss man mit Substitution oder Ausklammern tricksen, oder Polynomdivision anwenden.

### Polynomdivision

Verfahren, um mit einer bekannten Nullstelle den Grad des Polynoms so weit zu senken, dass die oben beschriebenen Lösungsverfahren anwendbar sind.

Dafür wird die Gleichung durch (x-p) geteilt, wobei p der x-Wert an der Nullstelle ist.

1. Monom höchsten Ranges durch x teilen und hinter das = schreiben
2. Diesen Wert mit (x-p) multiplizieren und das Ergebnis vom Polynom abziehen.
3. Diese zwei Schritte solange wiederholen, bis der Rang des größten Monoms im Polynom kleiner als der des größten Monoms im Teiler ist. 
4. Der Rest des Polynoms, der übrig bleibt, kann nicht weiter vereinfacht werden und muss als Bruch ins Ergebnis übernommen werden.

### Lineare Gleichungssysteme

#### Gauss Algorhithmus

Durch intelligentes verrechnen der Gleichungen das Gleichungssystem in dreiecksform bringen: nach unten immer weniger Variablen. Dann von unten nach oben auflösen.

#### Rang

Der Rang eines LGS ist die Anzahl der durchführbaren Eliminationsschritte mit dem Gauss-Algorithmus.


