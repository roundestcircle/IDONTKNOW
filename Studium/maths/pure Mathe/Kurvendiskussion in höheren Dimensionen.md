#Mathe 

### Partielle Ableitungen

Für partielle Ableitungen wird immer nur eine Variable abgeleitet, die anderen Variablen werden einfach als Zahlen betrachtet. Ansonsten gelten die bekannten [[Differentialrechnung#Ableitungsregeln]].

### Gradient

Der Gradient ist der Vektor aus den zwei, drei, oder mehr ersten partiellen Ableitungen. Er zeigt an jedem Punkt (x,y,...), in welche Richtung die steilste Steigung liegt. 

Der Gradient liegt Normal zum Tangentenvektor, entlang dessen keinerlei Steigung in Z-Richtung stattfindet.

#### (Höhenlinien oder Niveaulinien)

Linien, die Normal zu allen Gradienten liegen. Entlang von ihnen findet keinerlei Steigung statt. Mithilfe von ihnen lassen sich dreidimensionale Funktionen in 2-D übertragen: Der Funktionswert der Gleichung wird einfach festgesetzt auf eine konstante C. Wird die Gleichung nun nach Y aufgelöst, erhalten wir eine Zweidimensionale Funktionsschar in Abhängigkeit von C. Je nachdem, welche Konstante wir einsetzen (also welche Höhe), erhalten wir eine Funktion, die die Höhenlinien für genau diese Funktion abbildet.

#### (Richtungsableitung)

Die Richtungsableitung zeigt die Steigung der dreidimensionalen Funktion in eine bestimmte Richtung, von einem bestimmten Punkt aus. Sie setzt sich zusammen aus dem transponierten Gradienten, der mit dem Richtungsvektor multipliziert und dann durch den Betrag des Vektors geteilt wird. Wenn man nun den Punkt und den Vektor einsetzt, erhält man eine Zahl, die dem Anstieg beziehungsweise Gefälle in diese Richtung entspricht, also $\delta z$ pro Einheit.

### Hesse-Matrix

Die Hessematrix ist die Matrix, die aus den zweiten partiellen Ableitungen besteht. Dafür wird jede erste partielle Ableitung nochmals partiell abgeleitet. Die Zahl der partiellen Ableitungen steigt so exponentiell mit jedem Grad der Ableitung.

#### Satz von Schwarz

Wenn alle partiellen zweiten Ableitungen existieren, so sind alle Werte in der Hauptdiagonalen der Hesse-Matrix identisch.

### Extrempunkte

Die Stellen, an denen der Gradient ein Nullvektor ist (dafür einfach jede Zeile gleich null setzen und als lineares Gleichungssystem lösen), sind die sogenannten kritischen Punkte. 

Nun wird die [[Matrizen#Determinanten|Determinante]] der Hesse-Matrix überprüft: Ist sie größer als 0, liegt ein Extremwert vor, ist sie kleiner als 0, liegt ein Sattelpunkt vor.

Falls ein Extremwert vorliegt, werden die Werte in der Hauptdiagonale betrachtet.
Sind sie größer als 0, so liegt ein Minimum vor, sind sie kleiner als 0 ein Maximum. 