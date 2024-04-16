#Stat #Zusammenhänge 

## Einfache lineare Regression

Wir beschäftigen uns zunächst nur mit der einfachen linearen Regression. Um die Berechnungsmethoden nutzen zu können, müssen verschiedene Bedingungen erfüllt sein:

1. nur eine unabh. und eine abhängige Variable
2. lineare Beziehung dieser Variablen

### Regressionsgerade

Die Regressionsgerade ist die Gerade (vorzustellen in einem [[Einführung Zusammenhangsanalyse#Streudiagramme|Streudiagramm]], für die die Abstände der Punkte/Wertepaare zur Geraden minimal sind.Normalerweise werden hier die Abstandsquadrate minimiert, und nicht die Abstände direkt.

Diese Gerade lässt sich durch eine Geradengleichung, die sogenannte Regressionsfunktion beschreiben.

$y = b_0 + b_1x$
$b_0$ ist der Y-Achsenabschnitt,
$b_1$ die Steigung

#### Berechnung eines Erwartungswertes

$\hat{y}_i = b_0 + b_1x_i$

#### Berechnung der Steigung

$$
b_1 = \frac{\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})(y_i-\bar{y})}{\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})^2} = \frac{\text{Kovarianz}}{\text{Varianz}}
$$

Zur Veranschaulichung:
Wenn man hier einen Wert betrachtet (Summen fallen weg, 1/n und ein $(x_i-\bar{x})$ ebenfalls), erhält man ein normales Steigungsdreieck:

$$
b_1 = \frac{(y_i-\bar{y})}{(x_i-\bar{x})}
$$

#### Berechnung des y-Achsenabschnitts

$$
b_0 = \bar{y}-b_1\bar{x}
$$

Anschaulich: Man wandert vom Schnittpunkt der Mittelwerte zur y-Achse. Um sie zu erreichen, muss man $\bar{x}$ mal die Steigung nach links unten laufen.

### Regression in R

[[R for basic stats#Regression]]

### Bewertung der Güte von Regressionsmodellen

Die quadrierten Abstände der Werte können je nach Verteilung größer oder kleiner sein. Dementsprechend sinkt oder steigt auch die Vorhersagequalität des Modells. Mithilfe der Residuen kann die Güte der Regression dargestellt werden.

$$
QS_{Residuen} = \sum_{i=1}^{n}(y_i-\hat{y}_i)^2 = s^2_y
$$

vgl. [[Streuungsmaße#Varianz]]

#### Bestimmtheitsmaß/Determinationskoeffizient

An der Gleichung oben ist zu erkennen, dass der Wert der Residuen mit der Anzahl der Wertepaare steigt. Deswegen wird der Wert zur besseren Vergleichbarkeit normalisiert.

$$
R^2 = \frac{QS_{Schätzwerte}}{QS_{Residuen}} = \frac{s^2_{\hat{y}}}{s^2_y}
$$

Anders gesagt: Theoretische Varianz durch tatsächliche Varianz.
Diese Gleichung bestimmt also den Anteil der tatsächlichen Varianz, die durch die unabh. Variable erklärt wird. Da die Theoretische Varianz eigentlich immer kleiner ist, als die tatsächliche Varainz, kann der Wert nur zwischen 0 und 1 liegen.

Bei einem Wert von über 0.8 spricht man von guter Anpassung, bei über 0.9 von sehr guter Anpassung.

## Multiple Regression

Die multiple Regression wird genutzt, um den Einfluss mehrerer unabh. Variablen zu testen, oder drittvariablen zu kontrollieren.

Die Regression ist dann keine Gerade mehr, sondern eine Ebene, die Gleichung dementsprechend eine Ebenengleichung.

$y = b_0 + b_1x_1 +b_2x_2$

Durch umstellen erhält man leicht die Formel für den Ursprung, doch die Formeln für die Steigungen sind komplexer, sie enthalten Standardabweichungen der einzelnen Variablen und [[Korrelationsanalyse metrischer Daten#Korrelationskoeffizient/Pearson r|Korrelationskoeffizienten]] verschiedener Variablenkombinationen.

$$
b_1 = \frac{r_{yx_1}-r_{yx_2}r_{{x_1}{x_2}}}{1-r_{{x_1}{x_2}}^2} \cdot \frac{s_y}{s_{x_1}}
$$
$$
b_2 = ...
$$

Diese "Steigungen" werden auch partielle Regressionskoeffizienten genannt, sie sind vom Effekt des jeweils anderen Prädiktors bereinigt.