#Mathe 

[[Matrizen#Skalarprodukt]]

### Orthogonalität

Zwei Vektoren sind orthogonal, falls ihr Skalarprodukt $(\vec x|\vec y)$ 0 ergibt. 

### euklidische Norm

Die euklidische Norm $||\vec x||$ ist die Wurzel aus dem Skalarprodukt des Vektors mit sich selbst.

### euklidischer Abstand

Der euklidische Abstand ist ist die euklidische Norm der Differenz von zwei Vektoren.

### euklidische Winkel 

Der euklidische Winkel ist der arccos des Skalarprodukts zweier Vektoren durch das Produkt der euklidischen Normen der Vektoren.

### Lineare Unabhängigkeit

Zwei Vektoren sind linear unabhängig, falls sie sich durch keine Skalarmultiplikation ineinander überführen lassen. Bei mehreren Vektoren, Dürfen die Vektoren durch keine Kombination der anderen Vektoren darstellbar sein.

### Unterraum

Der Unterraum U des Vektorraums V beinhaltet folgendes:
1. Wenn er einen Vektor enthält, enthält er auch jeden beliebigen Skalarmultiplizierten Vektor dieses Vektors.
2. Wenn er zwei Vektoren enthält, enthält er auch deren Summenvektor.

Vorstellungshilfe: ein zweidimensionaler Unterraum eines höherdimensionalen Vektorraums ist eine Ebene, ein eindimensionaler eine Gerade und so weiter.

#### Dimension des Unterraumes

Die Dimension bezeichnet die maximal mögliche Anzahl linear unabhängiger Vektoren in einem Unterraum.

#### Basis eine Unterraumes

Eine Basis eines Unterraumes ist ein Vektorsystem, das aus linear unabhängigen Vektoren besteht und den Unterraum aufspannt.

### Kreuzprodukt oder Vektorprodukt

Das Kreuzprodukt ist bildet einen Vektor, der Senkrecht auf der von den zwei Vektoren (Faktoren) aufgespannten Ebene steht. 
Das Kreuzprodukt ist ein Nullvektor, wenn die Vektoren nicht Linear unabhängig sind, da seine Länge dem Flächeninhalt des von ihnen aufgespannten Parallelogramms entspricht.

$$
\displaystyle {\vec {a}}\times {\vec {b}}={\begin{pmatrix}a_{1}\\a_{2}\\a_{3}\end{pmatrix}}\times {\begin{pmatrix}b_{1}\\b_{2}\\b_{3}\end{pmatrix}}={\begin{pmatrix}a_{2}b_{3}-a_{3}b_{2}\\a_{3}b_{1}-a_{1}b_{3}\\a_{1}b_{2}-a_{2}b_{1}\end{pmatrix}}
$$

### Spatprodukt

Das Spatprodukt von drei Vektoren in einem dreidimensionalen Raum entspricht der Determinante einer 3x3 Matrix aus den drei Vektoren. 
Es lässt sich auch wie folgt berechnen: 
1. Kreuzprodukt von zwei Vektoren bilden
2. Vom Ergebnis das Skalarprodukt mit dem dritten  Vektor bilden.

Der Betrag des Skalarprodukts entspricht dem Volumen des von den drei Vektoren aufgespannten Spats (Volumen von [[Elementarzellen]] berechnen!).

### Länge eines Vektors

Die Länge eines Vektors ist die Wurzel aus der Summe der Quadrate der Werte des Vektors.