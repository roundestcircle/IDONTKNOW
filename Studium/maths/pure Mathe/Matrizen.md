#Mathe 

### Matrixmultiplikation

Für die Matrixmultiplikation müssen Spaltenzahl der ersten Matrix und Zeilenzahl der zweiten Matrix übereinstimmen. Es entsteht dabei eine neue Matrix. An jedem Punkt dieser neuen Matrix wird die Summe der komponentenweisen Multiplikation der Zeile der ersten Matrix mit der Spalte der zweiten Matrix eingetragen.

Achtung: Die Faktoren sind nicht austauschbar! Das Ergebnis unterscheidet sich je nachdem welcher Vektor links und welcher rechts steht.

$$
\displaystyle {\begin{pmatrix}\color {OliveGreen}3&\color {OliveGreen}2&\color {OliveGreen}1\\1&0&2\end{pmatrix}}\cdot {\begin{pmatrix}\color {BrickRed}1&2\\\color {BrickRed}0&1\\\color {BrickRed}4&0\end{pmatrix}}={\begin{pmatrix}{\color {OliveGreen}3}\cdot {\color {BrickRed}1}+{\color {OliveGreen}2}\cdot {\color {BrickRed}0}+{\color {OliveGreen}1}\cdot {\color {BrickRed}4}&\ast \\\ast &\ast \end{pmatrix}}={\begin{pmatrix}{\color {Blue}7}&\ast \\\ast &\ast \end{pmatrix}}
$$

### Skalarprodukt

Das Skalarprodukt zweier Vektoren ist die Matrixmultiplikationen des transponierten ersten Vektors mit dem zweiten Vektor. Der Erste Vektor hat dann n Spalten, der zweite n Zeilen. Das Skalarprodukt ist eine Zahl.

### Matrixaddition

Sowohl Zeilen- als auch Spaltenzahl müssen übereinstimmen. Die neue Matrix besteht aus den Summen der Werte an den jeweiligen Stellen der Ursprungsmatrix.

### Determinanten

Determinanten lassen sich nur für quadratische Matrizen mit n Zeilen und Spalten berechnen.

#### Fall n=2

Produkt der Hauptdiagonale minus das Produkt der Nebendiagonale.

#### Fall n=1

Die Determinante ist der Matrixeintrag.

#### Fall n=3

Berechnung mit der Regel von Sarrus oder "Zaunpfahlregel".
$$
\displaystyle \det(A)=a_{\text{11}}a_{\text{22}}a_{\text{33}}+a_{\text{12}}a_{\text{23}}a_{\text{31}}+a_{\text{13}}a_{\text{21}}a_{\text{32}}-a_{\text{13}}a_{\text{22}}a_{\text{31}}-a_{\text{11}}a_{\text{23}}a_{\text{32}}-a_{\text{12}}a_{\text{21}}a_{\text{33}}
$$

#### Fall n > 3

Berechnung mit dem Laplaceschen Entwicklungssatz. 
1. Aufteilung der Matrix in eine Summe kleinerer Matrizen. 
2. Dafür Entwicklung entlang einer Spalte oder Zeile.
3. Jeder Wert dieser Spalte oder Zeile wird multipliziert mit einer kleineren Matrix, die aus allen Werten besteht, die sich nicht in der Spalte und Zeile dieses Werts befinden, sowie mit $(-1)^{i+j}$. Es bietet sich also an, nach Zeilen zu entwickeln, die möglichst viele Nullen enthalten. 
4. Dieser Schritt wird solange wiederholt, bis nur noch Matrizen mit n<4 vorliegen, deren Determinanten berechnet werden können. 
5. Aufsummieren.

#### Bedeutung der Determinante

Wenn die Determinante einer nxn-Matrix ungleich 0 ist, gilt:
1. der Rang der Matrize ist n
2. die Matrix ist invertierbar
3. Cramersche Regel

#### Cramersche Regel

Methode zur Lösung von [[Gleichungen und Nullstellen#Lineare Gleichungssysteme]].
1. Lgs in Matrix überführen, Die jeweiligen Ergebnisse der Gleichungen (rechts des =) dabei in einen separaten Vektor.
2. Die Determinante der Matrix berechnen.
3. Weitere Determinanten berechnen, von den Matrizen die entstehen, wenn man den oben erstellten Vektor in die Spalten der Matrix eintauscht. Dabei entstehen logischerweise n neue Matrizen wobei n die Spaltenanzahl ist.
4. Lösungen berechnen. Die Erste Variable ist dabei die Determinante der Matrix, in der die erste Spalte ausgetauscht wurde, geteilt durch die allgemeine Determinante, die Zweite Variable ist die Determinante der Matrix, in der die zweite Spalte ausgetauscht wurde geteitl durch die Ursprungsvariable und so weiter.

Achtung: Die Übertragung des LGS in die Matrix läuft wie folgt ab: Die Vorfaktoren der einzelnen Variablen werden in eine Matrix überführt. Die Variablen werden herausgezogen in eine Vektor, oben die erste Variable (linke Spalte der Matrix) unten die letzte (rechte Spalte). mit dem Lösungsvektor auf der echten Seite ergibt sich folgendes Schema: $A \cdot \vec x = \vec b$
Wenn man die entstehende Matrix mit dem Variablenvektor multipliziert, erhält man so wieder die ursprüngliche linke Seite des Gleichungssystems.

### Inversen bestimmen

Die Inverse ist die Matrix, die mit der Ursprungsmatrix multipliziert eine Einheitsmatrix ergibt. Inversen gibt es nur bei quadratischen Matrizen, deren Determinante ungleich 0 ist (s.o.).

#### Cramersche Regel II

Zur Berechnung wird die Inverse aufgeteilt: Eine Matrix muss, wenn man sie mit einer Spalte der Inverse multipliziert, genau die korrespondierende Spalte des Einheitsvektors ergeben. So lässt sich die Inversenbestimmung in n (Spaltenzahl) lineare Gleichungen aufteilen.  
Schematisch sieht das wie folgt aus: $A \cdot \text{n-ter Spaltenvektor der Inverse} = \text{n-ter Spaltenvektor der Einheitsmatrix}$

Dann geht es genauso weiter wie oben: 

Der jeweilige Spaltenvektor der Einheitsmatrix wird in jede Spalte eingesetzt, die Determinanten berechnet, und durch die Ursprungsregel geteilt, um den Wert für die jeweilige Variable zu erhalten. Bei einer 3x3 Matrix muss dieser Schritt dementsprechend 9 Mal durchgeführt werden.

#### Gauss-Algorithmus

Simultane Elimination von der Ursprungsmatrize und einer Einheitsmatrix mit gleicher Zeilen- und Spaltenzahl. Die Ursprungsmatrix wird über Gauss zur Einheitsmatrix gebracht, die Matrix die dabei aus der Einheitsmatrix vom Anfang entsteht, ist die Inverse.