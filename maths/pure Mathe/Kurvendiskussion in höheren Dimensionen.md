#Mathe 

### Partielle Ableitungen

Für partielle Ableitungen wird immer nur eine Variable abgeleitet, die anderen Variablen werden einfach als Zahlen betrachtet. Ansonsten gelten die bekannten [[Differentialrechnung#Ableitungsregeln]].

### Gradient

Der Gradient ist der Vektor aus den zwei, drei, oder mehr ersten partiellen Ableitungen. Er zeigt zu jedem Punkt (x,y,...), in welche Richtung die steilste Steigung liegt. 

### Hesse-Matrix

Die Hessematrix ist die Matrix, die aus den zweiten partiellen Ableitungen besteht. Dafür wird jede erste partielle Ableitung nochmals partiell abgeleitet. Die Zahl der partiellen Ableitungen steigt so exponentiell mit jedem Grad der Ableitung.

#### Satz von Schwarz

Wenn alle partiellen zweiten Ableitungen existieren, so sind alle Werte in der Hauptdiagonalen der Hesse-Matrix identisch.

### Extrempunkte

Die Stellen, an denen der Gradient ein Nullvektor ist (dafür einfach jede Zeile gleich null setzen und als lineares Gleichungssystem lösen), sind die sogenannten kritischen Punkte. 

Nun wird die [[Matrizen#Determinanten|Determinante]] der Hesse-Matrix überprüft: Ist sie größer als 0, liegt ein Extremwert vor, ist sie kleiner als 0, liegt ein Sattelpunkt vor.

Falls ein Extremwert vorliegt, werden die Werte in der Hauptdiagonale betrachtet.
Sind sie größer als 0, so liegt ein Minimum vor, sind sie kleiner als 0 ein Maximum. 